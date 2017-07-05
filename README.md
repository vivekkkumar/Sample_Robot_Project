# Sample_Robot_Project
Learnt the Robot framwork from a a tutorial and created a sample Robot framework project for showing how easy and powerful Robot framework is using Selenium libraries.

The file structure is such that: 

Resources contains all the libraries or functions defined
Tests directory contains all the tests that needs to be executed, consuming the libraries
Results have comprehensive output of Robot framework displayed in HTML format. 

To run the tests: 

pybot -t testcase1 testfile (python 2.x)

or 

pybot -d /Results directory_containing_test_files (-d flags tells where to store the results)
