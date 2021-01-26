# Introduction
The purpose of this project is specified in [ProjectIntroduction](./ProjectIntroduction.md).

# Project Submission Items
## Screenshots
1. back-end build failed: ![SCREENSHOT01](screenshots/SCREENSHOT01.png)
2. back-end test failed: ![SCREENSHOT02](screenshots/SCREENSHOT02.png)
3. back-end scan failed: ![SCREENSHOT03](screenshots/SCREENSHOT03.png)
4. slack notification: ![SCREENSHOT04](screenshots/SCREENSHOT04.png)
5. deploy-infrastructure failed
   1. using wrong key: ![SCREENSHOT05](screenshots/SCREENSHOT05.png)
   2. invalid resource type (not sure if it has to be exactly the same reason to fail as shown in the example...): ![SCREENSHOT05-1](screenshots/SCREENSHOT05-1.png)
6. Appropriate job failure for the smoke test job. ![SCREENSHOT06](screenshots/SCREENSHOT06.png)
7. Successful rollback after a failed smoke test. ![SCREENSHOT07](screenshots/SCREENSHOT07.png)
8. Successful promotion job. ![SCREENSHOT08](screenshots/SCREENSHOT08.png)
9.  Successful cleanup job ![SCREENSHOT09](screenshots/SCREENSHOT09.png)
10. Only deploy on pushed to `master` branch: ![SCREENSHOT10](screenshots/SCREENSHOT10.png)
11. a graph of your EC2 instance including available memory, available disk space, and CPU usage. ![SCREENSHOT11](screenshots/SCREENSHOT11.png)
12. an alert that was sent by Prometheus: ![SCREENSHOT12](screenshots/SCREENSHOT12.png)

## Urls
Public Url to GitHub repository (not private) [URL01]

Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]

Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]

Public URLs to deployed application back-end in EC2 [URL04]

Public URL to your Prometheus Server [URL05]

## Presentation

# Build Steps

# Random Notes

## Connect CircleCI to Slack
Get instructions at: CircleCI Project Settings -> Slack Integration.
1. Setup Authentication: https://github.com/CircleCI-Public/slack-orb/wiki/Setup
   - SLACK_ACCESS_TOKEN: The OAuth token acquired through the previous steps.
   - SLACK_DEFAULT_CHANNEL: If no channel ID is specified, the Slack orb will attempt to post here.
2. Integrate Slack orb: https://circleci.com/developer/orbs/orb/circleci/slack


