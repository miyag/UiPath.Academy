# RPA Infrastructure Training

https://www.uipath.com/ja/academy/training#t5

---

## Quiz - High Level Arch and deployment options

---
### 1) Is the SQL database mandatory for Orchestrator?
- [-] Yes, any Relational database, such as Oracle, SQL Server, MySQL, is supported
- [o] Yes, only SQL Server is supported
- [-] No, it can be replaced with Elasticsearch

---
### 2) Who communicates with Orchestrator directly?
- [-] Studio
- [-] The Executor
- [o] The UiPath Agent Windows service

---
### 3) What happens when the Start button in Orchestrator is clicked to start a Job?
- [-] Orchestrator waits for the next heartbeat from the Agent and sends back the Start command as an acknowledgement of the heartbeat
- [o] Orchestrator sends the Start command to the Agent using the WebSocket channel that was created by the Agent
- [-] Orchestrator creates a RDP connection to the robot, using the credentials set on the Robots page, and then starts the process on the robot machine

---
### 4) Where can the messages sent by the robots to Orchestrator be stored?
- [-] In both the SQL database and Elasticsearch
- [o] In one or more targets, which can include the SQL database, Elasticsearch, as well as other targets
- [-] Only in the SQL database, if Elasticsearch is not used
- [-] Only in Elasticsearch, if this optional component is included in the solution

---
### 5) When Orchestrator is deployed in the cloud, where can the robots be located?
- [-] The robots must be on premises for security reasons, and a VPN from the intranet to the cloud needs to be created
- [-] The robots must be on premises for security reasons, and Orchestrator needs to be publicly accessible from the Internet
- [-] The robots must be in the cloud too, to be able to connect to Orchestrator
- [o] The robots can be located either in the cloud or on premises, as long as the Orchestrator URL is accessible to them

---
### 6) What is the TCP port used by the Robot to connect to Orchestrator?
- [o] the port being listened to by Orchestrator
- [-] 443
- [-] 80

---
### 7) What are the Orchestrator components whose redundancy needs to be ensured by the High Availability deployment option?
- [-] The SQL Database and Elasticsearch, as they are the only persistent data components
- [-] The Web Application and the SQL database, because Elasticsearch is optional
- [-] The Web Application and Elasticsearch
- [o] All the components of the solution

---
### 8) What are the possibilities provided by an active-active Disaster Recovery model?
- [-] Robots can only be triggered from the Primary data center, because those from DR Data Center can only be used in case of a disaster
- [o] Robots can be triggered to run from both Data Centers, because they connect to the same Orchestrator farm

---
### 9) What needs to be done as a minimum recommendation to provide a Disaster Recovery solution?
- [-] Replicate the data stored in SQL DB and Elasticsearch, because this is the only persisted data
- [o] Replicate the data stored in SQL DB and Elasticsearch, plus the NuGet packages delivered to the robots, because this is the only persisted data
- [-] Replicate all the machines in the Primary Data Center to the Disaster Recovery one

---
### 10) What are the actions performed by the executor?
- [-] communicating with Orchestrator
- [-] receiving the Start message from Orchestrator and calling another Executor to open the required XAML file
- [o] reading and executing the automation scripts (XAML files) and communicating with the Agent

---
## Quiz - Administrative Features


### 1) Who can create Roles?
- [-] Administrators only
- [-] Any user with at least View and Create permission on Roles
- [o] Any user with at least the View permission on Users and the View and Create permissions on Roles
- [-] Any user with at least the Create permission on Roles

---
### 2) Which of the following statements about project publishing in Studio is false?
- [o] A project published from a Studio instance that is connected to Orchestrator is immediately used by the robots that share the environment with that Studio instance
- [-] A project published from a Studio instance that is connected to Orchestrator requires manual approval before being used by the robots that share the environment with that Studio instance
- [-] A project published from a Studio instance that is connected to Orchestrator is sent directly to Orchestrator without creating a local copy

---
### 3) What are the supported targets for the messages logged by the robots and collected by Orchestrator?
- [-] Either the SQL database or Elasticsearch
- [o] One or more targets; the messages can even be discarded
- [-] Only SQL database and Elasticsearch

---
### 4) If Orchestrator encounters an error and can’t display the requested page anymore, where can the details of the error be found?
- [-] The Windows Event log of the Orchestrator machine
- [-] The SQL database
- [o] The location that is currently configured in web.config to hold Orchestrator errors
- [-] The log files of Orchestrator
- [-] The browser

---

