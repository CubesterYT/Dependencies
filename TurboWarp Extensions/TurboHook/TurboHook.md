# TurboHook Documentation

TurboHook is a fully Modular Webhook extension that you can be easily implemented into your projects. TurboHook is able to contact the Webhook of any site that supports basic Webhook Syntax. As of right now, the current KNOWN sites that can properly use TurboHook are Discord and Guilded. If there are more, join the TurboWarp discord server and DM me from there.

TurboHook has three types of blocks:
 - **[Webhook | Command Block]** webhook data: (NULLED STRING) webhook url: (STRING)
    - The Nulled String area is where you insert the data reporter and/or connector reporter.
 - **[Data | Reporter Block]** (MENU) (STRING)
    - The Menu area currently has three options, ("content","name","icon").
        - When choosing "content", you will type in the text you want to send to the string part of the reporter.
        - When choosing "name", you will type in the name of the webhook you want to set to the string part of the reporter.
        - When choosing "icon", you will type in the link to the image you want to set as the profile picture of the webhook to the string part of the reporter.
    - ## **NOTE: "name" AND "icon" ARE NOT NECESSARY TO BE SENT, YOU NEED TO AT LEAST HAVE "content" AS A DATA SET!**
 - **[Connector | Reporter Block]** (NULLED STRING1) , (NULLED STRING2)
    - This Boolean connects two *different* Data Reporters together or another Connector Reporter so you can send multiple pieces of data to the webhook. **Note: You can only have one of each option from the menu, such as: | content, name, icon | in any variation but not: | content, icon, name, name, content | as there can be one of each option.**


# TurboHook future Additions
 - TurboHook currently supports normal webhook messages, but will soon support fully modular embeds as well.
 - TurboHook might soon add a rate limited proxy link to parse the specified Webhook URL as there is a big possibility of this Extension being abused and used to potentially, either intentionally or unintentionally, DDOS the servers of the Webhook provider, causing problems and ip blocking. So TurboHook may soon have a Webhook Proxy to rate limit requests for security.