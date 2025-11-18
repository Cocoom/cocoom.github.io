# Notify in Teams

Cocoom allows you to be notified in Teams about newly created memos.
As a Cocoom administrator, you can choose which Teams channel will receive the notifications.

This configuration is done in 2 steps:

1. Microsoft Teams side: creating a webhook in the channel of the team or chat group of your choice
2. Cocoom side: adding this webhook to the configuration of a channel of your choice

## 1. Microsoft Teams side: creating a webhook

Open Microsoft Teams and go to the team and channel where you want to receive Cocoom notifications.

### 1.2. Extension selection

Click on the three dots next to the channel name to open the context menu, then select "Workflows".

![Step 1](/img/en/guide/msteams-app/notifications/step1-workflows-menu-selection.png)

### 1.3. Workflow type selection

Filter the workflow type by typing "Webhook" in the search field.

![Step 2](/img/en/guide/msteams-app/notifications/step2-workflow-type-selection.png)

### 1.4. Connection to use for notifications

In the workflows window, click on the 3 dots to select an existing connection or add a new connection.

Choose a name for this workflow.

![Step 3](/img/en/guide/msteams-app/notifications/step3-connections.png)

### 1.5. Notification destination selection

Select the Teams team and channel where notifications should be sent (use case for a channel notification; there is an equivalent for chat group notifications).

![Step 4](/img/en/guide/msteams-app/notifications/step4-notification-targeted-channel-choice.png)

### 1.6. Copy the Webhook link

Click the "Copy link" button to copy the webhook URL to the clipboard.

![Step 5](/img/en/guide/msteams-app/notifications/step5-link-to-copy.png)

## 2. Cocoom side: configuring a channel to be notified in Teams

Go to the administration section, then select the "Channels" menu item.

### 2.1. Edit a Cocoom channel

Click the "Edit" button for the Cocoom channel to link to Teams for notifications

### 2.2. Microsoft Teams integration

Scroll down the page to the "Integration with your tools" section until you reach the "Microsoft Teams" section.

![Step 6](/img/en/guide/msteams-app/notifications/step6-add-webhook-to-cocoom-channel.png)

### 2.3. Paste the webhook link

Paste the "Webhooks" link, previously copied, into the designated field.

You can add a comment to qualify the link (for example, the Teams team name and Teams channel name).

### 2.4. Validate the association

The association is now active and ready to relay group notifications such as when a new memo is published.

### 2.5. Verify the association

Example of a notification when content is published in the previously selected Cocoom channel.

![Step 7](/img/en/guide/msteams-app/notifications/step7-channel-notification-example.png)
