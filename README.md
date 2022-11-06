# Warp Unlimited Workers Script

* Get 1 GB per minute without deploying any server anywhere.
* Make Cloudflare account and paste the script in New Workers
* Add `referrer` from your Warp+ App. Go to Settings > Advanced > Diagnostics > ID
* Add Telegram Bot Token and Chat ID (optional)
* Go to Workers > Triggers > Cron Triggers > Add Cron Trigger, set it to 1 minute and save.
* Enjoy!

## Possible Drawback

* As Cloudflare Workers use specific IP addresses internally, this may show RATE LIMIT, if used by many users.

## Credits

* Made from [TheCaduceus](https://github.com/TheCaduceus/WARP-UNLIMITED-ADVANCED)'s Python Code