### 5) Which of the following statements about users is true?
- [-] When a local user is created, the password does not have to be provided to log in
- [o] When a domain user is created, the password does not have to be provided to log in
- [-] When a local user is created, the input of the domain name field has to be “‘local”

---
### 6) What are the available roles right after the Orchestrator installation?
- [-] Administrator
- [-] Administrator, Robot and Developer
- [o] Administrator and Robot

---
### 7) Who receives the email alerts sent by Orchestrator?
- [-] The users with the Administrator role
- [-] The users that are currently logged in to Orchestrator
- [-] A specific group of users that you can configure in Orchestrator
- [o] The users with a valid email address and View permission on alerts

---
### 8) What are some useful recommendations for the Orchestrator administrator?
- [-] Encrypt the secureAppSeetings section in web.config
- [o] All the options apply
- [-] Change admin password after the first login
- [-] Create multiple roles and assign them to the users; not all the users should be able to log in with the Administrator role


## Quiz - Elasticsearch and Kibana

---

### 1) What is Elasticsearch?
- [-] A search tool used to identify the data stored in a relational database
- [-] Another relational database
- [o] A big data storing tool

---

### 2) Orchestrator uses the NLog library to collect logs from several sources and redirect them to different targets. What type of target is Elasticsearch?
- [o] A custom target that is accessible through an extension
- [-] A standard target
- [-] A natively supported target

---

### 3) What is Kibana is used for?
- [-] Creating index patterns
- [-] Creating and displaying charts and dashboards
- [o] All the options apply
- [-] Searching through messages stored in Elasticsearch

---
### 4) Which statement about Elasticsearch is false?
- [-] Elasticsearch needs Java to run
- [-] Elasticsearch is a free product
- [-] Elasticsearch is a cross-platform tool
- [o] Elasticsearch needs a separate web application server

---
### 5) Which of the following statements about the use of Elasticsearch with Orchestrator is false?
- [-] There is a separate index created for each tenant
- [-] There is one index created for each month, for every tenant
- [o] There is one index created for each month, with all the tenants, the separation being ensured logically\ by the tenantID field

---
### 6) Why is it required to create at least one index pattern in Kibana?
- [o] To be able to access all the indices that match that pattern, considering that a new monthly index is created for every tenant
- [-] To be able to distinguish between the different months of the year
- [-] To be able to distinguish between different tenants

---

## Quiz - web.config explained

### 1) Which of the following statements related to Organization Units is false?
- [o] NuGet packages are separated by OU
- [-] Users have the same roles on all OUs they can access
- [-] Users can be granted access to zero or more OUs
- [-] There is one OU even if the feature is not activated

---
### 2) What happens when Windows Integrated Authentication is used?
- [o] The users in the same domain as Orchestrator can authenticate with their Windows identity, and also the users in different domains, if there is a TRUST relationship between the two domains
- [-] Only the users in the same domain as Orchestrator can authenticate with their Windows identity

---
### 3) What is the use of the NuGet.Packages.Path parameter?
- [o] Indicating the location of the NuGet packages as a local folder or a shared one
- [-] Indicating the location of the NuGet packages as an URL, from either the local intranet or the public cloud
- [-] Indicating the location of the NuGet packages as a local folder, a shared folder, or the URL of an online NuGet repository

---
### 4) What is the recommended way to create multiple tenants?
- [o] By logging in to the “host” tenant as an administrator, creating the tenants, and communicating the admin password to each tenant administrator; even if the creator knows the admin password of every tenant, that can be changed after the first login.
- [-] By turning Tenant.Registration.Enabled to true until all the tenants are created, and then turning it back to false; this is the recommended option, because the tenant creators can set their own password and no one else knows it.

---
### 5) Where can the minLevel and maxLevel attributes in the <nlog> section be used?
- [-] In the <targets> section
- [o] In the <rules> section

---
### 6) Which UiPath component uses the NuGet.Activities.Path parameter?
- [-] UiPath Studio, to look for the latest activity versions
- [-] UiPath Studio, after downloading new activity pack versions, to save them in the repository indicated by NuGet.Activities.Path
- [o] The robots to download a specific activity pack version when needed

---
### 7) Where can the messages generated by the Orchestrator web application be stored?
- [o] In Elasticsearch in a separate index, using the serverElasticBuffer target;In a target of the standard File type, if that target is created manually.
- [-] In Elasticsearch in a separate index, using the serverElasticBuffer target
- [-] Only in Windows Event Log, because that log allows access to administrators only
- [-] In a target of the standard File type, if that target is created manually

---
### 8) Which of the parameters below are among the most important ones when it comes to queues?
- [o] inProgressMaxNumberOfMinutes
- [-] QueuesStatisticsScheduleCron
- [-] UpdateUncompletedItemsJobCron

