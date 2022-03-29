# Twitch references
* Twitch API: https://dev.twitch.tv/docs/api/
* TwitchAPI Discord Server : https://discord.gg/8NXaEyV
* TwitchDev Discord Server : https://discord.com/invite/G8UQqNy
* TwitchCLI : https://github.com/twitchdev/twitch-cli (helps generate test data)
* Twitch Dev Application : https://dev.twitch.tv/console/apps
## Twitch OAuth scopes
https://dev.twitch.tv/docs/authentication#scopes
### Required Scopes
- channel:read:hype_train
- channel:read:subscriptions
- bits:read
### Maybe useful Scopes
- user:read:follows
- user:read:subscriptions
- chat:read
## Checklist
- [ ] Data storage for counting events
- [ ] Read Hype Train End at what Level (https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types#channelhype_trainend)
- [ ] Count Hype Trains of Each Level - Data Storage
- [ ] Read Subs Gifted (https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types#channelsubscriptiongift)
- [ ] For Each Chatter Total Count of Subs Gifted - Data Storage
- [ ] Read Bits Cheered (https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types#channelcheer)
- [ ] Read Subscribe and record each chatter (https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types#channelsubscribe)
- [ ] Read ReSubscribe and record each chatter (https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types#channelsubscriptionmessage)
- [ ] Read New Followers (https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types#channelfollow) *NO SCOPE NEEDED*
- [ ] Total Count of New Followers during stream - Data Storage
- [ ] Write data to discord webhook (https://discord.com/developers/docs/resources/webhook#create-webhook)
# Discord references
* Discord Developer Documentation : https://discord.com/developers/docs/intro
* Official Discord Developers server : https://discord.gg/discord-developers
* GitHub : https://github.com/discord
