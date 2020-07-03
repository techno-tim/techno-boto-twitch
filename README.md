# techno-boto-twitch

This is a simple moderation bot that can be added to your own Twitch channel.

For instructions, please see [https://youtu.be/7uSjKbAUHXg](https://youtu.be/7uSjKbAUHXg)

## Getting started

If you need help setting up your machine for JavaScript development, see https://www.youtube.com/watch?v=kL8iGErULiw

[Sign Up for a Twitch Developer Account](https://dev.twitch.tv/)

[OAuth Scopes](https://dev.twitch.tv/docs/authentication#scopes)

After signing up, you can get your token by visiting:

https://id.twitch.tv/oauth2/authorize?client_id=CLIENT_ID&redirect_uri=YOUR_HOST&response_type=token&scope=chat:read+chat:edit+channel:moderate

After authorizing, you will be rdirected to `YOUR_HOST` and the access token will be in the URL `access_token` param.

Replace `CLIENT_ID` and `YOUR_HOST` with the values for your newly created Twitch application from the dev portal.

## Credits

It was created by TechnoTim:

[Techno Tim on YouTube](https://www.youtube.com/TechnoTimLive)

[Techno Tim on Twitch](https://www.twitch.tv/technotim)
