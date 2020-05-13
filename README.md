# Self-Invitation in Slack: No More Manual Invites

## Overview
 
A community needs a place to interact with each other. [Slack](https://slack.com/) has been one of the ways people do exactly that.

One bottleneck was that an existing member of the Slack chat had to invite people manually.
Fortunately, projects like [Slackin](https://github.com/rauchg/slackin) came along to streamline this process.

Now, Slack has made changes to their [invitation flow](https://slack.com/help/articles/201330256-Invite-new-members-to-your-workspace), and people can self-invite themeselves via a shared link.

This doc describes how you can integrate this self-invite flow (aka, shared link) into your project's README, or site.

## Process

First, you will need to retrieve a shared invitation link. This link lets new members to join directly without you inviting them one by one.

Here is how to get the link:

1) Go to Profile Settings
<img src="/assets/profile.png" alt="Profile Settings" width="300px"/>

2) Select "Invite people to [NAME_OF_YOUR_WORKPLACE]"
<img src="/assets/invitation-profile.png" alt="Profile Invitation" width="300px"/>

3) In the Invitation Window, press "Share invite link"
<img src="/assets/invitation-window.png" alt="Invitation Window" width="500px"/>

4) Press "Deactivate link". It's done because the default link expires in 30 days.
<img src="/assets/deactivate-link.png" alt="Deactivate Link" width="500px"/>

5) In the Invitation Window, press "Get an invitation link"
<img src="/assets/get-link.png" alt="Getting Shared Link" width="500px"/>

6) Set the expiration date for the invitation link to "Never expire"
<img src="/assets/expiration.png" alt="Expiration Window" width="500px"/>

7) Copy the invitation link
    *(Optional)* Choose whether you want to be notified when someone joins by checking the checkbox
<img src="/assets/share-link.png" alt="Sharing Link" width="500px"/>

After you retrieve the shared invitation link, you can share it with your community. 

If you have a Slack workspace for an open source project, you can add a link to your README like this:
[![Slack: blue](https://img.shields.io/badge/Slack-join-blue)](https://join.slack.com/t/personal-s2q5219/shared_invite/zt-edfit7jo-Gweh_WCR3gz7o66keakO6w)

