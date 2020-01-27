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
7. The LHS of the screen is called as 'Archive Condition' list.
8. The RHS of the screen is called as 'Archive preconditions' list

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

> Using this, the archive preconditions on the RHS of the screen can be moved to the Optional Condition from the Required Condition and vice-versa.

1. The right-hand side section of the screen is called as Archive preconditions \(archive policy\).
2. The move icon gets displayed before each archive precondition with a mouse hover.
3. Click & hold the move icon for a precondition and move to the Optional Condition section from the Required Condition.
4. Click the 'Save' button on the bottom of the screen.
5. Success message gets displayed on the top-right of the screen.

{% hint style="info" %}
The archive precondition history \(who & when\) can be seen next to the 'Save' button.
{% endhint %}

## 3. Reset Archive Condition

> Using this, the archive preconditions can be moved back to their original positions.

1. On the LHS of the screen, click the up arrow next to the archive condition name that you wish to reset.
2. The horizontal three dots button will be displayed.
3. Clicking the three dots button displays a menu with the options: "Edit, Reset, Copy, Delete".
4. Click the 'Reset' option.
5. Reset confirmation alert will be displayed.
6. Clicking the 'OK' button in the confirmation alert shows the success message on the top-right of the screen and resets the preconditions back to their original places.

{% hint style="info" %}
The 'Reset' will be displayed only when there is at least one change in the preconditions order.
{% endhint %}

## 4. Create Archive Condition

> Using this, new archive conditions can be added.

1. Click the 'plus' icon next to the 'Archive Conditions' title presented on the top-left of the screen.
2. The 'Add Archive Condition' dialog will be displayed.
3. Enter the 'Title\*' and 'Description' for the archive condition.
4. Click the 'Save' button.
5. Wait till the red loading bar on the top of the screen gets finished.
6. The success message will be displayed on the top-right of the screen.
7. The created new archive condition will be displayed on the Archive Conditions list.

{% hint style="warning" %}
Duplicate archive conditions won't be allowed while adding.
{% endhint %}

## 5. Edit Archive Condition

> Using this, the name of the archive condition can be revised.

1. On the LHS of the screen, click the up arrow next to the archive condition name that you wish to edit.
2. The horizontal three dots button will be displayed.
3. Clicking the three dots button displays a menu with the options: "Edit, Reset, Copy, Delete".
4. Click the 'Edit' option.
5. The 'Edit Archive Condition' dialog will be displayed.
6. Enter the revised Title or Description.
7. Click the 'Save' button.
8. Wait till the red loading bar on the top of the screen gets finished.
9. The success message will be displayed on the top-right of the screen.

{% hint style="warning" %}
Duplicate archive conditions won't be allowed while editing.
{% endhint %}

{% hint style="warning" %}
The name of 'Default Archive Condition' cannot be updated, so the 'Edit' option won't be displayed to it.
{% endhint %}

## 6. Copy Archive Condition

> Using this, the archive condition policy can be duplicated.

1. On the LHS of the screen, click the up arrow next to the archive condition name that you wish to duplicate.
2. The horizontal three dots button will be displayed.
3. Clicking the three dots button displays a menu with the options: "Edit, Reset, Copy, Delete".
4. Click the 'Copy' option.
5. Confirmation alert for the duplication will be displayed.
6. Click the 'OK' button in the confirmation alert.
7. Wait till the red loading bar at the top of the screen gets finished.
8. The success message will be displayed on the top-right of the screen.
9. The duplicate archive condition with the exact archive preconditions will be created.

{% hint style="warning" %}
The duplicate archive condition name is suffix with '-1'. The number is auto-incremented for the next duplication.
{% endhint %}

## 7. Delete Archive Condition

> Using this, the archive condition can be deleted.

* On the LHS of the screen, click the up arrow next to the archive condition name that you wish to delete.
* The horizontal three dots button will be displayed.
* Clicking the three dots button displays a menu with the options: "Edit, Reset, Copy, Delete".
* Click the 'Delete' option.
* Delete confirmation alert will be displayed with the following message.
  * Upon deletion, the engagement types under this archive condition will be moved to the Default Archive Condition policy. Do you want to continue?
* Click the 'OK' button in the confirmation alert.
* Wait till the red loading bar at the top of the screen gets finished.
* The success message will be displayed on the top-right of the screen.
* The archive condition will be removed from the screen.

{% hint style="warning" %}
The 'Default Archive Condition' cannot be deleted, so the 'Delete' option won't be displayed to it.
{% endhint %}

{% hint style="info" %}
Deleting the archive condition moves all it's engagement types to the ‘Default Archive Condition’ policy.
{% endhint %}

## 

