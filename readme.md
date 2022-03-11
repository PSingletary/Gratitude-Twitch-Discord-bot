# A Twitch/Discord Gratitude Bot

## CORE FEATURE : Post Twitch stream summary to Discord (webhook)

 - Hype Trains - How Many at each level
(1 train at level 5, 2 trains at level 3)
 - Gifted Subs - Who gave How Many
(Gifter 1 gave 5 subs, Gifter 2 gave 10 subs)
 - Bits - Who Gave
 - Resusbscribed - Who
 - Subscribed - Who
 - New Followers - How Many
 - Total Followers - How Many

**Match Twitch Account to Discord Account**
 - One summary per stream.
 - If stream instability means stop/starts of stream would cause multiple posts, then the Last 8 hours of stream activity

Important contextual requirements
 - Docker : docker-compose.yml

### Stretch Features 1 : Web dashboard (improve UX for people who don't push code)

 - Authenticate in With Twitch
 - Associate to Discord Server
 - any items in core feature can be turned on/off
 - Set the time frame for Events (Last 8 hours)

### Stretch Features 2 : End Credits - like a SteamElements overlay, access with a URL in OBS
 - Thanks to Mods active during stream
 - Thanks to People who gifted subs or cheered bits (don't include Mods)
 - Thanks to Active Subscribers (don't repeat above two)
 - Thanks to Active Chatters (don't repeat above 3)
