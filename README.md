# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Kyle Zhou

_Student NetID_: qz30

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Grading}
- Assumptions:
  - The homework is a coding project submitted onto Github Classroom. No one has access to my Github account. This a graduate level course.
- Assets:
  - Original work(No plagiarism). The first asset is a student's original work. This asset needs to be protected because it motivates students to explore different solutions and potentially learn more than what has been taught in the class. If this asset is not protected, students who are less willing to think on their own or are trying to maximize their grade will simply give up and copy code he found online. On the other hand, protecting original work helps the instructor see how well students actually learned in class instead of seeing one student's (refactored) work repeatedly which falsely represents the true outcome of a class.
  - Students' opportunities to learn. Although this may sound politically incorrect, students can still learn even if they copy form others. The reason why this is considered as an asset is because it is impossible eliminate plagiarism, and when we can not guarantee orignal work, hoping that the student can at least learn something becomes the secondary goal.
- Threats:
  - Student copy code from previous semesters: this threat has two sides, the supply side is that students who have came up with interesting, orignal answers are likely to post them in a public repository on Github as a demonstration of their coding skills, which might help when they are looking for a job. The demand side is students who are currently taking the class is running out of time, don't know how to complete the assignment, or is trying to maximize their grade by copying a "verfied" project. Although students are generally not allowed to post their code in public repositories, many of them still post them after graduation (because they have to demonstrate their coding skills with something, and code from work/internship generally can not be posted due to confidentiality). Since most coding assignments are not changed for many semesters, this is a common threat to some students' original work.
  - Student copy code from classmates: this threat happens when the assignment has some changes or no existing work can be found online. This threat is harder to detect, since instead of copying from a publicly known Github/Bitbucket repository, students copy from each other, and without knowledge of students' friend circle there's no way to quickly find out which student copied code from another student. Although there are some anti-cheat tools like Moss which may help, there are many flaws that can help a student bypass the system. The existence of late days and the fact that most students want a grade before the next assignment make detecting plagiarism much harder. 
- Countermeasures:
  - Make small changes to assignment each semester: this countermeasure aims to encourage original work. Students who graduated and put projects online are unlikely to be regulated, but students who are currently taking the course will consider the consequence of sharing code because of the honor code and the following punishments. Therefore, making changes to the assignment each semester can potetnially prevent students from copying from previous projects. In the case of making small changes to the assignment, some students may still look at past projects to guide their thought, and there is almost no way to completely eliminate this situation. However, students' opportunities to learn is still partially guaranteed, since they have to understand the previous projects and extract useful concepts.
  - Ask the students to write a report explaining what they have done: this countermeasure is used to make sure students understand what the program is doing (even when they are copying from others). The extra steps of writing a report should make copying code much more difficult and easier to be found out. Students who can writing working code but can not give good explainations can be easily found out. If students copy code, understand it, then write the report with enough explainations, the asset of opportunities to learn is still protected (because there is no way to know if a student copied or not in this case, and this is the compromise we have to make to give out grades on time).

## Problem 2
- Scenario: {TSA}
- Assumptions:
  - We have sniffer dogs. We have Itemiser 3 Enhanced (detects explosives (+/- ions) and some drugs). The airport is like IAH. We background checked all the employees.
- Assets:
  - Safety of individuals inside building but outside of security checkpoint: most airports only check to make sure no dangerous items can be brought onto the plane. However, people outside the security check point can still be in danger. This asset includes passengers, airline staff, TSA staff, airport staff and so on.
  - Safety of individuals passed security checkpoint (includes passengers on a flying aircraft): this asset is harder to protect compared to the first one if the individuals are already on a plane (there are federal air marshall officers, but situation can be hard to control while flying on a plane).  
