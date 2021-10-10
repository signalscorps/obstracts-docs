---
description: Learn more about managing Obstracts Groups and Users.
---

# Group Management

## Groups

### Group Management

Each user belongs to a Group. A user can only belong to one group.

Each Group has one Group Admin. By default this is the creator of the Group, however, ownership can be reassigned to any active Member of the Group.

A Group Admins can:

* invite new Members to the Group
  * user invited can choose to accept or reject invite
* delete existing Members from the Group
  * see Delete User below
* edit user permissions for member of the Group
  * see User Permissions section below

![Obstracts Group Management](../.gitbook/assets/obstracts-group-management.png)

Use the Group Management page for this: [https://app.obstracts.com/user/manage\_group](https://app.obstracts.com/user/manage_group)

### Group Plans

Each Group has a plan. By default, the free plan is assigned at sign up. Any user of the group can request a plan upgrade.

You can see a current list of plans and their restrictions here: [https://www.obstracts.com/pricing/](https://www.obstracts.com/pricing/)

## Users

### User Permissions

There are two user permissions available, read and read/write. You can see what functions are available for each permission type below:

| Function | Read | Read/write |
| :--- | :--- | :--- |
| View feed | TRUE | TRUE |
| Add/edit feed | TRUE | FALSE |
| View report | TRUE | TRUE |
| Add/edit report | TRUE | FALSE |
| View extractions \(all types\) | TRUE | TRUE |
| Add/edit extractions \(all types\) | TRUE | FALSE |
| View alerts | TRUE | TRUE |
| Add/edit alerts | TRUE | FALSE |
| Generate API key \(if supported in plan\) | TRUE | TRUE |

### User Security

Two-factor authentication to all users. It is strongly recommended that all users configure two-factor authentication.

{% hint style="info" %}
A 10% discount will be applied on Group Plans where all members have two-factor authentication enabled.
{% endhint %}

Group admins can view which of their Group Members have two-factor authentication enabled on the Group Management page: [https://app.obstracts.com/user/manage\_group](https://app.obstracts.com/user/manage_group)

### Delete user

A user or group admin can delete a members account.

A user can do this on the "My Profile" page. Group admins can do this from the "Group Management" page.

Deleting an account will delete that Members personal information \(inc. API keys\) but any content created by the Member \(e.g. Reports, Feeds, Alerts and extractions\) will remain available to the Group