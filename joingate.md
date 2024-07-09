
# JoinGate

**What is joingate?**  
Automod is a module created to prevent any spam or phishing attempts. It detects curse words/links/discord invites/mass mentions in chat and deletes the message. It also temporarily mutes the user to prevent further such attempts.

> Administrators/Users with higher role/Users with the automod bypass role will not be affected by the automod. Read further to learn how to set a bypass role.

## Basic
If you've already used the command `/setup` then joingate is probably already enabled.

## Filters
JoinGate will filter users with these properties. They can be enabled/disabled individually.
 * No Avatar
 * New Accounts
 * Advertising Names

## Commands (4)

### joingate enable
Enables automod.  
Required permission: Ownership  
Usage: `/joingate enable`

### joingate disable
Disables joingate.  
Required permission: Ownership  
Usage: `/joingate disable`

### joingate toggle
Enable/Disable specific event.  
Required permission: Ownership  
Usage: `/joingate toggle <status> <event>`

### joingate acc_age 
Set the minimum account age.  
Required permission: Ownership  
Usage: `/joingate acc_age <age>`