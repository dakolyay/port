+++
author = "Dariya Mukhatova"
date = ""
hero = ""
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

* Change the name of Plane:

  ![](/images/7.png)
* Reset the transform field to make position equal to (0,0,0):

  ![](/images/7-5.png)
* Make the plane big since we will need enough space to roll our ball: 

  ![](/images/8.png)
* It will be also good to distinguish the plane from anything else from the scene and make it more custom. So we will add a material to the plane by choosing Materials in Assets in the menubar.

  ![](/images/10d.png)Now we can edit the material how we want and assign it to the plane by dragging and dropping it. 

  ![](/images/11.png)![](/images/12.png)

  Now we have our custom plane and we would like to place an actual ball on it.

  Since the ball it is a sphere we can add it to our scene with the same process as with plane: 

  ![](/images/13.png)

  Voila! We can see the ball on the plane. For now, it has initial settings which we will further change:

  ![](/images/14.png)  
  ![](/images/15.png)

  fdlfkd

  ![](/images/16.png)