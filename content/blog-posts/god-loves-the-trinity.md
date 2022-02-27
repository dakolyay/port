+++
author = "Dariya Mukhatova"
date = ""
hero = "/images/three-706895_960_720.jpg"
title = "3 ideas of VR Locomotion Technique"
type = "blog"

+++
The locomotion technique is the way to maintain movement in the VR world and it is an important and interesting idea. Because VR is relatively new and we have all got used to the movement technique we do in PC. The philosophy of the movement technique in the virtual world is more close to our real-life movement because the main point of VR is to be as real as the real environment. Locomotion techniques can differ from each other because we do various types of movement related to an activity we are accomplishing. We walk, we drive, we jump, we crawl, we climb and any other type of action we perform to reach the destination.

The locomotion technique in VR has its own feature which you should keep in mind to get the best solution. Accuracy, speed, feeling immersion into VR, and other features are crucial

No matter how good is locomotion technique we have to think about simulation sickness as well. According to Wiki:

> Simulator sickness is a subset of motion sickness that is typically experienced while playing video games from first-person perspective.

For the game industry, it is a challenge to create a locomotion technique in VR that will decrease the simulation sickness, follow the philosophy of movement physics in real life, be accurate, easy to use, not too complex, and still be fun to use.

After a small intro about what is locomotion technique is, in this blog post, I will present three ideas for locomotion movement in VR which could be implemented during this course.

#### Skiing locomotion

The first locomotion technique that came to my mind and that I like the most among the next three is the skiing locomotion technique. The idea of this skiing movement came to me during Christmas vacation 2022 which I spend in my hometown. One of the must-do during winter in Almaty is the winter sports and activities. (1st reason the weather condition, 2nd it is really cheap in comparing with other ski resorts). The motivation behind the skiing locomotion technique was the idea that not all people have a chance to ski in real life because of different reasons.

One of the ways to make this skiing locomotion is to utilize the controllers.  Same as an actual skiing walk the position of arms and sticks in these arms play an important role. Both of the arms will be associated as controllers. The movement towards will be performed by considering the relative position of the controllers with each other. Here we can also describe the velocity. With bigger differences between the controllers, there will be a bigger push forward so the faster user can get to its destination. There is classical walking skiing. Besides, there is another way to ski walk where you pull your both arms with sticks at the same time.

![](/images/overview-of-the-techniques-gears-employed-in-classical-cross-country-skiing-dp-double.png)For this project, I chose the first type of walking. I want to make this locomotion as fun as real skiing. I have some doubts about the rapidity because performing necessary physical efforts here can take time.

It would be very interesting to know how many times people can go through parkour and at what point it will become difficult for them because of the arm movement they have to do.

![](/images/2022-02-27-11-33-49.png)

#### Clown walk

Of course, the name may shock you, but in fact, it is a completely harmless form of movement. Maybe you've ever seen clowns or street performers in the square, entertainment fairs, or even on TV who walk on very long legs. actually, it's not their legs (sorry kids) but very long sticks.

![](/images/174429453_e8d499ad51_b.jpg)

This technique will be a bit like teleportation because users will throw one leg forward as far as they can and drag the other leg to stand on two legs. This will of course will be long because the clown will only move by performing stepping forward with one leg and another. But the main metric here is fun. I want to add a sense of balance, that the longer you stand on two legs the more you stagger. This will make the users move forward faster which will be more exciting.

![](/images/2022-02-27-10-48-45.png)

#### Flying boots

This locomotion technique idea came to me itself while I was visiting my best friend and her family. Since she is half English her family had an English channel on TV.  I paid zero attention to the TV during the dinner we had until the time [**this**](https://www.youtube.com/watch?v=e9RMybk7jsY) advertising came out. In the advertising, there is Aunt Helga who puts on reactive boots that allow her to fly. But we also want to move forward.

For this locomotion technique, users could move forward with flying boots. Same as Aunt Helga, we will use the left boot to fly and the right boot which is placed in position so jet gas will go behind allowing us to move ahead.

Here I want to focus more on speed and fun. As well it can be accurate enough. Unfortunately, probably there will be some simulation sickness but not a lot because the user will have to control avatar-Aunt Helga.

![](/images/helga-hed-2021_0.jpg)

To implement this I will trigger buttons on the controller. One of them will be responsible for flying, the other for going forward. If the user will not trigger the flying button then Aunt Helga will go forward by running on the street in Parkour. The moment user will trigger the button to fly Aunt Helga will go up at some height and can fly ahead if the user will also press the forward button.

![](/images/2022-02-27-11-14-45.png)