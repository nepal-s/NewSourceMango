Mango

Introduction

Welcome to Mango! This document aims to streamline the setup and deployment process, providing comprehensive instructions for building and running the project on both macOS and Windows platforms.

Prerequisites

Before you begin, make sure you have the following prerequisites installed on your system:

•	Virtual Machine or System Emulator: You'll need a virtualization solution such as UTM to run a Windows environment on your macOS system.
•	Windows System Image: Download a Windows system image compatible with your virtualization software.
•	Java Development Kit (JDK) 1.8.0_202: You can download the JDK from Oracle's website.
•	Apache Tomcat 9.x.x: Visit the Tomcat download page to download the desired version.
•	Apache Ant 1.10.14: Download Apache Ant from the official website.
•	Supplementary Packages: Ensure you have necessary packages like Spice Tools for proper I/O and network drivers within the virtualized environment.

Installation

For MacBook
1.	Set Up Virtual Machine: Download and configure a virtual machine or system emulator like UTM.
2.	Windows System Image: Obtain a Windows system image compatible with your virtualization software.
3.	Configuration: Customize the virtual machine settings including RAM, storage space, and additional drivers.
4.	Virtual Windows Machine: Create and start the virtual Windows machine. 
5.	The remaining process is similar to windows.

For Windows
1.	Install JDK: Install Java JDK 1.8.0_202 on your Windows machine. You can get it from https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html
2.	Install Apache Tomcat: Download and install Apache Tomcat 9.x.x from https://tomcat.apache.org/download-90.cgi
3.	Install Apache Ant: Download and install Apache Ant 1.10.14 from Apache Ant's download page. You can get it here: https://ant.apache.org/bindownload.cgi


Environment Setup
1.	Set JAVA_HOME: Set the JAVA_HOME environment variable to the JDK directory.
2.	Add Apache Ant to PATH: Add the Apache Ant bin directory to the PATH environment variable.

Project Setup
1.	Download Project Files: Clone or download the project files from the GitHub repository.
2.	Modify build.properties: Update tomcat.home and db.url in the build.properties file to match your directory structure.

Deployment
1.	Start Tomcat: Run “./startup.sh” in Tomcat's bin directory to start the server.
2.	Build and Deploy: Navigate to the project directory in PowerShell and run “ant fullDeploy” to build and deploy the project. Use “ant reload” to reload the project after making changes.
3.	If changes are made to the source code, repeat step 2.
Usage:
1.	Login to Manager App: Access the Manager App using default credentials (username: admin, password: admin).
2.	Explore the Application: Navigate to /test to access the Mango landing page. Explore and utilize the application's features as needed.
Shutdown
1.	Close Project Execution: When done, run “./shutdown.sh” to gracefully shut down the project.

Identified Bugs


GitHub URL
https://github.com/nepal-s/NewSourceMango

Support

For any assistance or inquiries, please reach out to either of the following individuals:

•	Eluri Sai Karthik(saikare@clarkson.edu)
•	Garshan Kumar Konuguru (konugug@clarkson.edu)
•	Giovanne Pinto (pintoge@clarkson.edu)
•	Sahil Nepal (nepals@clarkson.edu)
•	Surendra Gutta (guttas@clarkson.edu)



