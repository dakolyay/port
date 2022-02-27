+++
author = "Dariya Mukhatova"
date = ""
hero = "/images/9c1b8f97-0af3-466d-889c-23dc08fdc49e.jpeg"
title = "Roll-A-Ball"
type = "blog"

+++
There is a really goodly explained tutorial for beginners who just started to work with Unity. It is called [**Roll a Ball**](https://learn.unity.com/project/roll-a-ball) where you will have to create a mini-game with the ball in the closed territory and collect points by hitting the collectibles.

I found this tutorial quite easy to do and well explained. In this blog post, I will summarize the most important parts of Roll A Ball implementation.

First of all, we have to create a new project. To do so we launch Unity and press the _New_ button. You can always continue with the existing project by adding it to the projects window in Unity.

![](/images/screenshot-2022-02-27-134851.png)

For this project, we will choose a 3D project because we would like to have a game in a 3D envirolment.  
![](/images/screenshot-2022-02-27-135158.png)

First thing that we will have to do when we will launch our just created project is to create a scene. There are different ways to do so and this is one of them:

![](/images/screenshot-2022-02-27-135615.png)

After we will have our scene it will be nice to have some kind of flatness on which we will put our balls and collectibles. It is not complicated and we have to follow the same process:

![](/images/5.png)

As a result, in your scene we will have a plane which was created to initial position (0,0,0).

![](/images/6.png)

There are some modifications we still have to do:

Change the name of Plane:

![](/images/7.png)

Reset the transform field to make position equal to (0,0,0):

![](/images/7-5.png)

Make the plane big since we will need enough space to roll our ball:

![](/images/8.png)

It will be also good to distinguish the plane from anything else from the scene and make it more custom. So we will add a material to the plane by choosing Materials in Assets in the menubar.

![](/images/10d.png)

Now we can edit the material how we want and assign it to the plane by dragging and dropping it.

![](/images/11.png)![](/images/12.png)

Now we have our custom plane and we would like to place an actual ball on it.

Since the ball it is a sphere we can add it to our scene with the same process as with plane:

![](/images/13.png)

Voila! We can see the ball on the plane. For now, it has initial settings which we will further change:

![](/images/15.png)

We will rename the GameObject as Player and reset its transform field in inspector.  
![](/images/14.png)

Next, we will create new material for a ball and attach it to the Player.

![](/images/16.png)

We want to play with the ball and control it. To do so we will have to go to Package Manager and find Input System. So we will apply the keyboard input to control the ball's movement on the plane.

![](/images/16-5.png)![](/images/17.png)After the installation and rebooting Unity, we will go to the Player's inspector field and add a new component. Adding new components to our GameObjects allows us to customize and modify them for our needs.

![](/images/18.png)

After adding a Player Input component to Player we will press Create action.

![](/images/2022-02-27-17-56-58.png)

![](/images/20.png)We will drag this .inputaction file to the Actions field in the Players Input component in the Inspector. This will allow us to access the information for control devices but yet we can not move our ball.

It is important to change your building settings if you are thinking to work on Windows we have to change the Architecture to x86_64 by following File and Build Settings.

![](/images/27.png)

In order to control and move the ball, we will create a script. In Unity, we will have to write code time to time in C#.

![](/images/22.png)![](/images/23.png)For now, there is not much code in PlayerController. We will do some modifications to it. We will add the line of code which allows us to work further with InputSystem package.

![](/images/24.png) 

We will create a void function OnMove where we will add force to the rigid body