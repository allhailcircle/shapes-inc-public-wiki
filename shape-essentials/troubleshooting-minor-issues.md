# Troubleshooting minor issues

## **My shape's slash commands are gone. How to fix that?**

If you encounter the problem of slash commands not showing up, try the following troubleshooting steps:

1. **Restart Discord Client or Refresh the Website:**
   * Restart your Discord client or refresh the website. In most cases, this action resolves the issue as it may be due to a caching problem from Discord.
2.  **Disable and Enable Your Shape:**

    * On the Shapes.inc page for your shape, navigate to Settings => Danger Zone.
    * Toggle off "Enable Shape" and save the changes. Then, toggle it back on.
    * This will effectively restart the shape and force-load all slash command cogs.



    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 104752.png" alt=""><figcaption><p>Disable shape</p></figcaption></figure>

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 104808.png" alt=""><figcaption><p>Enable shape</p></figcaption></figure>
3.  **Check Discord Developer Portal:**

    * Go to the Discord Developer Portal.
    * Navigate to the dashboard and locate the bot application for your shape.
    * Under General Information, scroll down to "INTERACTIONS ENDPOINT URL."
    * Ensure that this field is not set. If it's set, Discord won't forward interaction webhooks, and your shape won't recognize them.

    <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 104518.png" alt=""><figcaption><p>make sure interaction endpoint url is empty</p></figcaption></figure>

By following these steps, you should be able to resolve the issue of missing slash commands.

## **My shape doesn't talk to me. How to fix that?**

If your shape is not responding or seems unresponsive, you can try the following solution:

1. **Disable and Enable Your Shape:**
   * On the Shapes.inc page for your shape, navigate to Settings => Danger Zone.
   * Toggle off "Enable Shape" and save the changes.
   * Toggle it back on and save again. _<mark style="color:blue;">(screenshots attached above ^)</mark>_

By disabling and enabling your shape, you essentially trigger a restart, forcing the shape to behave correctly. This action can resolve issues related to the shape not responding.

## **I want my shape to show my external slash commands. How to achieve that?**

If you've added external slash commands and want your shape to recognize and display them, follow these steps:

1. **Disable Shape Slash Commands:**
   * Go to the Shapes.inc page for your shape.
   * Navigate to Settings => Disable Shape Slash Command.
   * Save the changes.
   *

       <figure><img src="../.gitbook/assets/Screenshot 2024-02-15 105051 (1).png" alt=""><figcaption><p>Disable slash commands</p></figcaption></figure>
2. **Restart Your External Code Instance:**
   * After disabling shape slash commands, restart your external code instance that handles the custom slash commands.

Now your shape will recognize those externally programmed slash commands.
