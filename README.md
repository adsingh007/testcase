# E-Transport Automation
## _Objective_
The Objective of the task is to implement the automation in the E-transport Services,So that the development of services that are we providing get smother.

## _Features_

- User authentication using LDAP.
- Import and save files or code from GitHub.
- Fast and smooth Development & Deployment



## _Tech_

We are using number of open source tools to make our Automation works.
- [LDAP] used to validate usernames and passwords with Github.
- [Github] Git simplifies the process of working with other people and makes it easy to collaborate on projects.
- [Jenkins] is a powerful application that allows continuous integration and continuous delivery of projects,
- [Ansible] file management and deployment is done by Ansible.



## _Test Case_

 |**SNo.** | **Task Description** |**Test Steps** | **Expected Result** | **Actual Result** | **Status** |
|:-----: | :-----: | :------: | :-----: | :-----: | :-----: |
|1|Get user validation using LDAP on Devloper side| Configure LDAP on dev and Github side so that |User validation done successfully|||
|2|Push Source code data on Github Using LDAP user authentication|Login at Github using LDAP user athentication and access to the repository and store data in it.|Able to store code to github by dev.|||
|3|Get code from Github and move code to the server using Jenkins to staging server.|Move data from repository to the stagging server using git hoke & Jenking pipline|Code should be moved to stagging server.|||
|4|Transfer Devloped application from staging to pre-production server|Testing of Devoloped application will be done here before final deployement on production server|Application deployed at pre-poduction server.|||
|5|Now deploye the final application on production server|After testing the application will be deployed using Ansible|Final application deployed at production.|||




   [LDAP]: <https://ldap.com/>
   [Github]: <https://github.com/>
   [Jenkins]: <https://www.jenkins.io/>
   [Ansible]: <https://www.ansible.com/>

