A bot that hangs out in the UC Tech Slack team and welcomes new members as they join the workspace.

## Configuration

The bot expects the following environment variables.

| Variable Name | | Notes |
| --- | --- | --- |
| `BOT_TOKEN` | required | Your bot token. |
| `CLIENT_ID` | required | Your app's client id. |
| `CLIENT_SECRET` | required | Your app's client secret. |
| `CLIENT_SIGNING_SECRET` | required | Your app's client signing secret. |

Add them to your `.env` file for local development, or as config variables to your hosting environment, e.g. [Heroku](https://devcenter.heroku.com/articles/config-vars).

## Customizing the welcome message

Update `welcome.txt` found in this project.

## Attribution

This bot was created using the [Botkit starter kit for slack](https://github.com/howdyai/botkit/tree/master/packages/generator-botkit#readme).


