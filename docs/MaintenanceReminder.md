---
title: "Google Cloud Nightscout maintenance reminder"
description: "Set up a recurring reminder to protect your Google Cloud Nightscout site. Perform regular backups and log in to FreeDNS to prevent data loss or service interruption."
---

# Google Cloud Nightscout maintenance reminder  
[Google Cloud Nightscout](../) >> Maintenance reminder  
  
#### **Why this matters**  
If there is a problem with your credit card and a payment is delayed, Google Cloud may suspend or delete your project. In that situation, your Nightscout data could be permanently lost.  
You must log in to your FreeDNS account periodically to keep it active. If you do not log in within the required time, the account will become dormant and your Nightscout site will stop working until you log in again.  
This page focuses on building a simple habit that reduces both risks.  
  
#### **Twice-yearly maintenance checklist**  
A practical approach is to complete the following tasks twice per year. The entire process usually takes only a few minutes:  
1- Follow the existing [Database Backup guide](./DatabaseBackup.md) to create a backup on your virtual machine.  
2- Download the backup file to your computer.  
3- Upload the backup file to secure cloud storage (such as Google Drive or another reliable location) for safekeeping.  
4- Log in to your FreeDNS account to keep it active.  
  
Completing these steps twice per year significantly reduces the risk of data loss or service interruption.  
  
#### **Add an extra layer of protection**  
For additional safety, configure your uploader to retain several months of data locally.  
Ideally, your uploader should retain at least as much data as the time between your maintenance intervals. For example, if you perform maintenance every six months, your uploader should retain at least six months of data. This overlap helps protect you in a worst-case scenario:  
- Your Nightscout backup protects older data.  
- Your uploader retains recent data until it is uploaded again.  
  
This layered approach significantly reduces risk.  
  
#### **Set a recurring calendar reminder**  
Create a recurring calendar reminder to complete this maintenance checklist twice per year.  
Setting up the reminder takes less than a minute. Completing the checklist takes only a few minutes twice a year. For such a small time investment, the protection and peace of mind are well worth it.  
Build the habit now, and you greatly reduce the chance of losing access to your data or your site.  

  
