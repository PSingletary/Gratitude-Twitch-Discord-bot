# Gratitude-Twitch-Discord-bot
Gratitude is a bot that Twitch Streamers use to show gratitude.

## Feature 1 Thank You Note : Post Twitch stream summary to webhook (Discord)

 - Hype Trains - How Many at each level (1 train at level 5, 2 trains at level 3)
 - Gifted Subs - Who gave How Many (Gifter 1 gave 5 subs, Gifter 2 gave 10 subs)
 - Bits - Who Gave (do not need to keep track of hoe many bits)
 - Resubscribed - Who
 - Subscribed - Who
 - New Followers - How Many
 - Total Followers - How Many

Important context 
 - One summary per stream.
 - If stream instability means stop/starts of stream would cause multiple posts, then the Last 8 hours of stream activity

Some Preliminary research has been completed on API and are noted here -> https://github.com/PSingletary/Gratitude-Twitch-Discord-bot/blob/main/Twitch_Stream_Summary_References.md

### Feature 2 **Match Twitch Account to Discord Account**
 - Intended result is that when webhook posts to discord that the twitch chatters are mentioned in Discord Message
 - If no Twitch / Discord association exists, it should default to Twitch username
 
## Feature 3 Stream supported by viewers like you - overlay, access with a URL in OBS
 - Thanks to Mods active during stream
 - Thanks to People who gifted subs or cheered bits (don't include Mods)
 - Thanks to Active Subscribers (don't repeat above two)
 - Thanks to Active Chatters (don't repeat above 3)

## Feature 4 Run localy in a container or deployable to IaaS

## Feature 5 Web dashboard
 - Authenticate with Twitch
 - Associate to Discord Server / Channel
 - Any items in features can be turned on/off
 - Set the time frame for Events (Last 8 hours)
