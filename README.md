# General Interview Questions and Answers

---
#### Description:
This repo is to hold the interview questions and answers related to project, teams etc which are generic in nature.

---
#### Author:
* Created By: <b>Akash Tyagi.</b> 
* Reach me out at: akashdktyagi@gmail.com
* Date: Jan-2020
---

### Common Interview Questions and Sample Answers on Introduction,  FW and Project

#### Tell me about yourself.

* My Name is XYZ. 
* I have a total of 2.4 years of exp in Automation Testing using Selenium in Java.
* I did my graduation from <ABC> in the year 2015 in IT Branch and secured 70 %.
Currently, I am working with XYZ technologies from past 2.4 years as a Automation Tester.
Working on Automation of Retail Banking Application using TestNG/ and page object model-page factory based Framework.

* Or

Hi I am XYZ. I have a total of 3 years of exp in IT Industry. I completed my B Tech in Information Technology branch in the year 2008 from XYZ  and secured 70 % marks. 
Then I joined “<CompanyName>” as an Automation Testers and since then I am working on Selenium with Java project to automate a GUI application.
We are currently automating a Retail Banking Application. This Application has all the typical retail banking application functionalities like Transfer Funds, Bill Payment, Account Overview features etc. My assigned module is Transfer Funds.
We are using a Hybrid FW with data driven Features such as Data Provider in Test NG. We are also using Page Object Model;page factory with Test NG in our FW.
Using Git for version control and Maven as Build and dependencies management.
In order to manage our Tasks we are using Jira.
Agile environment with Scrum wit Sprint cycle as 2 weeks.

#### About your roles and responsibility:

Or

#### What kind of work do you do in your project:

I am working in a agile dev-test env. Currently my roles and responsibility are creation, maintenance and Execution.Typically core level FW changes are being done by our architect/Team Lead. 

As I said, We usually have three kinds of task:

#### Maintenance Activity: 
If existing functionality of the application is changed due to new enhancement, we need to change our scripts accordingly, to make them work else they will continue to fail, due to functionality change.
New Test Cases Automation: We also have to automate new test cases given to us by Manual Testers.
Execution: We are responsible for execution of Automation Pack. We run Smoke Tests after each code deployment and regression pack once every Sprint. 
We the analyze the results generated by our Regression pack and log defects if any.

Report Analysis.

Manual test Case Execution

Defect logging

How do you decide which test case to automate:

We have a “Automation BackLog Sheet”. Our team lead maintains that sheet. It is a collection of all the test cases. Once new test cases are created, we add those test case in the sheet and after discussion with the manual team we put the priority i.e. (High, Medium,Low) for the test cases. 
We also analyze the test case based on its complexity (High, Medium,Low).
We first pick the High Priority test cases for automation and then medium and low.
What do you mean by Complexity of the test cases:

Complexity indicates how much efforts are required to Automate a Particular test case. This will help in estimations about the Automation project. Generally speaking, a High Complexity TC takes 1 day to complete where as a 5 Low complexity test cases can be done in a day. This is how we (our team lead) do estimations.
What is the parameters to categorize Complexity

Or

#### What is High, Low and Medium Complexity:

* Low Complexity: If a Test case only says to login in to the application and validate if login is successful, such test cases are of low complexity.
* Medium Complexity: If a test case requires to automate steps like, Login, then transfer funds and validate that amount has been deducted from “source” and added in “destination” account. This requires additional validations and need to navigate to multiple pages and need to interact with multiple locators and validation logic is to be written. Such test cases could be classified as Medium Complexity.
* High Complexity: Generally test cases which requires navigation to many pages or lots of Locators are to be handled. 
* Or, test cases whose steps require to navigate to different Systems, i.e. a multi system environment.
* Or Test case which requires DB validations or Excel Manipulations etc,
* Such kind of test cases could be termed as High Complexity

#### Explain about your Application:

E-Commerce:

* I am currently working on a E Commerce website. Website’s Business is B2C. We have all the necessary features and functionalities of a B2C e-commerce website like Search for Product, Compare products, Add to Wish List, Add to basket, Check out and Payment gateway.
* I am currently working on Search feature, as it is the most volatile functionality of the application. As different products are being added very frequently and functionality of those search varies with each product, it becomes quite challenging to test it.
* Testing of payment gateway is another challenging area which is challenging. We make use of API testing tools to test payment gateway APIs which is done by our API testing team.

