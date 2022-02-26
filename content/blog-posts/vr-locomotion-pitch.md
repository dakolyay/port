+++
author = "Dariya Mukhatova"
date = ""
hero = ""
title = "VR Locomotion Pitch"
type = "blog"

+++
My initial idea for the locomotion technique which I wanted to implement was [**skiing**](https://drive.google.com/file/d/1SEJKd4w7FolLSJmBBUw7AIw2vWkmVanv/view?usp=sharing). I got inspired by a mountain skiing walk that practice often in my hometown. As well I got inspiration from the [**demo**](https://www.youtube.com/watch?v=9EQ3ZR57O6w) of a Skiing game that I found on YouTube. 

But...

My final idea for the locomotion technique, which I implemented as the final project was not skiing. There were several reasons why I changed my mind. 

1. It was challenging to implement the whole range of movement with the skiing locomotion technique. Because the whole process of movement during skiing is to maintain your legs muscles as well as arm muscles. It did not sound to me right to implement this technique and ignore the leg movement which was crucial in this type of movement. 
2. I found that there is no way to make a 180-degree turn.
3. As well as a person with no experience in Unity I should also keep in mind the complexity of implementation. Working with skiing physics and arranging all the small details to make the technique as real as it should sound really hard.
4. Obligatory arm movement from some degree to some degree which is the main source of your movement during the whole Parkour sound to be really exhausting and did not stick with the view for locomotion technique I wanted to have in the end. 

So I decided to implement a car movement locomotion technique. But instead of classing steering wheel controlling car I wanted to implement a flying car of the future that will both have a driving and flying ability. I found it really interesting after rewatching one of my favorite movies of all time [**the Fifth Element**](https://www.imdb.com/title/tt0119116/). The [**part**](https://www.youtube.com/watch?v=24bRtzwK4rY) where we can witness the future Manhetten with all this flying version of cars and yellow taxi cars, that became already sightseeing of New York. 

![](/images/flying-car1.jpg)

I saw this locomotion technique as avatar movement where you can control your driving car using your controllers. It would be possible to turn the car left and right, as well as take off up and land. For controlling it from side to side it was decided to use controllers orientation towards each other, and for managing flying it was decided to assign special buttons on controllers. Since it was a car it has to have both brake and acceleration. 

This locomotion technique was named unofficially TeachMeHowToDrive. Because it could teach us the concept of driving for future cars and simulate the driving process for people who do not have driving experience. The most important features are speed and accuracy. It is not surprising, since this locomotion technique still follows the prototype of the car where we need to be accurate to avoid accidents and fast to not cause accidents and reach our destination point. I not expecting a lot of simulation sickness because the user will control the car model.

After summing up all the needed functionality and having overall view of the future project the next challenge was to actually make this idea real. 

![](/images/tf4z0z8x7mr61.jpg)