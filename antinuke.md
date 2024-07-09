
# Antinuke

**How does the antinuke work?**  
If the bot detects any malicious action performed by any user, then as a safety measure the bot bans the user and reverts the action (if possible).

> Whitelisted Users or Users who have a role higher than the bot will not be affected by the antinuke.

## Basic
If you've already used the command `/setup` then antinuke is probably already enabled. You can check that by running the command `/antinuke config`.  
Make sure the bot has the highest role as it will require that to function properly.

## Whitelists
Whitelist is a list of users who are immune to the bot's antinuke measures. They won't be punished for doing any changes to the server and their actions won't be reverted.  
> You can add maximum 10 users to the whitelist.  

## Events
By default, all of these events are enabled. They can be enabled/disabled individually.  
 * Anti Ban
 * Anti Kick
 * Anti Unban
 * Anti Bot Add
 * Anti Guild Update
 * Anti Role Create 
 * Anti Role Update
 * Anti Role Delete
 * Anti Channel Create
 * Anti Channel Update
 * Anti Channel Delete

## Commands (8)

### antinuke enable
Enables antinuke.  
Required permission: Ownership  
Usage: `/antinuke enable`

### antinuke disable
Disables antinuke.  
Required permission: Ownership  
Usage: `/antinuke disable`

### antinuke toggle
Enables/Disables a specific event.  
Required permission: Ownership  
Usage: `/antinuke toggle <status> <event>`  
**Example:**  
* `/antinuke toggle enable ban`  
* `/antinuke toggle disable bot-add`

### antinuke config
Shows the server configuration for antinuke.  
Required permission: Ownership  
Usage: `/antinuke disable`

### antinuke whitelist add
Adds an user to the whitelist.  
> No need to add the users who have a higher role.  
Max Limit: 10

Required permission: Ownership  
Usage: `/antinuke whitelist add <@user>`  
**Example:**  
* `/antinuke whitelist add @krshhn`

### antinuke whitelist remove
Removes an user from the whitelist.  

Required permission: Ownership  
Usage: `/antinuke whitelist remove <@user>`  
**Example:**  
* `/antinuke whitelist remove @krshhn`

### antinuke whitelist show
Lists all the user in the whitelist.  

Required permission: Ownership  
Usage: `/antinuke whitelist show`  

### antinuke whitelist clear
Clears the whitelist.  

Required permission: Ownership  
Usage: `/antinuke whitelist clear`  
