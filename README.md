# Telegram Bot Template


1) Go to https://t.me/botfather, run '/newbot', set bot name ending in 'bot' case insensitive
2) Save access token as environment variable TELEGRAM_TOKEN of this project
3) Deploy this project and run the below CURL command to set the webhook to the deployment URL
   `curl -X POST https://api.telegram.org/bot<YOUR-BOT-TELEGRAM-TOKEN>/setWebhook -H "Content-type: application/json" -d '{"url": "https://project-name.username.vercel.app/api/webhook"}'`

