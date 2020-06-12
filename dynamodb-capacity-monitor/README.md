This workflow sends a notification to Slack when DynamoDB provisioned capacity exceeds defined limits.

## Prerequisites

Before you run this workflow, you will need the following:
- An [AWS](https://aws.amazon.com/) account and credentials with read access to DynamoDB.
- A [Slack](https://slack.com/) workspace and an appropriate channel to send notifications to.

## Configure the workflow

- Define the following parameters:
    - `slackChannel`: the slack channel to send notifications to.
- Setup unconfigured connections from the **Settings** sidebar:
    - Configure the Slack connection `slack-connection`.
    - Configure the AWS connection `aws-connection`.
- Update the `capacity` specification if desired.


