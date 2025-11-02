---
title: "Delete Snapshot Schedule for Google Cloud Nightscout"
description: "Learn how to remove the automatic snapshot schedule on your Google Cloud Nightscout VM to avoid unexpected disk and snapshot costs. Step-by-step guide using console, CLI or API."
---

# Delete Google Cloud snapshot schedule  
[Google Cloud Nightscout](../../) >> Delete Snapshot Schedule  
<br/>  
  
As of April 2025, a snapshot schedule is automatically created when you set up a new virtual machine. Snapshots are not free.  
  
Before deleting a snapshot schedule, you must first detach it from the disk. The following clip demonstrates how to do this:  
  
<video width="400" controlsList="nodownload" src="./video/DeleteSnapshotSchedule.mp4" controls>  
</video>  
<br/>  
  
Once the schedule is deleted, you may still incur charges if existing snapshots remain. To avoid these charges, be sure to delete any remaining snapshots as well.  
  
