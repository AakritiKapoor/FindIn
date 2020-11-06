Name: Aakriti Kapoor

Table of contents:
CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Installation
 * Configuration
 * Troubleshooting
 * FAQ

 
Introduction:
---------------
# FindIn
FindInRepo :HR and Data expertise from 3K+ organizational hires and 30K+ job seeker interviews. It focuses on small-medium sized (SMB) organizations, &lt; 500 employees. The initial focus on developer/programmer/IT roles. The benefits are matched job seeker to their “right” opportunity, better organizational experience by reducing time and cost to recruit well-matched people and better job seeker experience as they never have to “apply” to a job again.

INSTRUCTIONS
-------------
Instructions for the software setup in the working enviornment :

Version 1- FindIN: 
Feature dilivered : LoginIN, Registration for employee, Registration for job-seeker,and Database extablishment.

Procedure to start the application:
* Edit programs/config.do to adjust the default path
* Run programs/00_setup.do once on a new system to set up the working environment.
* Download the data files referenced above. Each should be stored in the prepared subdirectories of data/, in the format that you download them in. Do not unzip. Scripts are provided in each directory to download the public-use files. Confidential data files requested as part of your FSRDC project will appear in the /data folder. No further action is needed on the replicator’s part.
* Run programs/01_master.do to run all steps in sequence.

For c# and  ASP.NET:
---------------------

* Open the startup.cs file with the userName and the key.
* Launch the FINDINdb file for the restoration into the local sytem or working space.
* Execute the SQL Server Manager Service in the working envirnment.
* Run the FindIN.SLN executable file in the setup enviornment.

REQUIREMENTS
------------

 * Login Views (https:Localhost:postnumber/mainpage/login.asp)
 * Login-Jobseeker Views (https:Localhost:postnumber/mainpage/JKlogin.asp)
 * Registration Views (https:Localhost:postnumber/mainpage/registeremployee.asp)
 * Registration-JobSeeker Views (https:Localhost:postnumber/mainpage/registercandidate.asp)
 
INSTALATION
---------------
 * Visual Studio 2019
 * Nodejs
 * Latestversion of JAVA
 * Newest version of the browser drivers.(Chrome, Firefox recommended)
 * ASP .net and c# packages.
 * SQLServer management Studio
 * SQL Services
 
CONFIGURATION
-------------
 
 * Configure the user permissions in Administration » People » Permissions:

   - Use the administration pages and help (System module)

     The top-level administration categories require this permission to be
     accessible. The administration menu will be empty unless this permission
     is granted.

   - Access administration menu

     Users with this permission will see the administration menu at the top of
     each page.

   - Display Drupal links

     Users with this permission will receive links to drupal.org issue queues
     for all enabled contributed modules. The issue queue links appear under
     the administration menu icon.

 *Customize the menu settings in Administration » Configuration and modules »
   Administration » Administration menu.

 *To prevent administrative menu items from appearing twice, you may hide the
   "Management" menu block.
   
FAQ
---

Q: I enabled "Aggregate and compress CSS files", but admin_menu.css is still
   there. Is this normal?

A: Yes, this is the intended behavior. the administration menu module only loads
   its stylesheet as needed (i.e., on page requests by logged-on, administrative
   users).
   
Q: I have restored the database in the SSMS on the set up using the (LocalDB/sqlserver).
   Is this enough for first time?
A: Yes, the setup for the FINDINDB is a one time process, that requirs restoring the DB 
    and then extablilsh the connection correctly.Post the installtion the SSMS is not
    nessesary to run , its activity will be triggered at the backend.

   
  
