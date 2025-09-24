# 🚀 Teams administrator & Cocoom

As a Teams administrator, you can fully manage Teams applications that can enhanced Teams behavior or content.

The “Microsoft Teams admin center” can be reached to this URL: [Admin Center](https://admin.teams.microsoft.com)

![](/img/en/advanced/teams-setup-admin/teams-admin-dashboard.png)

To manage Apps, there is a dedicated menu in the Admin center: [Teams apps](https://admin.teams.microsoft.com/policies/manage-apps)

⇢ More info : [Microsoft doc link](https://docs.microsoft.com/en-us/microsoftteams/admin-settings)

There are 3 main parts in this menu section:

1. [Manage apps](#manage-apps): allows you to give an overview of available Apps, which one you blocked or allowed to be installed & each app properties, but also grant admin consent when requested by an app,

2. [Permission policies](#permission-policies): which app is allowed to be installed,

3. [Setup policies](#setup-policies): which apps are pre-installed, which one are pinned & even if you let users pin their apps or upload custom apps by their own.


## Manage apps

Gives you the “big picture” about the Teams applications.

⇢ More info : [Microsoft doc link](https://docs.microsoft.com/en-us/microsoftteams/manage-apps)

From here, you can check that Cocoom is listed as part of available applications.

![](https://paper-attachments.dropbox.com/s_F4554E37D88F30AB7BEBF1845EA4EDBA717C9233F7EAE67807843257ADA51AC6_1610956776062_Teams+-+Manage+apps+availability.png)


### Grand admin consent

Cocoom Teams App requires a grand admin consent to be fully functional.
This is a one-time action that must be done by a Teams administrator.

![](/img/en/advanced/teams-setup-admin/teams-admin-grant-admin-consent.png)

→ To do so, click on Cocoom app in the list, then click on the `Grant admin consent` link.


## Permission policies

From there, you can define which permissions policy to apply to 3 categories of apps:

1. Microsoft apps (ie: Power BI)
2. Third-party apps (ie: Cocoom)
3. Custom apps (the ones you develop as internal usage apps)

⇢ More info : [Microsoft doc link](https://docs.microsoft.com/en-us/microsoftteams/teams-app-permission-policies)

Shown in the image below, there’s an example of customized permissions policy defined where:

- Only Microsoft Power Apps & Power BI apps are blocked (all other Microsoft apps are allowed)
- Cocoom & Trello are the only third-party apps allowed to be installed
- We use our pre-production Cocoom app for internal usage only (for QA purpose)
![](https://paper-attachments.dropbox.com/s_F4554E37D88F30AB7BEBF1845EA4EDBA717C9233F7EAE67807843257ADA51AC6_1610957300486_Teams+-+Permission+policy+creation.png)



## Setup policies

This is where you can choose if your tenant users could pin/unpin their apps, which apps to pre-install for your tenant users & which apps are pinned by default (in which order).

⇢ More info : [Microsoft doc link](https://docs.microsoft.com/en-us/microsoftteams/teams-app-setup-policies)

In the example below, we modify the global settings, but you can also create your own customized setup policies.

![](https://paper-attachments.dropbox.com/s_F4554E37D88F30AB7BEBF1845EA4EDBA717C9233F7EAE67807843257ADA51AC6_1610957468098_Teams+-+Setup+policy.png)

There’s a last menu item which allows you to graphically customize your tenant Teams store by changing UI elements as image, color, …
We don’t go into details about this part since it doesn’t change anything about Cocoom app installation.
