---
description: >-
  There are some frequently asked questions about Shapes. Some best practices
  you may need in the future.
---

# Frequently Asked Questions

## OAuth2 Code Grant

Inviting your bot is usually quite easy, although sometimes you may receive an error regarding "Bot requires a code grant." This is due to the "Requires OAuth2 Code Grant" setting enabled. You can fix this by doing the following:

1. Go to the [<mark style="color:purple;">**Discord Developer portal**</mark>](https://discord.com/developers) and select your bot's application.
2. Under your bot's application, go to the **Bots** tab.
3. Under the **Bots** tab, look underneath **Authorization Flow** and locate **REQUIRES OAUTH2 CODE GRANT**.
4. Disable **OAUTH2 CODE GRANT**.&#x20;
5. Retry inviting your Discord bot.

<div data-full-width="false">

<figure><img src="../../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

</div>

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Unable to Create In-App Authorization

1. Go back to the `Bot` section on the [<mark style="color:purple;">Discord Developer Portal</mark> ](https://discord.com/developers/applications)> make sure that the `PUBLIC BOT` option is enabled

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-01 at 9.38.16 PM.png" alt=""><figcaption></figcaption></figure>

### Missing In-App Authorization Method

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

if you can’t find the “In-App Authorization” option, go back to the `Bot` section and make sure that `REQUIRES OAUTH2 CODE GRANT` option is disabled

\
![](<../../.gitbook/assets/Screenshot 2023-12-01 at 9.40.54 PM.png>)
