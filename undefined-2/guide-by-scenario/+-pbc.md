---
description: >-
  This article illustrates how you can request your clients to upload auditing
  supported documents and, the workflow of email reminders for the pending
  requests.
---

# \(Venu/Pending\) PBC List - Request audit supported documents from your client

PBC stands for ‘Provided By Customer/ Client’. PBC is a list of items that users request from their audit clients when they perform audits. This is typically done by compiling the list in Excel and emailing them to the client and then they send their request by email manually.

PBC List function automates this whole process and the client can upload their requested documents directly into the application and it can alert users. 

## 1. Who can add, edit, delete PBC records?

1. Internal Users of project access rights “Project & Archive Admin, Project Admin, Project User” can create, edit, delete PBC records.
2. External Users of project access right ‘PC Upload’ can create, edit, delete PBC records. After visiting the project, they directly view the PBC List screen only.
3. The 'Read Only' users of Internal and External Type can view the PBC screen, but cannot do any actions on it.

![Project View for Internal Users](../../.gitbook/assets/pbc-list-internal-users.png)

![After visiting the project, &apos;PBC Upload&apos; user directly view the PBC List screen only.](../../.gitbook/assets/pbc-list-external-users.png)

{% hint style="info" %}
After visiting the project, they directly view the PBC List screen only. The 'Project View' left navigation will not be displayed to the 'PBC Upload' users.
{% endhint %}

## 2. How does the reminder feature work on the PBC List?

1. The 'Reminder \(days\)' is a numeric field and has the sub-columns “B, A, R”.
2. User can input the zero or bigger values in the "B, A, R" columns. \(Ex: 0, 1, 2, 3, 4...etc\).
3. **B** stands for ‘Before’, so the first email reminder notification would be sent ‘**\#B**’ days before the 'Due Date'.
4. **A** stands for ‘After’, so the next email reminder notification would be sent ‘**\#A**’ days after the 'Due Date'.
5. **R** stands for ‘Recur’, so the recursive email reminder notification would be sent for every ‘**\#R**’ days after the ‘\#A’.
6. The email reminder notifications will be recursively sent to the client users until the status is changed to 'Completed' for the pbc records.

## 3. Add PBC records

> You can add the PBC records in two ways.
>
> 1. Add records manually.
> 2. Using the 'Import' facility.

### 3.1. Add records manually

![Click &apos;PBC List&apos; menu &amp;gt; Click &apos;Add&apos; button &amp;gt; Fill details &amp;gt; Click &apos;Save changes&apos; link](../../.gitbook/assets/pbc-list-add-record.png)

1. Click the 'PBC List' in the left navigation menu of the 'Project View'.
2. Click the 'Add' button at the top of the screen.
3. An empty record will be displayed in the grid to input the details.
4. Fill the following fields:
   * **Area:** Enter the subject line here.
   * **Description:** Enter the detailed information of the PBC record here.
   * **Requested Date:** Select the future or current date here as required.
   * **Due Date:** It should be greater than or equal to the ‘Requested Date’.
   * **Reminder days \(B, A, R\):** Enter the reminder days \(numbers\) as required. \(B=Before, A=After, R=Recur\).
   * **Requested By:** Select the user.
   * **Requested To:** Select the 'External PBC upload' user whom you wish to request the documents to be shared.
5. Click the 'Save changes' link at the right-bottom of the screen, to save the records.
6. This way, you can add as many records as you required.

{% hint style="danger" %}
You cannot select the past date in the 'Requested Date' and 'Due Date' fields.
{% endhint %}

{% hint style="danger" %}
'Due Date' should be greater than or equal to the ‘Requested Date’.
{% endhint %}

### 3.2. Using the 'Import' facility

> Using this, you can add the bundle of PBC records at once.

1. Click the ‘Template’ button at the top of the screen.
2. A template excel file will be downloaded for the import into your computer.
3. Fill the excel file with as many records as you required \(Area, Description, Due Date, Before, After, Recur\).
4. Save the file.
5. Click the 'Browse' button to view the file explorer window for the file selection.
6. Select the saved file in \#5.
7. Click the 'Open' button or hit the ENTER key.
8. Click the 'Import Data' button.
9. Wait till all excel file data get inserted into the application.
10. On the screen, you can view the success message and the records that are imported.

![Click the &apos;Template&apos; button to download the template file for the bulk import](../../.gitbook/assets/pbc-list-import-1.png)

![Fill the template file &amp;gt; Browse the file using &apos;Browse&apos; button &amp;gt; Click the &apos;Import Date&apos; button](../../.gitbook/assets/pbc-list-import-2.png)

![You can view the imported records on the screen](../../.gitbook/assets/pbc-list-import-3.png)

## 4. Auditor upload documents section

> This is the place where the general auditors \(internal users\) can upload the reference documents for the client users to share the supporting documents in the suggested format.

1. It’s an optional field and has the file icon.
2. Find the PBC record that you wish to add documents for the client users reference.
3. Click the red colored file icon under the 'Auditor Upload Documents' column.
4. You will be navigated to the detail section.
5. You can add files in two ways.
   1. Using the 'Browse' button.
   2. Drag & drop of the files from your computer.
6. You can also perform the operations like update the content of the file, edit the file name and delete the file.

![Find the PBC record that you wish to add the reference documents and click the red-colored file icon](../../.gitbook/assets/auditor-upload-documents.png)

![You will be navigates to the detail page](../../.gitbook/assets/auditor-upload-documents-2.png)

![Add one or more files using the &apos;Browse&apos; button \(or\) Drag &amp; Drop facility](../../.gitbook/assets/auditor-upload-documents-3.png)