* Retail banking

* I am currently working on a Retail Banking Application. This application has typical Retail Banking features like Transfer funds, Bill payments, Account Overview etc.
* It also provides features to  its customer like, to check account activities. I am currently working on or assigned, Billl module where I am working on automating the test cases related to account activity.

#### Explain about your Project:

* Our project is following agile-scrum methodology.
* We have a Sprint cycle of 3 weeks. 1st two weeks is dedicated towards Development work. Remaining 1 week is reserved for testing activities.
* In the first two weeks while development team is working on the “Sprint BackLog” our functional team is also going through the same Sprint BackLog and deducing the corresponding Test Scenarios.
* Once development Team is done with their work and deploys the latest code on our Test server; then our Test Execution Cycle starts.
* New Test Cases i.e. test cases created in the same sprint by Manual testers are being executed manually.
* And Automation testers to which I am part of,  go ahead and execute our automation test pack for regression purposes.
* We are maintaining all of the activities in Jira and Storing our test artifacts in Agile Central.
* How many Test Cases are there in your Automation Pack:

* We have a total of 600 test cases.

* This list keeps on increasing with new test case being added every sprint.

* We usually automate High priority test cases first and so far we have automated 600 high priority test cases.

* We run these 600 test cases through Automation Pack every sprint as a part of regression. 

* We also continue to Automate the remaining test cases from our “Automation Back Log”

* Test case which are not part of Automation Pack are being executed manually.

* Since, testing Cycle is only one week, we have to complete all our testing efforts, manual and automation in this one week only. 

* All high priority test cases are covered in automation. Whatever is pending is done by manual team and on the last day Manual team also do exploratory testing.

#### What is execution time for these test cases:

* Ans: 5 hrs parallel execution

* In our FW, 1 test script usually takes around 5 mins on average and we have total of 600 test cases. So total sequential execution i.e. when executed on a single thread/instance takes 3000 mins i.e. 50 hrs which is almost 2 days.

* But we do parallel execution on a Virtual Machine with 10 consecutive instances/threads. This give us results in just 5 hrs.

#### Explain you current FW:

Since I joined this company, I am working on the same project. 

Our FW is a Hybrid FW which uses TestNG and page object model/page Factory as its main Components.
We have different page object file for different pages of the application.
 These Page object class files stores the locators of that page along with the public reusable methods.
We create our test cases in TestNG classes by calling reusable methods from the page object files.
We also have reusable utilities classes where we keep our all the reusable components and methods like BrowserManager, FileAndFolderManager,ExcelManager, DBManager etc.
Log4j for logging
For reporting we are using native TetsNG Reporter
If u join our company and we want to improve our Automation process how will u improve that? What will be proper answer for this sir? This question asked me in manager round. 

 

TO suggest improvement you need to know the problems which one could face in an automation project. Typically any automation project could have below issues in general. These are based on my years of experience. 

Of Course this is not the exhaustive list, just listed what was on top my mind.

 

Number of Script creation per day. It should be above 8 for an average complexity application, if it below, you need to find out why script creation output is low. Is automation testes are not disciplined enough, are they getting support from functional team on time, are the getting test data on time; if everything seems to be alright then flaw must be in the framework. Framework should be designed in a way to facilitate faster script creation, by providing more generic components as well as business related generic methods.
Script failure rate: If  you have 100 test scripts, failure rate should not be more than 10 percent. That means after every execution maximum 10 test cases should fail not more. Failure usually happens due to three major reasons, a. Actual application bug. b. Bug in the Script, script is not performing as expected 3. Sync related issues.
Your FW should be robust enough to minimize sync issues. Other than that your automation pack should tested multiple times before executing them during regression cycle. Your regression pack should not have faulty scripts. This reduces credibility of automation script and a blow to automation initiative.

