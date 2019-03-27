.. This document is written in reStructuredText, a simple and unobstrusive
.. markup language.  For an introductiont to reStructuredText see:
.. 
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
.. 
.. Lines like this which start with `.. ` are comments which won't appear
.. in the generated output.
.. 
.. To apply for a GSoC project with Xapian, please fill in the template below.
.. Placeholder text for where you're expected to write something says "FILLME"
.. - search for this in the generated PDF to check you haven't missed anything.
.. 
.. See our GSoC Project Ideas List for some suggested project ideas:
.. https://trac.xapian.org/wiki/GSoCProjectIdeas
..
.. You are also most welcome to propose a project based on your own ideas.
.. 
.. From experience the best proposals are ones that are discussed with us and
.. improved in response to feedback.  You can share draft applications with
.. us by forking the git repository containing this file, filling in where
.. it says "FILLME", committing your changes and pushing them to your fork,
.. then opening a pull request to request us to review your draft proposal.
.. You can do this even before applications officially open.
.. 
.. IMPORTANT: Your application is only valid is you upload a PDF of your
.. proposal to the GSoC website at https://summerofcode.withgoogle.com/ - you
.. can generate a PDF of this proposal using "make pdf".  You can update the
.. PDF proposal right up to the deadline by just uploading a new file, so don't
.. leave it until the last minute to upload a version.  The deadline is
.. strictly enforced by Google, with no exceptions no matter how creative your
.. excuse.
.. 
.. If there is additional information which we haven't explicitly asked for
.. which you think is relevant, feel free to include it. For instance, since
.. work on Xapian often draws on academic research, it's important to cite
.. suitable references both to support any position you take (such as
.. 'algorithm X is considered to perform better than algorithm Y') and to show
.. which ideas underpin your project, and how you've had to develop them
.. further to make them practical for Xapian.
.. 
.. You're welcome to include diagrams or other images if you think they're
.. helpful - for how to do this see:
.. https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html#images
.. 
.. Please take care to address all relevant questions - attention to detail
.. is important when working with computers!
.. 
.. If you have any questions, feel free to come and chat with us on IRC, or
.. send a mail to the mailing lists.  To answer a very common question, it's
.. the mentors who between them decide which proposals to accept - Google just
.. tell us HOW MANY we can accept (and they tell us that AFTER student
.. applications close).
.. 
.. Here are some useful resources if you want some tips on putting together a
.. good application:
.. 
.. "Writing a Proposal" from the GSoC Student Guide:
.. https://google.github.io/gsocguides/student/writing-a-proposal
.. 
.. "How to write a kick-ass proposal for Google Summer of Code":
.. https://teom.wordpress.com/2012/03/01/how-to-write-a-kick-ass-proposal-for-google-summer-of-code/

======================================
Weighting Schemes
======================================

About You
=========

 * Name: Sourav Saha

 * E-mail address: souravsaha.juit@gmail.com

 * IRC nickname(s): sourav

 * Any personal websites, blogs, social media, etc: 

 * github URL: https://github.com/souravsaha

 * Biography:

.. Tell us a bit about yourself.

I am doing my Masters(Mtech) in Computer Science from ISI Kolkata. Before that, I worked
for 2.5 years in Oracle as an Applications Engineer, and for 6 months at ServiceNow as a 
Platform Engineer. I did my B.E. from Jadavpur University in Information Technology during
2011-2015.

Background Information
----------------------

.. The answers to these questions help us understand you better, so that we can
.. help ensure you have an appropriately scoped project and match you up with a
.. suitable mentor or mentors.  So please be honest - it's OK if you don't have
.. much experience, but it's a problem if we aren't aware of that and propose
.. an overly ambitious project.

