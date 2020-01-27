---
description: >-
  This module lets the Archive Manager configure the Archive Policy based on
  Engagement Types. This policy gets validated while archiving the project.
---

# \(Venu/Pending\) Set Up &gt; Archive Condition

## Summary

> In order to archive a project, it has to satisfy a set of archive preconditions called archive policy, and this policy can be set up on the ‘Archive Condition’ screen.

1. Click the 'Set Up' button from the left navigation menu of the Organization View.
2. Click the 'Archive Condition' tab at the top of the 'Set Up' page.
3. This screen can be accessed by Super Admin and Group Admin users only.
4. But the operations like create, update, delete, move engagement types, move archive preconditions can be performed only by the Super Admin with the ‘Archive Manager’ permission.
5. Intended engagement types can be maintained as one ‘Archive Condition’ group and can set an archive policy to it.
6. This policy will get validated while archiving the project.

### Major components of Archive Condition

1. Default Archive Policy
2. Move Archive preconditions
3. Reset Archive Condition
4. Create Archive Condition
5. Edit Archive Condition
6. Copy Archive Condition
7. Move Engagement Types to Archive Condition

## 1. Default Archive Policy

* By default, the newly created Customer has only one archive policy named ‘Default Archive Condition’.
* All Engagement Types of Organization are assigned to this 'Default Archive Policy'.
* The archive preconditions are set as follows to this policy.
  * Required Conditions
    * **Re Sign Off 1** Sign Off again on every modified sign off \(No red colored sign off\)
    * **Opened Files** All Workpaper & Permanent File closed
    * **Review Sign Off** All Workpaper & Permanent Files Review signed off
    * **QC Review** All assigned Workpaper & Permanent Files are reviewed by Quality Control
    * **Attention Status** All Workpaper & Permanent Files are Completed
    * **Comments** All Comments on the Workpaper & Permanent Files are deleted
    * **Timeline** All items in the Timeline are completed
    * **PBC List** All items in the PBC List are completed
    * **PBC Attachments** All attachments in the PBC List are deleted
    * **Trash** All items in the Trash are deleted
    * **Final Issuance Date** Set the Final Issuance Date for the Archive
    * **Project Lock** Lock the project for the Archive
  * Optional Conditions
    * **Re Sign Off 2** Sign Off again on every modified contents \(No red \*\)
    * **Preparer Sign Off** All Workpaper & Permanent Files have Preparer sign off
    * **EP Review** All Workpaper & Permanent Files have Engagement Partner sign off
    * **CP Review** All Workpaper & Permanent Files have Concurring Partner sign off
    * **Rationale** Submit the Rationale for all modified files after the Final Issuance Date

## 2. Move Archive precondition

1. The right-hand side section of the screen is called as Archive preconditions \(archive policy\).
2. The move icon gets displayed before each archive precondition with a mouse hover.
3. Click & hold the move icon for a precondition and move to the Optional Condition section from the Required Condition.
4. Click the 'Save' button on the bottom of the screen.
5. Success message gets displayed on the top-right of the screen.
6. The archive preconditions can be moved to the Optional Condition from the Required Condition and vice-versa.

{% hint style="info" %}
The archive precondition history \(who & when\) can be seen next to the 'Save' button.
{% endhint %}

## 3. Reset Archive Condition

