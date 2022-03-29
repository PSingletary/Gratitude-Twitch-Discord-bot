# Mable-Twitch-Discord-bot
Mable is a bot that Twitch Streamers use to show gratitude.

## Feature 1 Thank You Note : Post Twitch stream summary to webhook (Discord)

https://github.com/PSingletary/Mable-Twitch-Discord-bot/blob/main/Twitch_Stream_Summary_References.md

**Match Twitch Account to Discord Account**
 - One summary per stream.
 - If stream instability means stop/starts of stream would cause multiple posts, then the Last 8 hours of stream activity

Important contextual requirements
 - Can be run in Docker : provide docker-compose.yml

## Feature 2 Stream supported by viewers like you - overlay, access with a URL in OBS
 - Thanks to Mods active during stream
 - Thanks to People who gifted subs or cheered bits (don't include Mods)
 - Thanks to Active Subscribers (don't repeat above two)
 - Thanks to Active Chatters (don't repeat above 3)

## UX : Web dashboard
 - Authenticate with Twitch
 - Associate to Discord Server / Channel
 - Any items in features can be turned on/off
 - Set the time frame for Events (Last 8 hours)
