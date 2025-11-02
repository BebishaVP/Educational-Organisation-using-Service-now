 Title: Educational-Organisation-using-Service-now:


 TEAM ID: NM2025TMID01617

 TEAM SIZE : 3
 Team Leader: Ashmi Fathima
 Team Member: Bebisha V P
 Team Member: Jaina Nasrin

 Problem Statement:
 In many educational organisations, daily operations such as admissions, student progress tracking, staff management, and communication are often handled manually or through different disconnected systems. This creates several challenges like delays in processes, lack of transparency for students and staff, and difficulties in managing large amounts of data. Without proper automation, tasks such as approvals, notifications, and report generation consume more time and effort.
Moreover, the absence of a single digital platform leads to communication gaps between students, teachers, and administrators. These issues highlight the need for a centralized and automated system to make educational management more efficient and reliable.
Objective: 
The project aims to develop a system for schools and colleges to manage admissions, student details, and academic progress, making the entire process quick, paperless, and user-friendly.
Skills:
ServiceNow Platform Knowledge
Scripting (JavaScript)
Database Concepts (RDBMS)
Web Technologies (HTML, CSS, PHP/Node.js)
Workflow Automation
Problem-Solving
Team Collaboration
Project Presentation
Analytical Thinking

TASK INITIATION
Module 1: Creating an Update Set

Step 1: Click on All >> Local update sets.
Step 2: Click on New
Step 3: Enter the Details Name: Educational Organisation >> Click on Submit and make Current.

Module 2: Creating A Table
Sub Module 1: Creating Salesforce Table. Step 1: All>>Tables
Step 2: Click On New
Step 3: Enter the Label (Anything you want): Salesforce >> Click on Name it will Automatically generate Api name.
Step 4: Create columns as given below, Double Click on Column label and Enter the Column labels and click on the tick mark >> Give Type as given.
Step 5: For “Admin Number” Give Display as True and right click on the toggle bar on top >> save.
Step 6: Click on controls >> Enable Extensible.
Step 7: Click on “Admin Number” column, In Related Links Click on Advanced View >> Default View (Enable Use dynamic default)
>> select Get Next Padded Number in Dynamic default value >> Update.
Step 8: Click on “Grade” Column >> Click on Choices and give Label, Value and Sequence as given below.
Sub Module 2: Creating Admission Table
Step 1: Create an Admission Table with Columns given.
Step 2: Select Extends Table >> Salesforce and also Select Add module to menu >> Salesforce.
Step 3: Create Fields as shown.
Step 4: Create choice for Admin Status as
Step 5: Create choice for Pin code as:
Step 6: Create choice for Purpose of Join as:
Step 7: Create choice for School as:
Step 8: Create choice for School Area as:
Sub Module 3: Creating Student Progress Table
Step 1: Create a Student Progress Table with Columns given.
Step 2: Select Add module to menu >> Salesforce.
 Step 3: Create Fields as shown:
Module 3: Form Layout
Step 1: In the Student Progress Table Page, Click on Layout form.
Step 2: Click on Admission Number [+].
Step 3: Select below Admission Number fields in Available side and send it to selected side as below >> save.
Module 4: Form Layout
Sub Module 1: Creating Form Design for Salesforce Table
 Step 1: All >> System Definition >> Tables.
Step 2: In Label Search for Salesforce and open.

Step 3: Right Click on top Toggle >> Configure >> Form Design
Step 4: In drop down select Salesforce(u_salesforce).
Step 5: Drag and drop the fields to the left side as below.
Step 6: Save
Sub Module 2: Creating Form Design for Admission Table
Step 1: Follow the same steps as Activity 1, Configure the fields as below and save.
Sub Module 3: Creating Form Design for Student progress Table
Step 1: Follow the same steps as Activity1, Configure the fields as below and save.
Module 5: Number Maintenance
Step 1: All >> Number Maintenance >> New
Step 2: Fill the details >> Submit.
Module 6: Process Flow
Step 1: All >> Process Flow>> New.
Step 2: Fill the Details as given Below
Step 3: Right Click on toggle and click on the save.
Step 4: Replace the Name and Label as below and click on Insert on stay.
Step 5: Replace the Name and Label in order and click on Insert on stay.
(Joined >> Rejected >> Rejoined >> Closed >> Cancelled.)
Step 6: Order should be New >> InProgress >> Joined >> Rejected
>> Rejoined >> Closed >> Cancelled.
Module 7: Client Script
Conclusion:
The project “Educational Organisation Using ServiceNow” successfully demonstrates how digital automation can simplify and improve the management of educational institutions. By using ServiceNow, we were able to centralize student data, automate workflows, and create an efficient platform for admissions, student progress tracking, and communication between staff and students. This solution reduces manual effort, saves time, and ensures accuracy in handling institutional processes. Overall, the project highlights the importance of using modern IT service management tools to build a smarter and more reliable educational system.
>   Servicenow Instance:https://dev317444.service-now.com/now/appenginestudio/my-apps/53a08b1f83f432100f19b755eeaad388
>> 
