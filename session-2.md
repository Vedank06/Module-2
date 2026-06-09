1.List 3 key responsibilities each for a Tester and a Test Leader in a software project, and give one example of how each role contributes during a release cycle.



Ans: 



Tester



Key Responsibilities:



\* Execute Test Cases: Runs functional, regression, and performance tests manually or automatically.

\* Log Defects: Documents identified software bugs with clear steps to reproduce.

\* Verify Fixes: Retests resolved bugs to ensure developers fixed them correctly. \[1, 2, 3, 4, 5] 



Release Contribution:

During a release cycle, a tester performs smoke testing on the final release candidate build. This quick check ensures critical paths work before deploying to production. \[6, 7] 



Test Leader



Key Responsibilities:



\* Define Test Strategy: Establishes the testing scope, environment needs, and tooling choices.

\* Allocate Resources: Assigns testing tasks to team members based on skills.

\* Assess Quality Risks: Identifies potential product vulnerabilities and tracks testing metrics. \[8, 9, 10, 11, 12] 



Release Contribution:

During a release cycle, a test leader provides the Go/No-Go recommendation. They review open high-priority bugs to decide if the software is safe to launch. \[13, 14, 15] 



2.Pick any app you use daily (Instagram, Zomato, Paytm, etc.) and write a one-paragraph comparison of how Quality Assurance (QA) and Quality Control (QC) would be performed for that app.<br><br><em><strong>Hint:</strong> Think about activities done before coding vs after coding is complete.</em>.



Ans: For Instagram, Quality Assurance (QA) is about preventing bugs before the software is built, which involves activities like setting strict guidelines for photo uploads, creating test checklists, and reviewing feature designs before developers write any code. On the other hand, Quality Control (QC) is about finding bugs after the app is built, which involves testing the actual app to ensure filters work properly, videos play without crashing, and buttons respond correctly before the update goes live. In short, QA builds the rules to prevent mistakes, while QC tests the final app to catch any mistakes that slipped through.



3.Explain the difference between Testing and Debugging by describing what a tester does vs what a developer does when a bug is found in a Flipkart-style shopping cart feature.

Ans:Testing and Debugging are different activities in software development.



In a Flipkart-style shopping cart feature, a Tester checks whether the cart is working correctly. For example, the tester adds a product to the cart and finds that the total price is calculated incorrectly. The tester then reports this bug to the development team.



A Developer performs Debugging. The developer investigates the code, finds the reason for the incorrect price calculation, fixes the problem, and updates the code. After that, the tester tests the feature again to make sure the bug has been fixed.



In simple words:



Testing = Finding bugs (done by Tester).

Debugging = Fixing bugs (done by Developer).



4.Create a basic test plan skeleton in a Word or Google Doc for a new feature in a food delivery app (like Swiggy) — include at least these sections: Test Plan ID, Feature Description, Test Scope, Roles \& Responsibilities, Test Environment, and Test Deliverables.<br><br><em><strong>Constraint:</strong> Do not copy any template from the internet; write each section in your own words for a real food delivery feature (e.g., promo code, order tracking).</em>



Ans:# Test Plan Skeleton for Food Delivery App (Promo Code Feature)



1\. Test Plan ID



TP\_FOOD\_001



2\. Feature Description



This feature allows users to apply promo codes while placing a food order. If the promo code is valid, the user receives a discount on the order amount.



3\. Test Scope



In Scope:



\* Apply valid promo codes

\* Apply invalid promo codes

\* Verify discount calculation

\* Verify promo code expiry date

\* Verify minimum order amount conditions



Out of Scope:



\* Payment gateway testing

\* Restaurant management features



4\. Roles \& Responsibilities



Tester



\* Create test cases

\* Execute test cases

\* Report defects



Developer



\* Fix reported defects

\* Support testing activities



Test Leader



\* Review test results

\* Track testing progress

\* Approve testing completion



5\. Test Environment



\* Android Mobile Device

\* iPhone Device

\* Internet Connection

\* Test Version of Food Delivery App

\* Test User Account



6\. Test Deliverables



\* Test Plan Document

\* Test Cases

\* Test Execution Report

\* Defect Report

\* Test Summary Report

\* Final Sign-off Report



