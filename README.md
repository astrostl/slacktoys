# slacktoys
Misc utilities that interact with the Slack team communication platform

## slack_mfa_audit
### Requirements
* curl
* [jq](https://stedolan.github.io/jq/)
* environment variables for your Slack team, [API token](https://api.slack.com/web), and reporting channel

usage: slack_mfa_audit annoy|report|noop

ANNOY: messages MFA instructions to non-MFA users, reports stats to a channel

![annoy](https://cloud.githubusercontent.com/assets/1126471/7189641/e0e8a846-e445-11e4-878e-7cc312296080.png "annoy")

REPORT: reports stats to a channel

![report](https://cloud.githubusercontent.com/assets/1126471/7189658/f9d2b6d0-e445-11e4-98a5-dfa671acccfe.png "report")

NOOP: reports messages that would have been sent and stats to the CLI

![noop](https://cloud.githubusercontent.com/assets/1126471/7190368/4048a660-e44b-11e4-8471-795679a66109.png "noop")
