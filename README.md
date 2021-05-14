# E-Transport Automation
## _Objective_
The Objective of the task is to implement the automation in the E-transport project ,So that the development of services that are we monitoring or providing get smother.

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

 |**SNo.** | **Test Case Description** |**Test Steps** | **Expected Result** | **Actual Result** | **Status** |
|:-----: | :-----: | :------: | :-----: | :-----: | :-----: |
|1|Get user validation using LDAP on Devloper side| Configure LDAP on dev and Github side so that |User validation done successfully||Pass|
|2|Push Source code data on Github Using LDAP user authentication|Login at Github using LDAP user athentication and access to the repository and store data in it.|Able to store code to github by dev.||Pass|
|3|Get code from Github and move codeg server using Jenkins to stagin|Move data from repository to the stagging server using Jenking pipline|Code should be moved to stagging server.||Pass|
|4|Transfer Devloped application on pre-production server Using Ansible|cc|Devloped application deployed at pre-poduction server.||Pass|
|5|Now deploye the final application on production server|aa|Final application deployed at production.||Pass|




   [LDAP]: <https://ldap.com/>
   [Github]: <https://github.com/>
   [Jenkins]: <https://www.jenkins.io/>
   [Ansible]: <https://www.ansible.com/>

