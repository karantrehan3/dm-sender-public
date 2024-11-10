# [DM-Sender](https://karantrehan3.github.io/dm-sender-public/)

{% include homeButton.html %}

## Introduction

This project is a slack-bot designed to send direct messages (DMs) to users in a Slack workspace posing as you. It includes various functionalities such as OAuth authentication, redis based bull-queue management, access-control layer and platform-based handling.

The App is capable of receiving the DM to be sent as a message and then trigger it immediately or schedule it for the users you select based on the filter options.

Via BullMQ, I have imposed rate-limits and that ensures we stay well-within the limit while sending Slack DMs.

## Source Code

The source code for this is kept in a private-repository since the project has been added as an internal tool for my current org. A security-step measure. If you'd like access to the code, please drop an email at karantrehan3@gmail.com

## Architecture

{% include architecture.html %}

## Demo Video

{% include demo.html %}
