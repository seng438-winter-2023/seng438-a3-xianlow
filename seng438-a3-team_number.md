**SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report #3 – Code Coverage, Adequacy Criteria and Test Case Correlation**

| Group \#:      |  1   |
| -------------- | --- |
| Xian Wei Low    |30113016|
| Akashdeep Singh |30128444|
| Abdul Moeiz     |30113088|
| Cale Morash     |30066719|


(Note that some labs require individual reports while others require one report
for each group. Please see each lab document for details.)

# 1 Introduction

Text…

# 2 Manual data-flow coverage calculations for X and Y methods

Text…

# 3 A detailed description of the testing strategy for the new unit test

We first have observed the a3 source code and alongside the javadocs to see what we have covered so far from a2. We used the Eclemma plugin to quickly see the coverage statistics. We mainly checked for statement/line and branch coverage. Then, based on that, we added new test cases to see which areas of methods were not covered in a3. Since a3 this time had the source code we were able to see which functions or branches had to be covered.

Since Range black box testing was extensively done in the previous assignment we had already a good level of coverage and therefore only added a few new coverages. 

# 4 A high level description of five selected test cases you have designed using coverage information, and how they have increased code coverage

Text…

# 5 A detailed report of the coverage achieved of each class and method (a screen shot from the code cover results in green and red color would suffice)

Text…

# 6 Pros and Cons of coverage tools used and Metrics you report

We used the Eclemma plugin from Eclipse. The pros of this tool are that it is widely popular and the installation process is very simple and straightforward, taking less than a minute. Also it allowed us to see easily and accurately the coverage, as well switching between line and branch coverage. With just a few clicks we were quickly able to view the statistics and as well the highlighted green or red areas of codes that were covered or uncovered.
However, one major drawback is that the plugin does not provide a conditional coverage metric, which might have been essential for our assignment task.


# 7 A comparison on the advantages and disadvantages of requirements-based test generation and coverage-based test generation.

Text…

# 8 A discussion on how the team work/effort was divided and managed

As a team of 4 members, we split up into 2 pairs: pair1(Abdul and Akashdeep) and pair2(Xian and Cale). Pair1 tested for Range whereas Pair2 tested for DataUtilities.
Each pair tested their respective program in a Pair programming style, where by taking turns one would code and the other guides or corrects in the process.
This allowed us to maintain an Agile workflow and complete the assignment in a tight timeline. Abdul and Xian have taken more responsibility in writing the testing code and they later compared the test cases between each other, once they were done coding. To allow the contributions to be fair therefore, Cale and Akashdeep partnered up on writing the report and added all calculations for the coverage.


# 9 Any difficulties encountered, challenges overcome, and lessons learned from performing the lab

One initial trouble we encountered was setting up the project. We were quite unsure whether the jar files and the mock jars as well had to be imported from assignment 2 or 3, as they were both present. However, by trial and error we were able to set up the imports properly as they were essential for running the Junit tests that had dependencies on these jar files.

Another problem was the fact that, since initially pair1 and pair2 were independently doing their assigned tasks we encountered a slight issue in importing and merging the test cases together. There was a slight build conflict when performing the action of Junit coverage test on the whole project. However, the conflict had been resolved without any complications.


# 10 Comments/feedback on the lab itself

Compared to the previous assignment, this 3rd assignment’s specification had a reasonable amount of text to read and comprehend the required task. This allowed us to quickly get started without having to read a lot.
Possibly the only very slight concern was setting up the project, we initially had the doubt on where to import the jar dependencies from, as mentioned before above. We believe providing a quick GIF animation of project setup would have been more easier to follow through, compared to switching back and forth between textual instruction and trying to find specific buttons or selections. We think this would make it an easier process for both the editor and the reader.

Although, this assignment has been a smoother process compared to previous ones and we are highly satisfied with it. 