---

## Quiz - Security Consideration

### 1) Which of the following statements about the security features implemented on the UiPath components is false?
- [-] A robot needs to be provisioned in Orchestrator before it can connect to Orchestrator
- [-] A new version of the automation package is not executed until it’s manually declared as “Current” in Orchestrator
- [o] A robot can’t connect to Orchestrator if Orchestrator uses a self-signed certificate
- [-] Installation of Orchestrator requires an SSL certificate

---
### 2) Which is the recommended security protocol version required in Orchestrator?
- [-] TLS 1.1
- [-] SSL 2.0
- [-] SSL 3.0
- [o] TLS 1.2

---
### 3) Which of the following statements is true if Orchestrator and CyberArk are integrated?
- [o] Orchestrator can obtain the robot passwords from CyberArk
- [-] Orchestrator can obtain the passwords of the users that connect to Orchestrator’s web interface
- [-] Orchestrator can obtain the passwords stored as Credential assets from CyberArk

---

## Quiz - Installation and update

### 1) Which of the following statements about the MSI Installer is false?
- [o] The wizard verifies whether the account used to connect Orchestrator to the database has the dbcreator server role
- [-] The wizard attempts to connect to SQL Server before starting the installation, to validate the server, instance, and port
- [-] The wizard verifies the availability of the port that is mentioned in the corresponding page of the wizard
- [-] The wizard verifies the account and the password if a domain account for the Application Pool identity is provided
- [-] The wizard verifies the presence of the mentioned SSL certificate

---
### 2) The Orchestrator update using scripts can only be performed if the previous version was installed using scripts as well. Which of the following statements related to the update is true?
- [o] The existing site is updated; the keys in web.config are preserved, and new ones are added if necessary
- [-] A new site is created; the packages and the content in web.config are copied to the new site; the old site is not affected
- [-] The existing site is updated, but the existing web.config file is not, so new keys are not added

---

### 3) If an Orchestrator 2017.1 instance installed using scripts is updated to 2018.1 using the MSI installer, which of the following statements is true?
- [o] A new website is created; the EncryptionKey, machineKey, and apiKey parameters in the old web.config file have to be copied to the new one, and the NuGet packages of each individual tenant have to be copied from the old location to the into the new one, namely ./NuGetPackages/Tenants/tenant name
- [-] A new website is created and everything is copied and migrated from the old website to the new one; no manual action is required after the update
- [-] The existing website is updated to the new one, so no manual action is required afterwards

---
### 4) Which of the following statements related to the Orchestrator MSI installation is true?
- [-] The prerequisites are no longer valid, because the installer does everything
- [-] The prerequisites are the same as the ones for the installation using scripts
- [o] The prerequisites are the same as the ones for the installation using scripts, except for the WebDeploy extension, which is not required with the MSI installation

---

## Quiz - Robot Setup

---
### 1) The following statements describe how a robot can be connected to Orchestrator when the Robot Key is unknown. Which statement is false?
- [o] By starting the Settings dialog box with elevated rights and filling in the connection string
- [-] By running UiRobot.exe after installation with the --connect command and providing the connection string, if the robot machine is in the same domain as Orchestrator and Windows Authentication is enabled
- [-] By editing the UiPath.Settings file to enter the connection string
- [-] By running the MSI installer with the CONNECTIONSTRING parameter, if the robot machine is in the same domain as Orchestrator and Windows Authentication is enabled

---
### 2) Can a robot be connected to Orchestrator when a proxy server restricts the connection?
- [-] Yes, if a section about the proxy is added to UiRobot.exe.config, even if the proxy requires authentication
- [-] No
- [o] Yes, if the proxy does not require authentication and a section about the proxy is added to UiRobot.exe.config

---
### 3) If a self-signed certificate is used in Orchestrator, to which location on the robot machine should the public key of the SSL certificate be imported to connect that robot to Orchestrator?
- [-] Current user, Trusted Root Certification Authorities Store
- [o] Local computer, Trusted Root Certification Authorities Store
- [-] Current user, Personal Store
- [-] Local computer, Personal Store

---
### 4) Can a robot be moved from a tenant to a different one?
- [-] No
- [-] Yes, if the TenantID value is edited in the connection string in UiPath.settings
- [o] Yes, if the robot is disconnected from the initial tenant, where it has a Robot Key, and then connected to the new tenant, where it has a different Robot Key

---

## Quiz - Database Maintenance

