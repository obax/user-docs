# Manage users in your organizations

Select the **Members** top-level menu option to manage your organization's members, you can:

* [Add members](manage-users-in-your-organizations.md#add-members)
* [Revoke pending invites](manage-users-in-your-organizations.md#revoke-pending-invites)
* [Change member roles](manage-users-in-your-organizations.md#change-member-roles)
* [Delete members](manage-users-in-your-organizations.md#delete-members)
* [Filter and sort views](manage-users-in-your-organizations.md#filter-and-search-views)

{% hint style="info" %}
Relevant permissions are required to perform all these tasks; see [managing-permissions.md](managing-permissions.md "mention").
{% endhint %}

### Add members

To add new users to your organization, click **Add members**:

![](<../../../.gitbook/assets/Screen Shot 2022-02-24 at 12.51.45 PM.png>)

From here:

* Select **Invite new members** to send an email invitation to a new user. Enter the email addresses of users to invite (separated by commas), then click **Send invite**.
* Select **Add existing members** to add existing members of your group to this organization. Select the members when prompted then click **Invite members.**
* (For Free plan users only) Select **Invite by link** to send a link; click **Copy link** then send the link yourself.

Use the **New members join as** drop-down to define the default joining role for the new member (such as **Org admin**). See [managing-permissions.md](managing-permissions.md "mention").

#### Video tutorial

To see a demonstration of adding members, play this 2-minute video:

{% embed url="https://thoughtindustries-1.wistia.com/medias/qqmkcaequj" %}

### Revoke pending invites

To remove pending invites:

1. On the **Members** page, below the search bar, click **Revoke pending invites** (see image below). Note: Link appears when there is at least one pending invite.
2. In the **Pending invites in \_your organization's name**\_ modal that appears, click the ![](<../../../.gitbook/assets/Screenshot 2022-03-11 at 08.05.56.png>) icon next to a user's name to cancel their invite.

![Revoke pending invites](<../../../.gitbook/assets/revoke-pending-invites-example (1).png>)

### Change member roles

To change the role of a member, click on the member's **Role** entry, and use the drop-down to select the new role:

![](<../../../.gitbook/assets/Member roles.png>)

{% hint style="warning" %}
For Enterprise plan customers who created custom member roles, Snyk prevents users from assigning roles to others that have more privileges than what they already have. You would encounter the following error, while trying to update the role of a member, invite a new member or add an existing member with a role that has more privileges than the logged in user.
{% endhint %}

![](<../../../.gitbook/assets/Screenshot 2022-08-01 at 15.51.05 (1).png>)

### Delete members

To delete a member from the organization:

1. Click the ![](<../../../.gitbook/assets/Screenshot 2022-03-11 at 08.05.56.png>) icon next to the user.
2. Click **Delete member from** _**your organization’s name**_ when prompted.

### Filter and sort views

#### Filter views

Click the filter icon (![](<../../../.gitbook/assets/Screenshot 2022-03-11 at 08.47.59.png>)) to expand the filter sidebar, to filter members displayed, by role or authentication method:

![](<../../../.gitbook/assets/Screenshot 2022-03-11 at 08.51.43.png>)

#### Sort views

You can sort user views by clicking on the column heading:

![](<../../../.gitbook/assets/Screenshot 2022-03-11 at 09.01.07.png>)

You can sort by Name, Authentication method, Role, and Date joined
