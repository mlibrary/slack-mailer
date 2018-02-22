# slack-mailer

Slack does not seem to offer a possibility to forward channel posts via email. What Slack does offer is a Webhook. It can be configured to call a certain URL every time someone is posting into a certain channel or posting a certain trigger word.

```ini
; config.ini:
to = "Example Name" <example@example.com>
slack_token = XXXXXXXXXX
domain = example.com
```
