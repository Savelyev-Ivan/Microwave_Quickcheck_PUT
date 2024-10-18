# Microwave_Quickcheck_PUT
Task 

In this assignment, you'll get some practice at writing parameterized unit tests using junit-quickcheck on the Microwave controller Java program.  The goal is to create parameterized unit tests for the user stories that are described as comments in the TestMicrowave.java file that is included with the initial project described below.

An initial project is available in the .zip / .tar.gz files below. This project contains a build.gradle file with all of the dependencies necessary to use junit-quickcheck, along with a very slightly buggy Microwave model.

Interaction should occur through the "microwave" object that is included in the TestMicrowave.java file.  We have demonstrated example parameterized unit tests (PUT) in an earlier video.  Your job is to fill in the PUTs described in the comments of this file. 

Download and expand the .zip / .tar.gz file into a directory of your choice, then to import the project into Eclipse, follow the directions to import gradle projects into Eclipse:

If you want to do things from the command line or from another IDE, you can use gradle directly starting from the build.gradle and settings.gradle file. To install gradle, follow the download and install directions from https://gradle.org/ that are appropriate for your platform. However, in this case you are on your own.

Deliverable

Your task is to complete the TestMicrowave.java file to test the Microwave application to ensure it is working properly.  There are two bugs in the original model.  Inside the project, you will find the functional code and a PUT to get you started.  To submit for grading, submit this file. 

How will this be graded?

In order to measure the adequacy of your tests, we will run your tests against the bugs in the original model, and a fixed version of the program. The tests should pass on the fixed version and detect the bugs in the buggy version, as well as three additional seeded bugs.

You will get half credit for submitting tests which accurately report a working correct implementation. Then, you get incremental credit for each buggy version your tests successfully identify as not correct. There are 5 buggy mutant programs in total; to receive full credit your program should discover 4 of the bugs.
