# Class 17: Feb 16
  * a final OSS projects is selected 
  
# Class 16: Feb 14
  * a candidate set of at least two projects is submitted 
      for options see [Section A](https://github.com/COSCS340/lectures/blob/master/ContributingToOSS.md). The instructions on how to submit are [here](https://github.com/COSCS340/oss/blob/master/README.md)

# Class 15: Feb 12
  * Will decide upon criteria to be used for OSS project selection
  * Final opportunity to finish Assignment 1: [see details: thanks @robobenklein]https://github.com/COSCS340/How-to-Gcloud/blob/master/README.md) or [original instructions](https://github.com/COSCS340/webserver/blob/master/README.md)
  * Ensure all projects have milestones and all members are assigned an issue (for the current sprint milestone) 
  
       1. Create a milestone "Backlog" (or whatever name) with no due date : it will be your backlog
       1. Create a milestone per Sprint with a due date
       1. Create issues in milestone "Backlog"
       1. Create two labels "Ready to review" and "In Progress"
       1. Add an estimate of effort [x] in points in the issue title, for example: "Restructure data [3]" (use 1 2 or 3)
       1. Create Pull Request in sprint milestone with tag "Ready to review"
       1. If you'd like you can use [zenhub](https://www.zenhub.com/blog/how-to-use-github-agile-project-management/)
  * Will start lecture on [Architecture](https://github.com/COSCS340/lectures/blob/master/software_architecture.pdf)

# Class 14: Feb 9
  * Chose an Open Source project to contribute to
  * Will work on finishing Assignment1: Create a docker container, deploy to GC, provide IP adress of the machine so that I can check if the web service is running: see recent status (as of last commit) in [results.md](http://github.com/COSCS340/webserver/blob/master/results.md) Thank you @bobzap66 for the presentation in class
  * Please take a look at [your team status](https://github.com/COSCS340/webserver), mailestones and assignees are still missing.

# Class 13: Feb 7
  * Software Process
  * Contributing to an Open Source Project

# Class 12: Feb 5
  * Software Process 
  * Contributing to an Open Source Project
  * [Asignment1 due on Friday](https://github.com/COSCS340/webserver) 

# Class 11: Feb 2
  * Finalize sprint implementation as issues for your project  
     [see QC Project as an example](https://github.com/COSCS340/QuantifyingCorruption/issues)
  * Software Process
  * GC assignment: create a docker container automatically built by dockerhub, deploy to GC, provide IP adress of the machine so that I can check if the web service
   
# Class 10: Jan 31
  * Continuous build (dockerhub)
  * Google cloud

# Class 9: Jan 29
  * Create sprint issues for your project repository
     - https://zube.io/blog/agile-project-management-workflow-for-github-issues/
     - https://codetree.com/guides/sprint-planning-github-issues
  
# Class 7: Jan 26
  * Project proposal is due 
     - See requirements in https://github.com/COSCS340/lectures/blob/master/project_proposal.pdf
     
# Class 6: Jan 24
  * Issue trackig / sprints 
     - https://codetree.com/guides/sprint-planning-github-issues
     - https://zube.io/blog/agile-project-management-workflow-for-github-issues/
  
# Class 5: Jan 22
  * Version Control (continued)
  * Introduction to Software Engineering
  * Not all project ideas are submitted to https://github.com/COSCS340/students
     - Please submit if you have not done so
     - Please chose one of the projects if you have not done so (many are looking for participants)
  
# Class 4: Jan 19
  * Discuss project proposals (as opposed to ideas)
  
# Class 3: Jan 17
  * Please accept the invitation to github organization for the class (you got invite in the email, but, if you misplaced it, you can accept invite at https://github.com/COSCS340 there will be a line at the top suggectin to accept the invite)
  * Project [options](https://github.com/COSCS340/news/blob/master/ProjectIdeas.md)
  * Please submit project idea as a pull request to students repository (in an A_prjname.md file, please prepend A_ to project name to differentiate from netid.md files)
     - Title
     - Basic idea
     - Technology used 
     - Members (and if additional members are needed to get up to four)
  
# Class 2: Jan 12
   * Version Control [slides](https://github.com/COSCS340/lectures/blob/master/version_control.pdf)

# Class 1: Jan 10
   * Introductions

# Syllabus for "Software Engineering"

* **Course:** [COSCS-340]
* ** MK404  MWF  12:20PM-01:10PM (Min Kao 404) **
* **Instructor:** Audris Mockus, [audris@utk.edu](mailto:audris@utk.edu) office hours MK613 - on request
* **TA:** Andrew Valesky, [avalesky@vols.utk.edu](mailto:avalesky@vols.utk.edu) office hours MK204 Mon&Wed: 1:15 to 2:15
* **TA:** Walton Macey,  [wmacey@vols.utk.edu](mailto:wmaceyy@vols.utk.edu) office hours MK618 Tu&Th 9:30 to 11:00
* **Need help?**

Simple rules: 

1. There are no stupid questions. However, it may be worth going over the following steps:
1. Think of what the right answer may be.
1. Search online: stack overflow, etc.
     - code snippets: On GH [gist.github.com](https://gist.github.com/) or, if anyone contributes, [for this class](https://github.com/snippets/COSCS340/)
     - answers to questions: [Stack Overflow](http://stackoverflow.com/)
1. Look through [issues](https://github.com/COSCS340/news/issues)
1. Post the question as an issue.
1. Ask instructor: [email](mailto:audris@utk.edu) for 1-on-1 help, or
   to set up a time to meet 

## Objectives
The course will provide basic software engineering approaches with a
focus on intense practice.

- Version control and issue tracking
- Basic software project management
- Build (cmake)
- Test
- Deploy to the cloud
- Participate in open source projects

## Expected Outcomes

Upon completion, students will be able to
work in teams, break work into iterations, write tests,
deploy their software to the cloud, and participate in open source
projects. 


## Course Description

All the assignments and projects for this class will use github -
*no exceptions*.

The work will have to be described via issues on github that
will be used to define and track progress. 

The resulting program will be deployed via docker container
to google cloud.

Each student will submit at least one contribution to an open source
project. 

## Prerequisites

While we have strived to make the programming component of this course
straightforward, we will not devote much time to teaching
programming. You should feel comfortable with:

1. How to look up syntax on Google and StackOverflow.
1. Basic programming concepts like functions, loops, arrays, dictionaries, strings, and if statements.
1. How to learn new libraries by reading documentation and reusing examples
1. Asking questions on StackOverflow or as a GitHub issue.

### Requirements and tips

These apply to real life, as well.

* Must apply "good programming style" learned in class
    * Optimize for readability
* There is no required programming language or framework: the
  project should choose the most relevant technology for its
  objective (i.e., the technology that would require least effort to
  implement the desired system). For example, it could be
  analytics/deep learning application on top of
  gensis/tensorflow/caffe, a mobile app, a web service, an algorithm
  library, ....
* There is no specific domain the project should focus on, but it
  has to solve a real or perceived problem. In other words, its
  important to motivate the project. There is no need to choose from
  a list of example topics, such as [this](http://www.ece.rutgers.edu/~marsic/books/SE/projects/)
  or [this](https://www.elprocus.com/top-software-engineering-projects-for-it-and-cse-students-in-2014/).
* Best results are typically achieved if you work on a problem that
  you deeply care about. I would recommend, therefore, to choose a
  problem primarily based on your interests.
    

## Teaming Tips

* Agree on an editor and environment that you're comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to others on the team

## Evaluation

* Class Participation – 25%: students are expected to read all
   material covered in a week and come to class prepared to take
   part in the classroom discussions. Responding to other student
   questions (issues) counts as classroom participation. Class time
   will be also used for teamwork on the course project.

* Assignments - 25%: Each assignment will involve writing (or modifying a template of)
   a small Python program or a documentation of an open source contribution.

* Project - 50%: one original project a group of 4
   students. The project will explore one or more of the themes covered
   in the course that students find particularly compelling.  The
   group needs to submit a project proposal (2 pages IEEE format).  The proposal
   should provide a brief motivation of the project, detailed
   discussion of the data that will be obtained or used in the project,
   along with a time-line of milestones, and expected outcome.


Course Project: You will work in teams to propose, design, implement, and present a semester-long
software project. Your project work must be done in groups of 4 (or 3 if a fourth member cannot
be found). This work accounts for a major portion of your course grade (50%), so choose your
teammates wisely. The course project consists of a series of presentations and deliverables that
will be assigned throughout the semester. The grade breakdown is shown below:

1. Preliminary Project Proposal (5%)
2. Revised Project Proposal (5%)
3. Status Report (Sprint) 1 (5%)
4. Status Report (Sprint) 2 (5%)
5. Status Report (Sprint) 3 (5%)
6. Final Project (Report + Demo) (25%)

Each student in the group should have a role and be able to explain their individual contribution
to the project. We will take into account student feedback on the project and on their teammates
at the end of the semester, but for the most part, teammates will receive the same project grades.


## Other considerations

As a programmer you will never write anything from scratch, but will
reuse code, frameworks, or ideas.  You are encouraged to
learn from the work of your peers. However, if you don't try to do
it yourself, you will not learn. [Deliberate practice][deliberate-practice]
(activities designed for the sole purpose of effectively improving
specific aspects of an individual's performance) is the only way to
reach perfection.

Please respect the terms of use and/or license of any code you find,
and if you re-implement or duplicate an algorithm or code from
elsewhere, credit the original source with an inline comment.

## Resources

Project ideas
---------------

http://www.ece.rutgers.edu/~marsic/books/SE/projects/

http://nevonprojects.com/web-based-project-ideas-topics/


## Textbook

** There is no required textbook for the course **
several optional textbooks/online materials are listed.

- Bash

- Regular expressions

- Databases

- IEEE's "Software Engineering Body of Knowledge (SWEBOK)" version 3.0.

* [Python for beginners](https://www.python.org/about/gettingstarted/)
  and [Python Dictionaries](http://pythonprogramminglanguage.com/dictionary/)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
	* [GitHub Issues](https://guides.github.com/features/issues/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


<!-- Links -->
[docker]:http://www.eecs.utk.edu/resources/it/kb/docker
[class-site]:http://web.eecs.utk.edu/~audris/fdac
[deliberate-practice]:http://www.psy.fsu.edu/faculty/ericsson/ericsson.exp.perf.html
[pull-request]:https://help.github.com/articles/creating-a-pull-request
[create-repo]: https://help.github.com/articles/create-a-repo
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md


[Academic Dishonesty / Plagiarism]

Cheating and plagiarism are serious offenses and are grounds for
dismissal from the course and an automatic F grade. Please read UT's
honor statement. for more information on what constitutes plagiarism
and what actions may be taken if the honor statement is violated. I
have written a helpful guide to avoiding plagiarism. The guide is
from my COSC102 course, but it is still relevant. 

Any plagiarism/cheating on an exam will be an automatic F for the
course and a referral. Any plagiarism/cheating on homework will
result in a 0 for that homework or assignment. 

Any repeat offenses in plagiarism/cheating will be an automatic F
for the course. 

Bottom line: It isn't worth it.....PLEASE don't do it!

Any cheating, plagiarism, etc. will be punished in accordance with
the current version of Hilltopics. For more information see
http://studentconduct.utk.edu/students/current-students/ 

[Grading]

See above


[MiniTasks]

Good quality commit messages

Issues that describe what is needed in a sprint

How to get a contribution accepted in an oss project

How to find project to learn from

The project quality index
