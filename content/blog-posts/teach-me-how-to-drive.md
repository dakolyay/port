+++
author = "Dariya Mukhatova"
date = ""
hero = ""
title = "Locomotion Technique Implementation"
type = "blog"

+++
In this blog post, I will describe the implementation process of the locomotion technique that I have chosen.

In terms of this course, we(students) have been asked to implement one variation of movement in VR. We have been provided with an environment where we could test our implementation related to different features: time, accuracy, playability, level of cause simulation sickness, fun during usage, and feeling of presence. The environment is called [**Parkour**](https://github.com/wenjietseng/VR-locomotion-parkour) which was provided by Wen-Jie Tseng.

You can find the idea for my locomotion technique [**here**](https://app.forestry.io/sites/l07bwi0ocbq4cw/#/pages/content-blog-posts-vr-locomotion-pitch-md/). In short, it is the avatar of the car model which players can drive and fly with it. It is a car for the future and I call my locomotion technique Teach Me How to Drive. There are two reasons for it: I wanted to teach players how to drive a car from the future to learn it in advance, and players can learn how to drive with a regular car.

First of all, I defined the manipulation process. I was thinking between implementing the locomotion technique with relation to the steering wheel and without. Because I wanted to make the game more intuitively and let players control the car with their understanding of hand position rather than checking every time the steering wheel and relying on it. But at the same time, I wanted to add the steering wheel only for guidelines.

I defined the position of both right and left controllers.

    leftPositon = OVRInput.GetLocalControllerPosition(leftController);
    rightPosition = OVRInput.GetLocalControllerPosition(rightController);

In a state where both of the controllers stay in a relatively equal position player will not turn anywhere and gonna stay straight. But if the user would like to turn left or right the controllers should change the position of height related to each other. I prevented the possibility of a controller switch by checking the positive value of the difference _dif_.

    dif = leftPositon.y - rightPosition.y;

![](/images/2022-02-28-16-16-42.png)

Now, I could turn my player to left and right and I realise that I have one bug. It was a camera and all the time when the player wanted to turn left or right the direction he/she was facing was left or right respectively. 

All the cars have some brake and speed up so I added acceleration and brake. I defined them as a value from a triggering certain trigger button on controllers. 

    acceleration = OVRInput.Get(OVRInput.Axis1D.SecondaryHandTrigger);
    brake = OVRInput.Get(OVRInput.Axis1D.PrimaryHandTrigger);
 fdlfd