---
title: Out-Of-Bound
date: 2019-06-30T19:17:43+00:00
type: blog
hero: "/images/oculusguardiansystem-scaled.jpeg"
author: Dariya Mukhatova

---
### **Motivation**

These days, users of VR systems are often injured while using these techniques and such cases are not uncommon and arise both for beginners who have tried it for the first time as well as for experienced users. For such reason, VR companies invented _Safety Mechanisms_ to protect their customers. Unfortunately, they did not completely stop the incidents that appeared in process of use. With the members of [the DIVA Research group](https://diva.telecom-paristech.fr)       Jan Gugenheimer and Wen-Jie Tseng, we want to pay attention to this issue.

Safety mechanisms nowadays are mostly rendered as a grid surrounding the user. For our convenience, we have denoted the term _“breaking out”_ which stands for any attempt to somehow violate the boundaries of the security mechanism, albeit in whole or in part.

Our motivation is to reduce the number of breaking out attempts as well as the number of incidents and accidents caused by the use of virtual reality systems. This could be accomplished by understanding what these new technologies are missing now. So the purpose of our work is to understand how users feel about this safety technique and to analyze how really useful they are.

![](/images/futureofvr_getty_ringer-0.jpg)

### **A New Blood**

["A persons who are accepted into a group or organization and are expected to provide fresh ideas and vitality."](https://www.merriam-webster.com/dictionary/new%20blood)

To address the lack of data on the user experience of safety technologies, it was decided to conduct our own research. The best option was to organize a survey with the key points that interested us.

As a newcomer, my work began with testing the water. In a short time, I had a chance to plunge into the world of virtual reality, go through half of [the Half-Life: Alyx](https://www.half-life.com/ru/alyx/), read about VR Fails and become sufficiently aware of the world of Virtual Reality.

The next stage of the process is the most important one - survey construction. Due to multiple iterations for the purpose of getting the best version this stage also became the longest. It was decided to create a survey on Google Forms by the reason of its clarity and convenience. With 48 questions of different categories, we published it on [Amazon MTurk](https://requester.mturk.com/create/projects), also between the DIVA research group and platform for VR research projects - [XRDNR](https://www.xrdrn.org/2021/06/experiences-and-attitudes-towards-the-safety-boundaries-in-virtual-reality/).

![](/images/2021-08-19-10-07-56.png)

1. Have you ever customized your safety mechanism with additional props, software or physical tools? (Yes/No)
2. Have you ever modified your safety boundary's default settings? (e.g., decrease or Increase proximity sensitivity, grid colour). (Yes/No)
3. Have you ever broke out of the safety boundary during a VR experience? We define the "breaking out" as leaving the safety boundary with any body part (e.g., controller, headset). (Yes/No)

It is important to mention that our research concerned only a special narrow circle of society. We examined people who actively used virtual reality technologies, thereby claiming that they have sufficient experience to fully answer our questions. As a result, we collected 191 responses, but unfortunately, not all of them were approved. I was in charge of the process of selecting and collecting the correct answers which were done manually as there was a lot of incorrect data and a lot of open questions.

![](/images/pie.png)

After collecting the answers, for the exact purpose of data analysis, a very long process of cleaning and preparing the data began. The questionnaire was in a CSV format and had open-ended questions like text also numeric values, scale values, categorical values, and lots of nan variable blanks. The particular reason for the circumstance of having empty data appeared due to the fact that not all participants answered these questions because they did not go further to the section where they were asked.

![](/images/2021-08-19-10-41-15.png)

lbhgcd

![](/images/2021-08-19-10-51-45.png)

klkvgfc

![](/images/worldcloud.png)

![](/images/2021-08-19-12-39-40.png)

The most popular pair of two positive signs are **safe and easy** meanwhile for negative signs are **risky and unproductive**.

During the breaking out, the most common application type was Gaming(**90%, wow**)

![](/images/2021-08-19-11-31-57.png) and in the list of applications, the dominant part is adventure shooter videogames (Half-Life: Alyx, Minecraft, Jurassic world, Zombie shooter, Gorn, Saber Fight VR, The Elder Scrolls V: Skyrim VR, Star Trek: Bridge Crew, Superhot VR, Vader Immortal: Episode I et cetera). All these games involve continuous movement and imitation of life activity. It gives a hint to us that breakouts have a connection to the number of movements made during use.

### What we learned:

* The more user has to perform physical actions the higher the probability of breaking out.
* For the user, the biggest drawback is not in the technical form of implementation, but in how this form irritates them. This means that it is worth choosing a different way of forewarning users than today's multi-coloured grids.