Total Script Execution time: Total execution time should not be more than 5 hours for 1000 test cases for an average complex application. Reduce the execution time by adding more machine to test bed or increase instances of parallel execution. Also, check if your FW or test scripts has proper synchronization implemented. No hard wait or thread sleep should be present. Proper times outs should be present. Test scripts or FW are not going in to infinite loops etc.
Remove Hard Coding of Data: Data which is subject to change should not be hard coded and at the same time FW should be 100 percent configurable, no manual intervention should be there in order to trigger the FW execution.
Time bound deliveries of Test Scripts.
Correct estimation based on complexity should be done before starting test case creation.
 

Your FW should be designed in a way so that even a non technical person should be able to trigger and analyze the results.
 

Work should be evenly distributed among all the team members.
 

Continuous process improvement as well as FW enhancement should happen during the course of automation life cycle.
 

Most Imp:

10: Continue to explore the opportunity to achieve back end automation. As per agile pyramid, it is imperative to have more back end tests than UI.

 

Peer review of code should be a part of every sprint. Script created by one should be checked and validated by each other. It is very important to ensure the quality of your automation scripts.


---
Questions for Interview perspective in face to face round 

What is sign off process how it is followed in your company?
Sign off is given by Test Manager at the end of the Sprint.
Sign off is given once Test Manager is satisfied with the test coverage and test goals have been achieved. All the SIT testing, performance testing, Regression Testing(manual or via Automation suite) is completed. All the defects have been fixed and retested. Exploratory testing is completed.
Once all the above is completed Test Manager sends an email indicating that “we have done all forms of testing and now QA team can say to a considerable degree of confidence that release is bug free”
Its a “go-ahead” from QA team side.
Sign off activity happens after end of each sprint.
What is User acceptance testing ? and what is the UAT criteria?
UAT testing is a mechanism by which actual user or client make sure that what ever was promised is delivered.
It happens after the test cycle.
In few cases its not even part of Sprint and happens as a separate activity after test manager signs off the code base.
In UAT primarily user stories of the current release is checked.
What is a Smoke test and what type of test cases are included in your smoke pack?
Smoke test is a way of validating the stability of the application.
We run smoke test usually just after the deployment, to check if application is stable enough to start further testing activities.
Smoke pack usually checks ‘end to end’ and top functionalities of the application.
For example in the case an e commerce application, Smoke test would have these test cases:
Check the URL
Login
Search a Product and add to cart
Check out the cart
Place Order and validate the price, quantity etc
Validate the Payment gateway API
Smoke test should be automated.
Automated UI Smoke test pack should not take more than 10 mins to execute.
What type of test cases included in your regression pack?
We have a total of 1000 test cases.
Out of 1000 we have automated around 700 + test case in a period of 1 year.
Our regression test pack usually contains all the priority test cases.
In each sprint we automate only the priority test cases from a list of Regression test cases.
We execute these 800 test cases via our automation test pack.
We are using test ng parallel execution feature. So, our Automation pack takes 5 to 6 hours to execute.
Remaining test case are executed manually.
Manual team usually only executes non-automated priority test cases
Other than that we also do 1 day of exploratory testing just before sign off.
How frequently do you execute the regression pack, its either a daily basis or weekly basis?
Every 2 day we have a new code deployment during the sprint.
We run our regression pack every 2 day i.e. as soon as new code is deployed.
As soon as new code is deployed, we executes Smoke automation pack first and with in 10 mins we get to know if code deployment is successful or not.
If smoke test results are green then we manually trigger full regression pack on Virtual Machine.
So in a single sprint, which is of two weeks for us, we execute the regression pack at least 4-5 times in 2 weeks.
What is the pipeline structure of Jenkins for execution of test packs?
We are using Jenkins for Continuous Integration.
 Jenkins is primarily responsible for building the application code. Steps in CI typically goes like this in our project:
