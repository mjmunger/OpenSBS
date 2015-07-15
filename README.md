# OpenSBS
A free, open source, Linux based replacement for Microsoft Small Business Server.

#Project Scope
This project aims to replace the primary features used by small businesses with 75 or less employees, which were previously fulfilled by the Microsoft Small Business Server, including:
* Active Directory User Control and Permissions
* Email
* Centralized calendar management, including shared calendars
* Centralized contact management.
* Centralized task management.
* Mobile device (Android / iPhone) support, which will afford users access to the feature set above.
* Meaningful integration with ownCloud
 
# Methodology
The primary deliverables of this project will be a set of scripts, which will take an ordinary (new) installation of Debian Linux, and download the required packages to create the features set. In addition, this project may create additional items, add-ons, scripts, or applications to serve as a bridge between these products to product the desired outcome and full feature set support.

#Technology Used in this Project
* Email Server: Postfix
* Active Directory Server: Samba 4
* Calendar Server: ?
* Address Book Server: ?
* Task Server: ?

#Supported Clients
Initially, this project aims to support the following email / task clients:
* Outlook 2010/2013
* Thunderbird
* Android
* iPhone

#Supported Protocols
Ideally, ActiveSync will be responsible for syncing calendar, contact, email, and task information.
