---
description: >-
  This module is used to add, update, delete groups, and illustrates how to
  restrict the user not to access all projects. This is the group master data
  for the respective firm.
---

# \(Venu/Pending\) Groups \(Set Up &gt; Groups\)

## Summary

![Organization View &amp;gt; Set Up &amp;gt; Groups tab](../../.gitbook/assets/groups.png)

1. The Groups screen can be accessed by both Super Admin and Group Admin users only.
2. The actions like create, edit, delete can be performed only by the Super Admin.
3. Both SA and GA can
   * Assign/unassign users to/from the group.
   * Assign/unassign clients to/from the group.
4. The restriction of project access to users revolves around the assign or unassign the user or client to the group.

### Major components of Groups module

1. Create Group
2. Edit Group
3. Delete Group
4. Assign/ Unassign Users to Group
5. Assign/ Unassign Clients to Group

## 1. Create Group

![Create Group button &amp;gt; Enter group name &amp;gt; Create button](../../.gitbook/assets/create-group.png)

1. Super Admin has access to create groups.
2. Clicking the ‘Create Group’ button displays the ‘Create Group’ dialog.
3. Enter the name of the group and clicking the 'Create' button adds the group to screen.

{% hint style="warning" %}
Duplicate groups won't be allowed while adding a group.
{% endhint %}

## 2. Edit Group

![Find the group that you wish to edit &amp;gt; Edit icon &amp;gt; Input the revised name &amp;gt; Update button](../../.gitbook/assets/edit-group.png)

1. Super Admin has access to revise the group name.
2. Clicking the ‘Edit’ icon displays the ‘Edit Group’ dialog.
3. Enter the revised name of the group and clicking the 'Update' button updates the group name.

{% hint style="warning" %}
Duplicate groups won't be allowed while editing a group.
{% endhint %}

## 3. Delete Group

![Find the group that you wish to delete &amp;gt; Delete icon &amp;gt; Clicking OK in the confirmation alert deletes the group](../../.gitbook/assets/delete-group.png)

1. Super Admin has access to delete the group.
2. Clicking the ‘Delete’ icon displays the delete confirmation alert.
3. Clicking the 'OK' button in the confirmation alert deletes the group.

{% hint style="info" %}
NOTE: A group cannot be deleted when it has at least one project.
{% endhint %}

![Group cannot be deleted when it contains at least one project](../../.gitbook/assets/delete-group-with-projects.png)

## 4. Assign/ Unassign Users to Group

1. Search the group that you wish assign users or clients to it.
2. Click the 'Assign Users/Clients to Group' icon under the Actions column.
3. SA & GA can select one or more users on LHS side and clicking the right arrow assigns the users to the Group.
4. With this, not all users of Organization would be displayed under the ‘Administration -&gt; Users -&gt; Assign User’ screen, instead admins can see only the users who are mapped to the respective Group in which the current Project file is present.
5. SA & GA can select one or more users on RHS side and clicking the left arrow unassigns the users from the Group.

## 5. Assign/ Unassign Clients to Group

1. SA & GA can select one or more clients on LHS side and clicking the right arrow assigns the clients to the Group.
2. With this, not all clients of Organization would be displayed ‘Create Project’ or ‘Edit Project Information’ screen, instead admins can view only the clients that are mapped to the respective Group in which the Project is getting created.
3. SA & GA can select one or more clients on RHS side and clicking the left arrow unassigns the clients from the Group.

