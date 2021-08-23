---
title: Out-Of-Bound
date: 2019-06-30T19:17:43+00:00
type: blog
hero: "/images/oculusguardiansystem-scaled.jpeg"
author: Dariya Mukhatova

---
### **Motivation**

Virtual reality is progressive technology these days. Thanks to them, we discovered a new type of interaction with information by the creation of a simulated environment. They open doors to new ideas and opportunities and their use is slowly becoming part of the routine of everyday life. But as exciting as they are, the experience[\[1\]](https://dl.acm.org/doi/10.1145/3411764.3445435) has shown that we are not fully prepared to use them safely. Users are often injured while using these techniques and such cases are not uncommon and arise both for beginners who have tried it for the first time as well as for experienced users. This is such a frequent occurrence that it deserves the term “_VR fail_”. Based on this, the companies of VR systems presented various techniques whose main goal was to keep the user safe as it was named _safety mechanisms_ (SM). Safety mechanisms nowadays are mostly rendered as a grid surrounding the user whose boundaries signal if the user is too close to them or if the user contacts with the border. For our convenience, any effort to somehow violate the boundaries of the SF, albeit in whole or in part we have denoted as “_breaking out_”.

Our motivation is to reduce the number of breaking out attempts as well as the number of incidents and accidents caused by the use of virtual reality systems. This could be accomplished by understanding what these new technologies are missing now. So the purpose of our work is to understand how users feel about this safety technique and to analyze how really useful they are.

![](/images/futureofvr_getty_ringer-0.jpg)

### **Problem**

### **Method**

It was decided to identify the key points and consider the problem in detail. However, the lack of information according to safety mechanisms as well as the information about users experiences with them in VR led us to run our own survey. We conducted an online experiment(N=62) that investigates respondents’ behaviour inside safety boundaries and during _the_ _breaking out_ process along with what were the border settings at that time. We focused on the public, which should be actively using VR headsets with inbuilt SM. The survey was created on[ Google Forms](https://www.google.com/forms/about/) for the reason of its clarity and convenience. Due to multiple iterations which were done in order to get an optimal version of the survey - two surveys were compiled. However, only open-ended questions of the pilot survey will be considered. The pilot survey was published on different platforms such as Reddit, [XRDRN](https://www.xrdrn.org/about/), also between [the DIVA research group](https://diva.telecom-paristech.fr) members. The second survey was posted on Amazon MTurk. The ameliorated survey covers demographic questions, questions about how participants act in VR also what brought them to act like that, plus personal feedback:

1. **Demographics**(n=10).
2. **Set up Safety Boundaries**(n=13). Questions asked was related to default settings and their modification together with customization of safety mechanism.
   * General setting up(n=8)
   * Customizing the VR safety boundaries(n=2)
   * Modify safety boundaries' default settings(n=3)
3. **While using VR**(n=22):
   * Attitude towards safety mechanism(n=9). This section has two 5-point scale questions about the frequency of notification and any kind of violation of safety boundaries, seven 5-point Likert scale questions ("strongly disagree" - "strongly agree") about safety mechanisms' performance from participants view.
   * Triggering the safety boundary(n=4). Questions of this section relate to how participants triggered safety boundaries warnings and what was their actions after it.
   * When breaking out happens(n=6). We are interested to know did triggering boundaries of SF led to _breaking out_ experience. If it was a case, what was the overall situation and what were the reasons and settings during it?
   * Inside the safety boundary(n=3). On the contrary, If there were not any _breaking out_ experiences, we are curious to know what made participants stay inside safety boundaries.
4. **Personal feedback on the VR safety boundaries**(n=3).

![](/images/demographics-and-backgrounds.png)

As a result, we received 14 answers from the pilot survey and 48 answers from Amazon MTurk.

_Demographics:_  
As mentioned above our research concerned only a special narrow circle of society. We examined people who actively used virtual reality technologies, thereby claiming that they have sufficient experience to properly answer the questions.

The results are based on respondents, who completed the MTurk survey. 59% of the respondents were male. The respondents ranged in age from 20 to 63, with an average age of 32 (standard deviation 9.1). Among 48 participants, 73% declare themselves as Gamers(35), 17% as Developers(8) and 10% as Designers(5). The majority held a Bachelor's degree(56%).

![](/images/demo1.png)

The proficiency of users was counted in months, therefore participants have on average a bit less than 2 years (21 months) of frequent user experience. The "newbies" are considered as frequent users only since June(2 months) when the "skilled" are in VR 5 years already(62 months).

According to the survey's result [ Oculus Quest 2](https://www.oculus.com/quest-2/) is the most used VR headset (31%) followed by  [Oculus Rift](https://www.oculus.com) (27%) and [Oculus Quest 1](https://www.oculus.com/quest/features/) (16%) that respondents chose as the device they are more familiar with and besides, they turned out to be the most sold among the audience (16 customers of Oculus Quest 2 and Oculus Rift & 15 of Oculus Quest 1).

Generally, the respondents used a VR headset 10.6 hours per week (1,77 per day) in the range from 1 to 30 hours per week. The majority spend this time equally between standing and sitting positions (27%). Participants did not show any preference in the type of VR setting (room-scale, stationary) which they set with proportion 50/50 of all the time spent in VR.

1. rectangles -> room
2. Likert scale
3. presentation
4. open-ended questions
5. method
6. word cloud

### **What we learned:(Conclusion)**

* The more user has to perform physical actions the higher the probability of breaking out.
* Although most users rarely notice boundaries and just as rarely violate them, they immediately rethink their actions and stop after triggered boundaries appear. This is what the third observation can tell us.
* For the user, the biggest drawback is not in the technical form of implementation, but in how this form irritates them. This means that it is worth choosing a different way of forewarning users than today's multi-coloured grids.
* Since more people find SM annoying they easily neglect them.

### **Future Work**

For future work, it could be useful to recruit more people in order to have more practical information. As an idea, further experiments could be arranged in real-time in which the participants will have to complete the VR game where they will need to avoid the barriers and obstacles.