Developer merges their code in to master branch of Git.
Jenkins continuously polls or reads application Git master branch.
As soon as there is new commit on application master branch, Jenkins triggers the Build process.
Jenkins downloads the application code(in  java, C#) etc and deploys the application code on the Test server.
Jenkins also would execute the Unit test before the deployment.
Then Jenkins Would go to the Selenium automation Git repository.
Jenkins then read the master branch of the repo and create automation code build
It then executes the test using maven sure fire plugin and TestNG.
We first run Smoke tests pack via Jenkins, to test the Stability of the application.(However, you can run full regression as well)
Once the execution is completed, Jenkins will email the report to all the stake holders.
How nightly execution is executed via Jenkins who triggers it and how the reporting is generated and sent to the respective persons? What is included in the reports.
How you configured Jenkins?
When you started the automation testing after the project started(after how many days,what’s the reason of delay in starting automation procedure )?
What if the requirements are fixed and customer needs an agile environment for testing?
How you are integrating maven with Jenkins?
How you are integrating maven with eclipse?
What if maven is not used then is it possible to build a project without any tool and deploy it or distribute it?
How you integrate Git with GitHub?
What is .bat file? Where you are using it?
How to reduce maintenance of our framework?
Suppose if your release is @6 pm  n before 2 hrs major blocker bug arises at client side then what should u do? And development team wants 2 days time to develop or Fix that issue?
What is non reproducible bug? How to raise it to the developer team as it doesn’t get reproduced quite easily.
If there is a verification module link and that is expired after 24 hrs and after link expired you have to automate or test it, then how can u automate that expired link?
If 1 module or test cases tested 5 times but 1 bug is there  and the whole project is retested already then how to handle that situation?
What is scrum? Explain roles ?
What is risk analysis?
Suppose you have 100 test cases and you want to run within 1 hr,then what should you do?
After automation testing completed assume that new requirement have been added how will you handle this in automation.
What is the design factors should been taken into consideration while creation of framework.
When you get the bug what is your approach.
What are the qualities you should have for becoming a good test engineer?
What is difference between test data and testing data?
When do you interact with BA and for what reasons?
Do you ask for a code freeze date for Dev Team?
How deployment process works,and explain continuous integration process,how to make a build using jenkins and how to test it on your environment?
internal working and flow of your FW?How to perform database validation at backend process?
On what basis you decides priority for test cases.
Realistically, its the manual team QA, BA or Scrum master determines the priority of the test cases.
Usually, all the requirements are in the form of User stories kept in jira.
All User stories have to have priorities and certain level of importance mentioned in the Jira itself.
So when you create test cases out of User stories they also inherit the same priority from their user stories or epics.
Higher the priority of user stories , higher the priority of the test cases.
Priority is mostly decided based on the how risky the feature/functionality is. By risk I mean, if a defect is not caught in the feature/functionality what and how much the client/company lose.
For example, take a case of an e-commerce application like amazon. Imagine there are two test cases.
Search a product and check filters are correctly displayed.
Search a product and check prices are correctly displayed.
Check all the categories are displayed in the menu item.
Check payment gateway window appears after user clicks “place Order”.
Lets decide the priority of above cases.
Any defect after the execution of above scenarios is bad, no doubt about it. But their impact would vary.
Test case 3 is lowest priority.
Test Case 1 and 2 will have Medium priority.
Test Case 4 will have Highest priority as this will have direct financial loss to the company.
What is drawback of your framework?
Current drawback is that in the way we have implemented the logs and reporting. Currently since we using test ng framework, we are using the testng Reports for logging and reporting.
We have around 1000 plus test cases, so the problem which we are facing is that our report becomes very bulky when we try to send it to client, as it contains low level logs and high level logs both.
Low level logs: Element clicked, Screen shot taken, Element is set with value as  John etc. These logs does not make sense to end customer, who is only interested in knowing test case pass and fail status.
High Level logs: Number of test cases passed and failed, what is passed and high level detail on the step it failed etc. Client should only see this.
Solution: We are trying to implement log4j2 for low level logs and Extent report for high level logs. Since we are having 1000 test cases it’s going to be little cumbersome, but we have started implementing the concept now.
Another challenge can be that we are not able to run failed test cases programmatically. To solve it, we are trying to implement test ng interface (Nivedita will write its code)
What is recovery scenario and how will achieve ?
Recovery scenario is being handled via Exception handling in java. It is used to get out of un-expected errors which might come during the execution.
We have good exception handling in al most all the important methods. So as soon as any method encounters an error, proper message is logged in the report and test case moves on to the next test cases.
Another example is of StaleElementException. Some times due to dynamic pages with java script code we get StaleElementException. This is not really an application issue, but we need to give our script enough tolerance so that if stale element occurs our test case should not fail but rather capture the exception and retry the step.