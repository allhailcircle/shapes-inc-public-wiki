---
description: Welcome to the control center of your Shape—the AI Engine.
---

# AI Engine

## Preset

Choose a default language and engine preset for your Shape.

### Language Preset

Setting a language preset means the default language your Shape responds in will be that language. Your Shape will understand any language being spoken in but only respond in that specific language.

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-04 at 6.12.56 AM.png" alt=""><figcaption><p>The Language Preset is a drop-down that shows ~20 languages</p></figcaption></figure>

### Engine Preset

Engine presets heavily influence your shape's behavior. You can select multiple presets or create a custom preset.&#x20;

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-04 at 6.18.50 AM.png" alt=""><figcaption></figcaption></figure>

## Generation

Choose the engine you want to utilize for your shape. Some engines are censored, while others are not. Some engines can generate images, while others cannot.

### AI Model

There are 5 AI Engine Models you can use. `llama 3 instruct`, `3.5 instruct`, `4`, `8x22` and `3.5`. Learn more about their differences and capabilities on [this page](../frequently-asked-questions/models.md).

<figure><img src="../../.gitbook/assets/image (1) (1) (1).png" alt="" width="240"><figcaption></figcaption></figure>

### Image Generation

To be able to toggle on Image Generation, you need to switch your AI Model to Engine `3.5` or `4`. After enabling this feature, you can now ask your shape to generate images!

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1).png" alt="" width="255"><figcaption></figcaption></figure>

## Short-Term Memory (STM)

Set the number of recent messages your Shape will consider when replying to a message. Short-term memory can be used for keeping your Shape up-to-date in the conversation so they know what to reply to and what they've already said (to keep from repeating).



:factory:We recommend enabling Short-Term Memory for 10-15 messages.

<figure><img src="../../.gitbook/assets/Screenshot 2023-11-30 103331.png" alt=""><figcaption></figcaption></figure>

## Long-term Memory (LTM)

### Number of Memories

Decide the number of long-term memories your Shape should take into context when replying to a message. When a Shape is generating a reply, they will retrieving similar memories to the recent message -- so this feature lets you choose up-to how many memories can they reference! \
\
:factory: We recommend keeping `Number of Memories` at 1 so your Shape doesn't get confused from different memories.

:bulb:Disabling LTM can keep roleplays new (so the Shape doesn't start responding based previous roleplays)

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-04 at 6.44.44 AM.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can review your Shape's Memories and manage how memories are synced in [<mark style="color:purple;">Privacy</mark>](ai-engine.md#privacy)
{% endhint %}

### Memory Similarity Threshold

Memory Similarity Threshold dictates what long-term memories are retrieved for a Shape to reference when they are generating their reply.

> If the memory similarity threshold is lower, it's easier for items to be considered a match because they don't have to be very similar. It's like having a low bar for a match.

> If the threshold is higher, items need to be **very** similar to match. So it's like raising the bar—you're being pickier about what counts as similar.

:factory: We recommend setting your Memory Similarity Threshold at 0.8

<figure><img src="../../.gitbook/assets/image (2) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Frequency&#x20;

Shapes generate their own memories. You can view this on the memory tab of your shape

<figure><img src="../../.gitbook/assets/Screenshot 2023-12-04 at 7.02.41 AM.png" alt=""><figcaption></figcaption></figure>

### Privacy

Adjust the privacy settings to tailor how private your shape keeps conversations. Decide whether memory from DMs and servers should be isolated or shared to different extents.

#### Privacy Levels:

* **Low = Private:** Memories from DMs and servers are isolated from each other.
* **Medium = Shared:** Memory can be pulled from the same server and from DMs.

<figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

## Generation

Manage your shape's response generation in this section. Choose the model it runs on, adjust creativity with temperature, Top P, determine response length, and control the context window for a balanced conversation.

<figure><img src="../../.gitbook/assets/Screenshot 2024-03-22 120914.png" alt=""><figcaption></figcaption></figure>

## Knowledge

Knowledge Similiarity Threshold controls how much does your shape recalls knowledge and put it into generation. To make the shape remember knowledge better, we recommend you to put it on `0.3 - 0.5` and make sure to `/wack` command after updating the knowledge of your shape.

<figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

## Time

In this section, decide whether your shape should be aware of the current time with the timezone you selected.

<div data-full-width="true">

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-24 082122.png" alt=""><figcaption></figcaption></figure>

</div>

<div data-full-width="true">

<figure><img src="../../.gitbook/assets/Screenshot 2024-04-24 082051.png" alt=""><figcaption></figcaption></figure>

</div>

Remember to save your changes after configuring each section to ensure your shape reflects your desired settings. With this level of control, your shape is ready to adapt to your preferences seamlessly! 🔧🤖✨