**Have you taken part in GSoC and/or GCI (https://codein.withgoogle.com/) and/or
similar programmes before?  If so, tell us about how it went, and any areas you
would have liked more help with.**

No, I have not taken any part in GSoc and/or GCI.

**Please tell us about any previous experience you have with Xapian, or other
systems for indexed text search.**

In Linux operating system I have seen synaptic graphical package manager and the terminal based package manager aptitude
uses Xapian for search. Also, I have used Lucene library for my research work. 


**Tell us about any previous experience with Free Software and Open Source
other than Xapian.**

I have developed Atlassian Jira utility for desktop for bulk insertion/updation of different tracking tickets.
Also I am familiar with web programming, created a dictionary app with React Javascript library. Both of them are 
there in the github repository.

**What other relevant prior experience do you have (courses taken at college,
hobbies, holiday jobs, etc)?**

Courses taken at college: Machine Learning, Probability and Stochastic Process, Software Enginnering, Algebra.
Extensive programming in C++, Java.
Summer Research Fellowship Programme - 2014, Indian Academy of Sciences
Advisor: Subhasis Chaudhuri, Prof. of Electrical Engineering, IIT Bombay.
Internship : Worked on Human pose estimation from streams of videos using OpenCV C++ library. 
Published one paper entitled with :
Sourav Saha, Pritha Ganguly, Subhajit Chaudhury, “Vision Based Human Pose
Estimation for Virtual Cloth Fitting”. Indian Conference on Computer Vision,
Graphics, and Image Processing (ICVGIP-2014) which is one of the top conferences for
Computer Vision in India,(ACM Conference).  


**What development platforms, tools and methods do you prefer to use?**

GNU toolchain, valgrind, underlying operating system.

**Have you previously worked on a project of a similar scope?  If so, tell us
about it.**

Project in ServiceNow: Worked on Virtual Agent Designer for chat-bot systems.
It's a flow based designer where one can design their own virtual agent conversation
and automate several processes. The entire source code was in git, have familiarity with
git based version control system. 
Project in Oracle: Part of Student Admissions module which helps the admin of universities to create or design a custom application forms.
Developed Restful apis for student application forms design. Worked on distributed environment where all the developers were working 
from different parts of the globe. Received pacesetter award for FY2017.
Developed utility to aid in bulk creation/ updating of issues/tickets in a project tracker based
on Atlassian Jira. Worked on mainly proprietary code management environment. 



**What timezone will you be in during the coding period?**

IST (Indian Standard Timezone)

**Will your Summer of Code project be the main focus of your time during the
program?**

If I qualify/ am selected , I will do it as part of the 8 weeks summer project/ internship that is a 
curricular requirement of the MTech program that I am enrolled in.

**Expected work hours (e.g. Monday–Friday 9am–5pm UTC)**

Monday-Friday 9:30am-6pm IST.


**Are you applying for other projects in GSoC this year?  If so, with which
organisation(s)?**

.. We understand students sometimes want to apply to more than one org and
.. we don't have a problem with that, but it's helpful if we're aware of it
.. so that we know how many backup choices we might need.

Yes, I am applying for Learning to Rank Stabilisation project under the same organisation group.

Your Project
============

Motivations
-----------

**Why have you chosen this particular project?**

My research interests are in the field of Information Retrieval. I have gone through some lecture materials(victor lavrenko), 
tutorials and research papers in the field of Information Retrieval. I have started working on the explainer for one of the 
most popular and robust retrieval system Lucene, which is widely used in academics as well in insdustry. 
As I had worked on the debugging use of Lucene for information retrieval research I have implemented
few language models inside the Lucene library. We have submitted a demo paper in SIGIR'19. 


**Who will benefit from your project and in what ways?**

.. For example, think about the likely user-base, what they currently have to
.. do and how your project will improve things for them.

I hope to contribute to the Xapian code base by completing one of the items on the TODO list 
of the Xapian project. This should improve the quality of the Xapian s/w and provide its users
with an improved version in the near future.


Project Details
---------------

.. Please go into plenty of detail in this section.

**Describe any existing work and concepts on which your project is based.**

Few scholarly work related to Weighting schemes:
1) Clinchant, S., Gaussier, E.: Bridging Language Modeling and Divergence from Randomness Models: A Log-Logistic Model for IR. In: Azzopardi, L., Kazai, G., Robertson, S., Rüger, S., Shokouhi, M., Song, D., Yilmaz, E. (eds.) ICTIR 2009. LNCS, vol. 5766, pp. 54–65. Springer, Heidelberg (2009)
2) Cummins R, O’Riordan C (2006) Evolving local and global weighting schemes in information retrieval. Inf
Retr 9(3):311–330

**Do you have any preliminary findings or results which suggest that your
approach is possible and likely to succeed?**

The findings in the articles referred to above suggest few different weighting schemes. I beleive this project has been put on the TODO list for 
Xapian for this reason.  

**What other approaches to have your considered, and why did you reject those in
favour of your chosen approach?**

See above.

