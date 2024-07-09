
# AutoMod

**What is automod?**  
Automod is a module created to prevent any spam or phishing attempts. It detects curse words/links/discord invites/mass mentions in chat and deletes the message. It also temporarily mutes the user to prevent further such attempts.

> Administrators/Users with higher role/Users with the automod bypass role will not be affected by the automod. Read further to learn how to set a bypass role.

## Basic
If you've already used the command `/setup` then automod is probably already enabled.

## Events
By default, all of these events are enabled. They can be enabled/disabled individually.
 * Anti Mass Mentions
 * Anti Links
 * Anti Invites

## Why not anti-spam?
Anti-Spam is a feature that just slows down the bot if used in multiple servers. As an antinuke bot, it needs to stay as fast as possible. Our **AutoMod + JoinGate + AntiRaid** combination already makes sure that there are no spam attempts.
> If you want the anti-spam feature, you should consider buying our [custom bot](). It has multiple other features to keep your server safe.

## Commands (5)

### automod enable
Enables automod.  
Required permission: Ownership  
Usage: `/automod enable`

### automod disable
Disables automod.  
Required permission: Ownership  
Usage: `/automod disable`

### automod bypass
Sets a role as automod bypass. Users with this role will not be affected by automod.  
Required permission: Ownership  
Usage: `/automod bypass <role>`  

### automod max_mentions
Sets the maximum mention limit in a message.  
Default Value: 5  
Minimum Value:5   
Required permission: Ownership  
Usage: `/automod max_mentions <integer>`  
**Examples:**
`/automod max_mentions 10`

### automod duration
Sets the timeout duration.  
Default Value: 30 minutes  
Range of Value: 5 to 1440 minutes
Required permission: Ownership  
Usage: `/automod duration <minutes>`  
**Examples:**
`/automod duration 15`