- Threats:
  - Terrorists trying to kill people in the check-in zone (outside of security checkpoint): this is a threat sometimes seems to be ignored. During busy hours, there are hundreds of people waiting to check in, and due to the design of most airports, these people generally stand closely, which is a great target for explosives. Explosives can either be in a luggage or be suicide bombs carried by terrorists. Although most airports nowadays ask passengers to report luggages left in public area, explosives can still be carried by a suicidal terrorist. This threat becomes more serious during holidays and weekends due to the large amount of passengers.  
  - Terrorists trying to kill people inside the security checkpoint: this is the threat that most security checkpoint is designed for (TSA created after 911). This threat has two part: 1. threat to passengers in the airport 2. threat to passengers on the plane and people in target location (hijacked like 911). The first part of the threat is similar to the previous threat. At each gate there are many passengers (especially right before boarding) that can become target of terrorists. The second part of this threat is even more serious because of the destructive power of hijacking a plane.
- Countermeasures:
  - Setup additional secuirty checkpoints at building entrance/elevators in the check in area: the number of open entrance can vary depending on the estimated number of passengers. Deploy K9 units and Itemiser 3 Enhanced machines at each gate and check individuals in batches (like 8 - 10). These checkpoints are used to make sure no explosives can be brought into the building, which protects both assets discuessed. Sniffer dogs should be roaming around the check in area as secondary check points. This countermeasure not only protects people outside security checkpoints (for luggage) but also people inside security checkpoints.
  - Setup security checkpoints to scan luggages and personal belongings: this is the widely used way to detect potential threats. If enforced properly, the second asset can be well protected. Any passengers, airlane staff, or even coffee shop staff should be properly checked to make sure no life-threatening tools and items can pass the security checkpoint.

## Problem 3
- Scenario: {Cheater: You are cheating on your wife (just don't do it in real life), and you need to keep in touch with your mistress 24/7 without being found out} 
- Assumptions:
  - Your wife can access your phone whenever she wants. You have time to close any apps before giving your wife the phone. You can code. Your wife can check any apps on the phone. If you do not contact your mistress frequently, she will be mad and contact your wife (game over). (I'm not married.)
- Assets:
  - Wife stays uninformed: this asset needs to be protected because you do not want to lose half the money/the kids. You may still keep the second asset even if you lose this asset, but it will have a big cost.
  - The chance to contact your mistress: this asset also needs to be protected because you are greedy. If this asset is not properly protected, the first asset will be lost too (see assumptions).
- Threats:
  - Your wife may take your phone and find out that you are texting your mistress: you are done. This is a common scenario/threat because nowadays many messaging apps syncs across different devices, and some deleted messages can be restored with the help of online tutorials. Since messaging apps may have updates that are easily ignored by users (like new sync feature), the threat is really dynamic.
  - Your mistress is not getting enough attention, gets mad, and contacts your wife: you are done. This is another common scenario since sometimes a mistress may be seeking revenge for lack of attentions. This is an unpredictable threat which needs to be handled with preventative approachs.
- Countermeasures:
  - Write a customized app that has secret messaging features: using built-in messaging apps or other popular messaging apps can be dangerous due to the unpredictable syncs and the lack of time to destroy evidence. However, both assets can be protected with a reliable, secret messaging app. The app can not have any notification features to protect the first asset. Building a server for the customized app is easy, but the mobile app frontend itself has to be disguised. An example in iOS will be to have a series of hidden buttons which bring out the message feature when pressed in a pre-defined sequence using 3D touch (and disable the default vibration response for 3D touch for the buttons). When the app is designed properly, even when your wife opens the app, the chance of her accidentally opens the message feature is almost zero (because 3D touch is so useless no one uses it). This approach is to hide valuable data when the source of threat (wife) thinks that the data exists somewhere.
  - Make the app looks like an app that counts how many days you two have been married, and also install it "as a gift" onto your wife's phone: this is the preventative approach. This approach will likely to eliminate her curiosity when she sees the app on your phone, which gives a second layer of protection to your assets. The goal is to make the source of threat (wife) believe that there is nothing valuable, which protects both asset.