### 1) Why it is recommended to archive and delete the old unused data in Logs and Queue Items, and to keep only the items registered in the last few days?
ｰ [-] Because the memory requirements of SQL Server increase when the data is not deleted
ｰ [-] Because the old items occupy disc space
ｰ [o] Because large amounts of data affect the current operations and slow down the performance of Orchestrator
ｰ [-] Because there are reports that need to be performed monthly, quarterly, and yearly

---
### 2) Why is the SQL Server database maintenance necessary?
ｰ [-] To update the table and index statistics, which better determine execution plans
ｰ [o]] To prevent any problems, to ensure smooth functioning, to free up disc space, to check for data errors, to update internal statistics, etc
ｰ [-] To reduce the space occupied on disc by shrinking the database files
ｰ [-] To reindex the tables that have accumulated many rows since the last maintenance operation

---
### 3) What should the Orchestrator backup procedure include?
ｰ [-] The SQL Server database and the Elasticsearch indices
ｰ [o] The SQL Server database, the NuGet Packages, the web.config file and the Elasticsearch indices
ｰ [-] The SQL Server database and the NuGet Packages
ｰ [-] The SQL Server database

---

## Quiz - Hardware Requirements

---
### 1) Which server has the highest hardware requirements for a given number of robots?
ｰ [-] NLB
ｰ [-] Web application server(Orchestrator)
ｰ [-] ElasticSearch
ｰ [o] SQL server

---
### 2) When is a NLB needed?
ｰ [-] When there are several separate Orchestrator installation instances that operate independently
ｰ [-] When there is a single Orchestrator installation instance
ｰ [o] When Orchestrator is installed in cluster mode
ｰ [-] When there is more than one tenant defined in Orchestrator

---

## Quiz - Final

---

### 1) What are the types of clients that can connect to the Orchestrator web application?

- [-] UiPath Studio and UiPath Robot
- [-] UiPath Studio, UiPath Robot and the browser for the Orchestrator’s web interface
- [-] UiPath Studio, UiPath Robot and a program or script that calls Orchestrator’s REST API methods
- [o] UiPath Studio, UiPath Robot, the browser for the Orchestrator’s web interface and a program or script that calls Orchestrator’s REST API methods

---
### 2) What happens if a robot downloads an automation package that contains unknown activity versions?
- [-] The robot downloads the required activity pack version directly from Orchestrator, using the specific URL of the activities feed in its own UiPath.settings file
- [-] The robot makes a call to Orchestrator specifying the required version, and Orchestrator uses the location specified in web.config under NuGet.Activities.Path to find the activity pack and deliver it to the robot
- [o] The robot tries to find the activity pack in several places, obtained from UiPath.settings, from the local Nuget.config file and from the system’s roaming profile Nuget.config.

---
### 3) Can a robot be connected to Orchestrator when a proxy server restricts the connection?
- [-] No
- [o] Yes, when the proxy does not require authentication, and after adding a new section, about the proxy, to UiRobot.exe.config
- [-] Yes, after adding a new section, about the proxy, to UiRobot.exe.config; even when the proxy requires authentication

---
### 4) What is the recommended way to create multiple tenants?
- [-] By turning Tenant.Registration.Enabled to true until all the tenants are created, and then turning it back to false; this is the recommended option, because the tenant creators can set their own password and no one else knows it.
- [o] By logging in to the “host” tenant as an administrator, creating the tenants, and communicating the admin password to each tenant administrator; even if the creator knows the admin password of every tenant, that can be changed after the first login.

---
### 5) When does the Orchestrator update procedure require special attention to the number of rows in the Logs table?
- [?] When updating from 2016.2 to 2017.1, because a new index is added to the table
- [?] When updating from 2017.1 to 2018.1, because a new index is added to the table
- [?] When updating from 2016.2 to either 2017.1 or 2018.1, because the index did not exist in 2016.2 and is necessary in all the later versions
- [?] When updating from 2016.2 to 2018.1, because a new index is added to the table

---
### 6) What should the Orchestrator backup procedure include?

- [-] The SQL Server database
- [-] The SQL Server database and the Elasticsearch indices
- [o] The SQL Server database, the NuGet Packages, the web.config file and the Elasticsearch indices
- [-] The SQL Server database and the NuGet Packages

---

### 7) If a self-signed certificate is used in Orchestrator, to which location on the robot machine should the public key of the SSL certificate be imported to connect that robot to Orchestrator?
- [ｰ] Local computer, Personal Store
- [o] Local computer, Trusted Root Certification Authorities Store
- [ｰ] Current user, Personal Store
- [ｰ] Current user, Trusted Root Certification Authorities Store

