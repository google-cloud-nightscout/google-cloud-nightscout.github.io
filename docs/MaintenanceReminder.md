---
title: "Google Cloud Nightscout maintenance reminder"
description: "Set up a recurring reminder to protect your Google Cloud Nightscout site. Perform regular backups and log in to FreeDNS to prevent data loss or service interruption."
---

# Google Cloud Nightscout maintenance reminder  
[Google Cloud Nightscout](../) >> Maintenance reminder  
  
#### **Why this matters**   
If a Google Cloud payment issue occurs, your project may be suspended or deleted and your Nightscout data could be permanently lost.  
  
Additionally, you must log in to your FreeDNS account periodically. If the account becomes dormant, your Nightscout site will go offline until you log in again to reactivate it.  
  
#### **Twice-yearly maintenance checklist**  
1- [Restart the server](./Restart.md).  Wait 10 minutes to ensure the system is fully back up.  
2- Use the [Backup guide](./DatabaseBackup.md) to create a backup on your virtual machine.  
3- Download the backup file to your computer.  
4- Upload the backup file to secure cloud storage (such as Google Drive).  
5- Log in to your FreeDNS account to keep it active.  
  
These steps take only a few minutes and greatly reduce the risk of data loss or service interruption.  
  
#### **Uploader data retention**  
Configure your uploader to retain at least six months of data. This overlap helps protect recent data in a worst-case scenario.   
  
#### **Set a recurring reminder**  
Create a recurring calendar reminder to complete this checklist twice per year.  

  
