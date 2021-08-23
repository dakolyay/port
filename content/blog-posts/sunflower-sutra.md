---
title: Out-Of-Bound
date: 2019-06-30T19:17:43+00:00
type: blog
hero: "/images/oculusguardiansystem-scaled.jpeg"
author: Dariya Mukhatova

---
### **Motivation**

Virtual reality is progressive technology these days. Thanks to them, we discovered a new type of interaction with information by the creation of a simulated environment. They open doors to new ideas and opportunities and their use is slowly becoming part of the routine of everyday life. But as exciting as they are, the experience[\[1\]](https://dl.acm.org/doi/10.1145/3411764.3445435) has shown that we are not fully prepared to use them safely. Users are often injured while using these techniques and such cases are not uncommon and arise both for beginners who have tried it for the first time as well as for experienced users. This is such a frequent occurrence that it deserves the term “_VR fail_”. Based on this, the companies of VR systems presented various techniques whose main goal was to keep the user safe as it was named _safety mechanisms_ (SF). Safety mechanisms nowadays are mostly rendered as a grid surrounding the user whose boundaries signal a users' close position or contact with the border.

For our convenience, we have denoted the term “_breaking out_” which stands for any attempt to somehow violate the boundaries of the  SF, albeit in whole or in part.

Our motivation is to reduce the number of breaking out attempts as well as the number of incidents and accidents caused by the use of virtual reality systems. This could be accomplished by understanding what these new technologies are missing now. So the purpose of our work is to understand how users feel about this safety technique and to analyze how really useful they are.

![](/images/futureofvr_getty_ringer-0.jpg)

### **Problem**

### **Method**

It was decided to identify the key points and consider the problem in detail. However, the lack of information according to safety mechanisms as well as the information about users experiences with them in VR led us to run our own survey. We conducted an online experiment that investigates respondents’ behaviour inside safety boundaries and during _the_ _breaking out_ process along with what were the border settings at that time. We focused on the public, which should be actively using VR headsets with inbuilt SM. The survey was created on[ Google Forms](https://www.google.com/forms/about/) for the reason of its clarity and convenience. Due to multiple iterations which were done in order to get an optimal version of the survey two surveys were compiled. Only open-ended questions of the pilot survey will be considered. The pilot survey was published on different platforms like Reddit, XRDNR, also between [the DIVA research group](https://diva.telecom-paristech.fr). The second survey was posted on Amazon MTurk. The second survey covers demographic questions, questions about how participants act in VR also what brought them to act like that, plus personal feedback:

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

As a result, we received 14 answers from the pilot survey and 48 answers from Amazon MTurk.

Demographics

### **A New Blood**

["A persons who are accepted into a group or organization and are expected to provide fresh ideas and vitality."](https://www.merriam-webster.com/dictionary/new%20blood)

![](/images/2021-08-19-10-07-56.png)

1. Have you ever customized your safety mechanism with additional props, software or physical tools? (Yes/No)
2. Have you ever modified your safety boundary's default settings? (e.g., decrease or Increase proximity sensitivity, grid colour). (Yes/No)
3. Have you ever broke out of the safety boundary during a VR experience? We define the "breaking out" as leaving the safety boundary with any body part (e.g., controller, headset). (Yes/No)

It is important to mention that our research concerned only a special narrow circle of society. We examined people who actively used virtual reality technologies, thereby claiming that they have sufficient experience to fully answer our questions. As a result, we collected 191 responses, but unfortunately, not all of them were approved. I was in charge of the process of selecting and collecting the correct answers which were done manually as there was a lot of incorrect data and a lot of open questions.

![](/images/pie.png)

After collecting the answers, for the exact purpose of data analysis, a very long process of cleaning and preparing the data began. The questionnaire was in a CSV format and had open-ended questions like text also numeric values, scale values, categorical values, and lots of nan variable blanks. The particular reason for the circumstance of having empty data appeared due to the fact that not all participants answered these questions because they did not go further to the section where they were asked.

![](/images/2021-08-19-10-41-15.png)

### Data Analysis

Description of the given sizes of borders and rooms(in meters) and user's frequency(in a month) and hours spent per week during VR.

![](/images/2021-08-19-10-51-45.png)

* To understand what is the first thing that comes to people’s minds according to safety mechanisms, we asked them to list three positives and negatives. Then we coded them into a word cloud. The most frequent positive association will be **safe** and the most frequent negative will be **annoying**. This actively demonstrates that the safety mechanism does its work correctly and users do not complain about technical shortcomings, but about the format of the implementation of these techniques.

![](/images/worldcloud.png)

![](/images/2021-08-19-12-39-40.png)

The most popular pair of two positive signs are **safe and easy** meanwhile for negative signs are **risky and unproductive**.

* During the breaking out, the most common application type was Gaming(**90%, wow**) and in the list of applications, the dominant part is adventure shooter videogames (Half-Life: Alyx, Minecraft, Jurassic world, Zombie shooter, Gorn, Saber Fight VR, The Elder Scrolls V: Skyrim VR, Star Trek: Bridge Crew, Superhot VR, Vader Immortal: Episode I et cetera). All these games involve continuous movement and are action-heavy. It gives a hint to us that breakouts have a connection to the number of movements made during use.

![](/images/2021-08-19-11-31-57.png)

* Participants who have not broken out from safety boundaries mostly triggered it with **"Breaking out of the boundary with the controller (or hand)"** and **"Approximating the boundary but not breaking out"**. Сuriously enough in most cases, they do stop their actions during VR if participants are too close to boundaries or made it show up because of the controller.
* We can see the only positive correlation between columns FeelAnnoyed and ContinueAction. As well shown in the diagram of the Likert scale below it is clear that more participants are more likely to disagree with these two statements: (a) **The VR safety boundary makes me feel annoyed.** and (b) **I do continue my action in spite of the warning of VR boundaries.**

![](/images/2021-08-19-1-16-39.png)

![](/images/2021-08-19-1-14-24.png)

![](/images/image.png)Thanks to Wen-Jie Tseng.

### **What we learned:**

* The more user has to perform physical actions the higher the probability of breaking out.
* Although most users rarely notice boundaries and just as rarely violate them, they immediately rethink their actions and stop after triggered boundaries appear. This is what the third observation can tell us.
* For the user, the biggest drawback is not in the technical form of implementation, but in how this form irritates them. This means that it is worth choosing a different way of forewarning users than today's multi-coloured grids.
* Since more people find SM annoying they easily neglect them.

### **Future Work**

For future work, it could be useful to recruit more people in order to have more practical information. As an idea, further experiments could be arranged in real-time in which the participants will have to complete the VR game where they will need to avoid the barriers and obstacles.

![](/images/is.png)