Simple Slack bot, responds on "hello" in #general channel

docker run -e SLACK_BOT_TOKEN=<SLACK_BOT_TOKEN> \
           -e SLACK_APP_TOKEN=<SLACK_APP_TOKEN> \
           -e DEFAULT_CHANNEL=<DEFAULT_CHANNEL> \
           dkrinitsyn/slack_bot:latest