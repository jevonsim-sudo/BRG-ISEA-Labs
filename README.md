# BRG-ISEA-Labs

ISEA Linux administration and server security practical labs

This repository documents my practical lab activities for the Murdoch University BRG-ISEA module at Kaplan Singapore. It covers my hands-on experience with Linux administration, cloud computing, server security, networking, automation and database management.

## Project Information

| Category | Details |
|---|---|
| Module | BRG-ISEA |
| Operating System | Ubuntu Linux |
| Local Environment | VirtualBox |
| Cloud Environment | AWS EC2 |
| Web Servers | Apache and Nginx |
| Additional Server Service | MariaDB |

## Lab Activities

| No. | Lab | Topic |
|---|---|---|
| 1 | [Lab 1A1](1a1.docx) | Virtualisation and Linux Setup |
| 2 | [Lab 1A2](1a2.docx) | Ubuntu Desktop and Command-Line Interface |
| 3 | [Lab 1B1](1b1.docx) | Linux Services, SSH and Firewalls |
| 4 | [Lab 1B2](1b2.docx) | File Permissions and Access Control |
| 5 | [Lab 1B3](1b3.docx) | File Search, Analysis and Archiving |
| 6 | [Lab 2A1](2a1_TCO.zip) | Total Cost of Ownership Analysis |
| 7 | [Lab 2A2](2a2.docx) | AWS EC2 Cloud Web Server |
| 8 | [Lab 2B1](2b1.docx) | Bash Scripting and System Automation |
| 9 | [Lab 2B2](2b2.docx) | Regular Expressions and Apache Log Analysis |
| 10 | [Lab 2B3](2b3.docx) | Linux System and Process Management |
| 11 | [Lab 3A1 and 3A2](3a1_3a2.docx) | Domain, DNS and HTTPS Configuration |
| 12 | [Lab 3B1](3b1.docx) | Automated Backups, Cron Jobs and SCP |
| 13 | [Lab 4A](4a.docx) | MariaDB Database Server |

## Additional Server Service

### MariaDB

MariaDB was selected as my additional server service to explore relational database management in a Linux cloud environment.

The practical activity covered:

- Installation and configuration of MariaDB
- Database security configuration
- Database and table creation
- SQL queries and record management
- User authentication and access permissions
- Database backup and recovery

[View MariaDB Lab Documentation](4a.docx)

## Technologies and Tools Used

- Ubuntu Linux
- Oracle VirtualBox
- Amazon Web Services (AWS EC2)
- Apache and Nginx
- Bash scripting
- SSH and SCP
- Cron
- DuckDNS
- Let's Encrypt and Certbot
- MariaDB and SQL
- GitHub

## Learning Goals

- Develop practical Linux server administration skills.
- Understand cloud computing and virtualisation.
- Configure and secure network services.
- Automate repetitive administrative tasks.
- Develop database management skills.
- Improve technical troubleshooting and documentation skills.

## My Learning Blog


### 1. Learning Ubuntu and Linux Commands

Before starting this module, I had never used Ubuntu or Linux. I was unfamiliar with the command-line interface because I was more accustomed to using Windows.

Throughout the practical activities, I learned how to navigate directories, manage files, install software and configure file permissions using Linux commands. I also learned how to interpret terminal outputs and troubleshoot errors.

These skills provided me with a foundation in Linux administration that will be useful in future IT roles.

### 2. Cloud Computing and AWS EC2

During this module, I gained practical experience using Amazon Web Services (AWS) to host an Ubuntu server.

I learned how to access a remote server using SSH, configure web services and understand the importance of network ports and security settings.

This activity helped me understand how cloud computing allows businesses to host and manage services without maintaining their own physical servers.

### 3. Server Configuration and Security

I learned that installing a server service is only one part of server administration. Proper configuration, access control and security are also important.

Through the practical activities, I worked with Apache, Nginx, DNS and HTTPS certificates. I also used system monitoring commands and examined server logs to understand system behaviour and identify potential issues.

These activities demonstrated the importance of maintaining secure and reliable server environments.

### 4. Bash Scripting and Task Automation

Bash scripting introduced me to automating repetitive administrative tasks instead of performing them manually.

I created a backup script that compressed files into ZIP archives and used cron to schedule automatic backups. I also verified the generated backup files and transferred a backup to my local computer using SCP.

This activity helped me understand how automation can reduce administrative workload, minimise human errors and improve data protection.

### 5. MariaDB Database Management

For my additional server service, I selected MariaDB to explore relational database management.

I installed and configured MariaDB, created databases and tables, inserted employee records and performed SQL queries. I also configured database user permissions and tested access restrictions.

One issue I encountered was attempting to create a table that already existed. I resolved this by checking the existing table structure instead of recreating it.

Finally, I successfully backed up and restored the database. This demonstrated the importance of database security, access control and disaster recovery.


## AI Tools Used

ChatGPT was used to assist with understanding certain Linux commands, troubleshooting specific errors, structuring documentation and improving written explanations.
