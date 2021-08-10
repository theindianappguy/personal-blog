---
title: "Google Forms to Slack"
date: "2021-08-10T07:15:53+0000"
template: "post"
draft: false
slug: "google-forms-to-slack"
category: "Tools"
tags:
  - "Slack"
  - "Google FromsAddon"
description: "Integrate Google Froms and Slack to send Personalised Message including answers to the questions on new form submission"
socialImage: "/media/image-0.jpg"
---

So For my product [blurweb.app](https://blurweb.app) I have an affiliate program, To apply for it people submit a google form now the problem is i was not receiving notification for it.

Email is full so even if i setup email notifications i might or might not get it, i have been using slack to connect with founders communities so i decided to integrate slack with google forms.

When i searched i didn't find a simple solution. So i build [slacknotify.app](https://www.slacknotify.app) - its a google forms addon just intall submit webhook url(two clicks to get this) write personalised message and you are done.

- Step1: [Install SlackNotify](https://workspace.google.com/marketplace/app/slack_notifications_for_google_forms/451493071820)
- Step2: Create a slack app and get webhook url
  visit: [Create App](https://api.slack.com/messaging/webhooks)

`video: /media/slackwebhookurl.mp4`

- Step3: Open/Create new Google form, click on addons and click on slacknotify.

`video: /media/use-slacknotify-app.mp4`

In the app enter the webhook url and personalised message and click on submit. That's all now submit the google forms and you will get notification in slack.

if face any problem please send a mail at contact@sanskar.dev

so as you can see Sharing Google Form response in slack, as direct message or as a channel message can be done very easily with slacknotify.app
