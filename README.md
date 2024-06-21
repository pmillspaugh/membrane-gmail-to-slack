# Gmail to Slack notifications

<iframe src="https://share.descript.com/embed/VNAlee2IAoo" width="640" height="360" frameborder="0" allowfullscreen></iframe>

## Setup

1. Sign up for [Membrane](https://membrane.io)
1. Install the Membrane `slack` driver ([instructions](https://docs.membrane.io/concepts/drivers/))
1. Fork this `gmail-to-slack` program in your workspace ([instructions](https://docs.membrane.io/getting-started/first-program/))
1. Create a Slack app: [api.slack.com/quickstart](https://api.slack.com/quickstart)
1. Add OAuth scopes `im:history`, `im:read`, `im:write`, `chat:write`, `users:read` to your app bot: [api.slack.com/apps/A078U9S3X7G/oauth](https://api.slack.com/apps/A078U9S3X7G/oauth?from_app_home=1)
1. Configure the `slack` driver with your bot token
1. Set up a forwarding rule in Gmail to your program's email address

If you'd a hand getting set up, don't hesitate to [email me](mailto:pete@membrane.io). We are eager to make sharing Membrane programs easier, so we'd love your feedback on what's confusing and what works.
