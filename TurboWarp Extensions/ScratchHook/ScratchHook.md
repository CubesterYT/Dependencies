# ScratchHook Documentation
ScratchHook has three types of blocks:
 - **[Webhook | Command Block]** webhook data: (BOOLEAN) webhook url: (STRING)
    - The Boolean area is where you insert the data boolean and/or connector boolean.
 - **[Data | Boolean Block]** (MENU) (STRING)
    - The Menu area currently has three options, ("content","name","icon").
        - When choosing "content", you will type in the text you want to send to the string part of the boolean.
        - When choosing "name", you will type in the name of the webhook you want to set to the string part of the boolean.
        - When choosing "icon", you will type in the link to the image you want to set as the profile picture of the webhook.
    - ## **NOTE: "name" AND "icon" ARE NOT NECESSARY TO BE SENT, YOU NEED TO AT LEAST HAVE "content" AS A DATA SET!**
 - **[Connector | Boolean Block]** (BOOLEAN1) , (BOOLEAN2)
    - This Boolean connects two *different* Data Booleans together or another connector boolean so you can send multiple pieces of data to the webhook.
