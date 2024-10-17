# Client id = Value "" isn't snowflake?

## **I'm encountering a "client id isn't snowflake" error when adding a shape, how can I fix this?**

If you're seeing the "client id isn't snowflake" error due to a problem with the invite link, follow these steps to address it:



1. **Go to Discord Developer Portal:** Visit the [Discord Developer Portal](https://discord.com/developers/applications).
2. **Copy Application ID:** From the general settings of your Bot Application, copy the APPLICATION ID.

<figure><img src="../../.gitbook/assets/Screenshot 2024-01-16 160329.png" alt=""><figcaption></figcaption></figure>

1.  **Edit the Invite Link:** Go back to where you are adding the bot and replace any missing or incorrect application id in the invite link with the one you just copied.

    **Errored Link Example:**

    ```
    https://discord.com/oauth2/authorize?client_id=&scope=bot&permissions=
    ```

    **Corrected Link Example:**

    ```
    https://discord.com/oauth2/authorize?client_id=1140495514752790579&scope=bot&permissions=0
    ```
2. **Invite Shape:** After correcting the invite link, click on it to invite Shape to your server.

This adjustment should resolve the "client id isn't snowflake" error. If you have any more questions, feel free to open a post in [#shape-help channel](https://discord.com/channels/781212328749301790/1185774428546682881) on our [discord server](https://discord.com/invite/shapes).
