Module 5 README: Archiving and Logging Data

Module Description
In this module, we will continue to learn system administration fundamentals by working in Linux environments to back up and recover data, preserving integrity and availability.

We will use the tar command to create, list, and extract data from archives. Creating archives ensures the availability of users’ data and configuration files.

We will use the cron utility to automate computing tasks to schedule regular and automatic execution of important maintenance and security operations.

We will learn about Linux log management by performing log file management tasks and trace a series of historical events to determine if a breach has occurred. We will then audit logs that provide critical insight into an attacker’s tactics, techniques, and procedures.

We will learn how to investigate suspicious network activity to manage log sizes and enable, troubleshoot, monitor, and audit logs using journalctl, logrotate, and auditd.

Module Objectives
  
Day 1: Backups and Restoring Data with tar

Identify and describe use cases for the three kinds of backups.
Create (tar) an archive from existing files and directories.
List and search the contents of an existing archive.
Extract (untar) the contents of an archive.
Describe and demonstrate two exploits for the tar command.

Day 2: cron and Scheduled Jobs

Schedule regular jobs for individual users with crontab.
Write simple scripts for maintenance and security tasks.
Use cron to automate the execution of security scripts to perform maintenance on a regular basis.

Day 3: Managing and Monitoring Log Files

Filter cron and boot log messages using journalctl.
Perform log size management using logrotate.
Install and configure audit rules using auditd to write audit logs to disk.

Lab Environment
This module will continue to use the web lab we we used in the previous module.

Student lab access credentials:

Username: sysadmin

Password: cybersecurity

What to Be Aware Of

When editing crontabs in Day 2, you may not be able to save the settings properly. This is because the file is defaulting to DOS mode when saved. This issue typically only occurs on Windows machines. To make sure the file is not saving in DOS mode, press Alt+M when saving a file in Nano.

Security+ Domains
This module covers portions of the following domains on the Security+ exam:

2.0 Architecture and Design
3.0 Implementation
4.0 Operations and Incident Response
5.0 Governance, Risk, and Compliance

For more information about these Security+ domains, refer to the following resource:

Security+ Exam Objectives

Additional Reading and Resources

These resources are provided as optional, recommended resources to supplement the concepts covered in this module.

📚 The Linux Command Line, 2nd Edition  by William Shotts
Downloadable PDF
Pages: 230-235

📚 Linux Essentials Manual, The LPI Introductory Programme
Downloadable PDF
Pages: 145-152

Day 1 Resources

How-to Geek: How to Compress and Extract Files Using tar

Day 2 Resources

Crontab Generator

Day 3 Resources

How-to Geek: How to Use journalctl to Read Linux System Logs

Rackspace: Understanding logrotate utility

Module 5: Challenge Assignment
This module's Challenge assignment can be found in Canvas.

For this week's Challenge assignment, students will play the role of a security analyst at a financial institution. The bank has developed a log management system, but in this Challenge, students will expand and enhance their log management system by learning new tools, adding advanced features, and researching additional concepts.

Looking Forward
Module 6: Bash Scripting and Programming

Next week, you will work through a series of exercises to create custom commands and bash scripts to collect evidence, perform system audits, reconfigure a Linux installation, and take the necessary steps to harden Linux systems.

Make sure to pull the latest builds before starting the Challenge assignment.
