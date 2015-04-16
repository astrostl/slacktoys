# slacktoys
Misc utilities that interact with the Slack team communication platform

## slack_mfa_audit
### Requirements
* curl
* [jq](https://stedolan.github.io/jq/)
* environment variables for your Slack team, [API token](https://api.slack.com/web), and reporting channel

usage: slack_mfa_audit annoy|report|noop

ANNOY: messages MFA instructions to non-MFA users, reports stats to a channel

REPORT: reports stats to a channel

NOOP: reports messages that would have been sent and stats to the CLI