---
### 8) When the Kibana interface is used to search for a specific word in Elasticsearch, what type of information is retrieved?
- [-] The messages logged by the robots
- [o] All the indexed fields: messages, robot names, levels, process names, etc.
- [-] All the indexed fields: messages, robot names, levels, process names, etc., but only if the “Search all fields” parameter is set to true.

---
### 9) When the UiPath Robot Service, or the Agent, retrieves credentials from Orchestrator to create an interactive Windows session, how is the password sent?
- [-] Encrypted, using the secure HTTPS channel
- [-] As a plain, unencrypted text, using the secure HTTPS channel
- [o] As an unencrypted Secure String, using the secure HTTPS channel

---
### 10) Why it is recommended to archive and delete the old unused data in Logs and Queue Items, and to keep only the items registered in the last few days?
- [-] Because the old items occupy disc space
- [-] Because there are reports that need to be performed monthly, quarterly, and yearly
- [o] Because large amounts of data affect the current operations and slow down the performance of Orchestrator
- [-] Because the memory requirements of SQL Server increase when the data is not deleted

---
### 11) Which of the following statements about project publishing in Studio is false?
- [o] A project published from a Studio instance that is connected to Orchestrator is immediately used by the robots that share the environment with that Studio instance
- [-] A project published from a Studio instance that is connected to Orchestrator is sent directly to Orchestrator without creating a local copy
- [-] A project published from a Studio instance that is connected to Orchestrator requires manual approval before being used by the robots that share the environment with that Studio instance

---
### 12) Who receives the email alerts sent by Orchestrator?
- [-] A specific group of users that you can configure in Orchestrator
- [-] The users with the Administrator role
- [o] The users with a valid email address and View permission on alerts
- [-] The users that are currently logged in to Orchestrator

---
### 13) Why is the Time Zone setting useful when there are multiple tenants?
- [-] To accurately display the logging time of the messages sent by robots that belong to separate tenants located in different time zones.
- [o] To specify the time zone of the robots for each particular tenant, in case the time zone of the robots and the one of the tenant are different, in order to appropriately calculate the time to start scheduled jobs.
- [-] To indicate the geographical location of the tenants for administrative purposes, such as calculating a common maintenance window.

---
### 14) Orchestrator uses the NLog library to collect logs from several sources and redirect them to different targets. What type of target is Elasticsearch?

- [-] A standard target
- [o] A custom target that is accessible through an extension
- [-] A natively supported target

---
### 15) What happens if a robot is installed using the MSI Installer with the CONNECTIONSTRING parameter in the command line, but it is not yet provisioned in Orchestrator?
- [o] The UiPath Robot service is started at the end of the installation and attempts to connect to Orchestrator, which rejects it because it is unknown. The service keeps trying until the robot is provisioned in Orchestrator.
- [-] The UiPath Robot service is started at the end of the installation and attempts to connect to Orchestrator, which rejects it because it is unknown. The service stops and needs to be restarted after the robot is provisioned in Orchestrator.
- [-] The UiPath Robot service is started at the end of the installation and attempts to connect to Orchestrator, which replies with a temporary Robot Key that allows the service to authenticate to Orchestrator until it is provisioned in Orchestrator and the final Robot Key is retrieved.

---
### 16) Which of the following statements related to the Orchestrator MSI installation is true?
- [-] The prerequisites are no longer valid, because the installer does everything
- [-] The prerequisites are the same as the ones for the installation using scripts
- [o] The prerequisites are the same as the ones for the installation using scripts, except for the WebDeploy extension, which is not required with the MSI installation

---
### 17) What is the TCP port used by the Robot to connect to Orchestrator?
- [-] 443
- [-] 80
- [o] the port being listened to by Orchestrator
 
ｰｰｰ
### 18) The Orchestrator update using scripts can only be performed if the previous version was installed using scripts as well. Which of the following statements related to the update is true?
- [o] The existing site is updated; the keys in web.config are preserved, and new ones are added if necessary
- [-] The existing site is updated, but the existing web.config file is not, so new keys are not added
- [-] A new site is created; the packages and the content in web.config are copied to the new site; the old site is not affected

ｰｰｰ
### 19)　Which of the following security protocols is the minimum requirement in Orchestrator?
- [-] SSL 3.0
- [-] TLS 1.1
- [o] TLS 1.2
- [-] SSL 2.0

---
### 20) Why is it required to create at least one index pattern in Kibana?
- [o] To be able to access all the indices that match that pattern, considering that a new monthly index is created for every tenant
- [-] To be able to distinguish between the different months of the year
- [-] To be able to distinguish between different tenants

