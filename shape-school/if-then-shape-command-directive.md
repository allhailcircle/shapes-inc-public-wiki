---
description: How to create a Shape that has !commands or does special things when asked.
---

# ! If-Then Shape Command/Directive



{% embed url="https://youtu.be/Ocar65ltyOQ?si=6TZWJjqPYcvMdVwk" %}

{% content-ref url="../shape-essentials/your-first-shape/getting-a-discord-bot-token.md" %}
[getting-a-discord-bot-token.md](../shape-essentials/your-first-shape/getting-a-discord-bot-token.md)
{% endcontent-ref %}

{% hint style="info" %}
Please press the tabs below to reveal the text you need and then press the copy button!
{% endhint %}

<details>

<summary>!response style</summary>

{% code overflow="wrap" %}
```
If {user} says !rpON {shape} writes all subsequent responses and includes *roleplay actions*. If {user} says !rpOFF then {shape} stops *roleplay actions* and is forbidden from using them in all subsequent responses.
```
{% endcode %}

</details>

<details>

<summary>!link or !command</summary>

{% code overflow="wrap" %}
```
If {user} says !link or send me an invite link then {shape} replies with this server link. https://discord.com/invite/shapes
```
{% endcode %}

</details>

<details>

<summary>Send me a picture or link</summary>

{% code overflow="wrap" %}
```
If {user} says something about sending a picture of {shape} or what do you look like or show me a picture, then {shape} replies with one of the following image links of herself.

[Smiling](https://media.discordapp.net/attachments/1275434480999469127/1280305256202506353/69145-1532336916.jpg?ex=66d798b0&is=66d64730&hm=450ccdf256be8a9d9bf5f00b5523b801811d98c8ac6e7d2aa9ed2d8548b80eb1&)

or

[Blush](https://media.discordapp.net/attachments/1275434480999469127/1280305256777121863/Lenalee_nueva_apariencia.png?ex=66d798b0&is=66d64730&hm=98cff70219879aacfdfb2354728e57660fdbdd9816a5a7a62ff2f8dbc3ecb717&]

or

[Cute](https://media.discordapp.net/attachments/1275434480999469127/1280305257343226007/Lenalee_Lee_Hallow.png?ex=66d798b0&is=66d64730&hm=ab472b1ecc48d137a6e75b5abad6a6ae488cea689f4ddf0f2fc028a6499c67ca&)

{shape} Is only allowed to respond with those exact links verbatim and is forbidden from creating other links, {shape} must always follow that exact format. 
```
{% endcode %}

</details>

{% hint style="info" %}
You can have your Shape do just about anything you can think of using the "If {user} says this then {shape} responds with" directive.&#x20;



If you're encountering any issues you can try changing the AI MODEL on the AI ENGINE PAGE to 4o & also adding these prompts you've written in the PRESET field on that page.&#x20;



Don't forget to provide a few examples of what you expect on the TRAINING PAGE so the Shape can see what its suppose to do in action!
{% endhint %}

