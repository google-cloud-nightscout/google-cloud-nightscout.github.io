---
title: "Google Cloud Nightscout Backup Reminder"
description: "Set up a recurring reminder to back up your Google Cloud Nightscout site. Reduce the risk of data loss by building a simple backup habit."
---

# Google Cloud Nightscout Backup Reminder  
[Google Cloud Nightscout](../) >> Backup Reminder  
  
#### **Why This Matters**  
If there is a problem with your credit card and a payment is delayed, Google Cloud may suspend or delete your project. In that situation, your Nightscout data could be permanently lost.  
There is already a detailed backup guide available. This page is not a replacement for that guide. Instead, it focuses on one important habit: making sure backups are actually done on a regular schedule.  
  
#### **How Often Should You Back Up?**  
A practical approach is to create a backup twice per year. The entire process usually takes only a few minutes:  
  
1- Follow the existing Database Backup guide to create a backup on your virtual machine.  
2- Download the backup file to your computer.  
3- Upload the backup file to secure cloud storage (such as Google Drive or another reliable location) for safekeeping.  
  
Even if you back up only every six months, you are protecting yourself from a total data loss scenario.  
  
#### **Add an Extra Layer of Protection**  
For additional safety, configure your uploader to retain several months of data locally.  
Ideally, your uploader should retain at least as much data as the time between your backups. For example, if you create backups every six months, your uploader should retain at least six months of data. This overlap helps protect you in a worst‑case scenario:  
- Your Nightscout backup protects older data.  
- Your uploader retains recent data until it is uploaded again.  
  
This layered approach significantly reduces risk.  
  
#### **Set a Recurring Calendar Reminder**  
Backups only work if they are done consistently. Create a recurring calendar reminder to back up your Nightscout site twice per year.  
Completing the backup process takes only a few minutes twice a year. For such a small time investment, the protection and peace of mind are well worth it.  
  
Build the habit now, and you greatly reduce the chance of ever losing your data.  
