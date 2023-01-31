# Configurations
![](/static/configBannerApollo.png)
!!!warning Apollo will not work unless configured.
You need to configure Apollo inorder for triggers, win-messages & claimtime to work.</br>
All settings for the guild can be managed by the **`a!config`** command.
!!!
  
 
## Quick setup
Use the **`a!quicksetup`** command to setup Apollo in your server within a few seconds.
- Adds GiveawayBot triggers like `g!end`, `g!reroll` and etc.
- Sets a default win message.
- Add claim time of 10 seconds to the [!badge variant="primary" text="@everyone"] role.

!!!info Setting up triggers for Apollo is not necessary.
Apollo wil respond to its giveaway messages by default, adding triggers for Apollo does nothing different.
!!!
 
## Customization

### Win Message
Win message enables Apollo to send a winner announcement message when the giveaway is ended or rerolled. To learn more, [click here](/guides/win-message.md)
![This is how a win message looks like.](/static/exampleWinMessage.png)

### Triggers
Triggers allow the win message to be executed when certain commands like `g!reroll` is used. Configure it via the `a!config` command.
![This is how triggers look like.](/static/exampleTriggersConfig.png)

### Claimtime
Claimtime allows you to set a claim time for the role which can be used through win messages. To learn more, [click here](/guides/claimtime.md)

||| To setup claimtime
`a!claimtime add <role> <input_time> [override=None]`
||| To remove claimtime
`a!claimtime remove <role>`
|||

!!!info Override settings
If override is enabled and the claim time for the role is 10 seconds, then everyone with the role will get ONLY 10 seconds to claim. </br>
If override is disabled, Apollo will add 10 seconds to other claim times to get the total claim time.
!!!

[!ref text="Join Apollo HQ, the support server for Apollo Bot." icon="rocket" target='blank'](https://discord.gg/gBpXtvUjhv)