**Please note any uncertainties or aspects which depend on further research or
investigation.**

Not applicable, since this project involves implementing a known technique described in the
scholarly literature for IR. Of course, forces majeures, are always a potential course of 
uncertainity.

**How useful will your results be when not everything works out exactly as
planned?**

Given the design document which constitutes the 1st milestone/deliverables, others developers
should be able to continue the work and implement the chosen features within Xapian. 

Project Timeline
----------------

.. We want you to think about the order you will work on your project, and
.. how long you think each part will take.  The parts should be AT MOST a
.. week long, or else you won't be able to realistically judge how long
.. they might take.  Even a week is too long really.  Try to break larger
.. tasks down into sub-tasks.
.. 
.. The timeline helps both you and us to know what you should do next, and how
.. on track you are.  Your plan certainly isn't set in stone - as you work on
.. your project, it may become clear that it is better to work on aspects in a
.. different order, or you may some things take longer than expected, and the
.. scope of the project may need to be adjusted.  If you think that's the
.. case during the project, it's better to talk to us about it sooner rather
.. than later.
.. 
.. You should strive to break your project down into a series of stages each of
.. which is in turn divided into the implementation, testing, and documenting of
.. a part of your project. What we're ideally looking for is for each stage to
.. be completed and merged in turn, so that it can be included in a future
.. release of Xapian. Even if you don't manage to achieve everything you
.. planned to, the stages you do complete are more likely to be useful if
.. you've structured your project that way. It also allows us to reliably
.. determine your progress, and should be more satisfying for you - you'll be
.. able to see that you've achieved something useful much sooner!
.. 
.. Look at the dates in the timeline:
.. https://summerofcode.withgoogle.com/how-it-works/
.. 
.. There are about 3 weeks of "community bonding" after accepted students are
.. announced.  During this time you should aim to complete any further research
.. or other issues which need to be done before you can start coding, and to
.. continue to get familiar with the code you'll be working on.  Your mentors
.. are there to help you with this.  We realise that many students have classes
.. and/or exams in this time, so we certainly aren't expecting full time work
.. on your project, but you should aim to complete preliminary work such that
.. you can actually start coding at the start of the coding period.
.. 
.. The coding period is broken into three blocks of about 4 weeks each, with
.. an evaluation after each block.  The evaluations are to help keep you on
.. track, and consist of brief evaluation forms sent to GSoC by both the
.. student and the mentor, and a chance to explicitly review how your project
.. is going with Xapian mentors.
.. 
.. If you will have other commitments during the project time (for example,
.. any university classes or exams, vacations, etc), make sure you include them
.. in your project timeline.

1st 4 week
    - Reading the code base and fixing/implementing some new features.
    - write test cases 
2nd 4 week
    - find the issues and fix the bugs
    - write more code
    - write test cases
3rd 4 week
    - fix the bugs
    - run with lots of test cases
    - do different types of testing
    - document it properly

Previous Discussion of your Project
-----------------------------------

.. If you have discussed your project on our mailing lists please provide a
.. link to the discussion in the list archives.  If you've discussed it on
.. IRC, please say so (and the IRC handle you used if not the one given
.. above).

https://lists.xapian.org/pipermail/xapian-devel/2019-March/003310.html

Licensing of your contributions to Xapian
-----------------------------------------

**Do you agree to dual-license all your contributions to Xapian under the GNU
GPL version 2 and all later versions, and the MIT/X licence?**

For the avoidance of doubt this includes all contributions to our wiki, mailing
lists and documentation, including anything you write in your project's wiki
pages.

Yes, I agree to dual-license all my contributions to Xapian under the GNU 
GPL version 2 and all later versions, and the MIT/X licence.

.. For more details, including the rationale for this with respect to code,
.. please see the "Licensing of patches" section in the "HACKING" document:
.. https://trac.xapian.org/browser/git/xapian-core/HACKING#L1399

Use of Existing Code
--------------------

**If you already know about existing code you plan to incorporate or libraries
you plan to use, please give details.**

Not applicable.

.. Code reuse is often a desirable thing, but we need to have a clear
.. provenance for the code in our repository, and to ensure any dependencies
.. don't have conflicting licenses.  So if you plan to use or end up using code
.. which you didn't write yourself as part of the project, it is very important
.. to clearly identify that code (and keep existing licensing and copyright
.. details intact), and to check with the mentors that it is OK to use.
