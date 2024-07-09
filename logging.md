
# Logging

**Why logging?**  
Logging is useful when you don't want to check the cluttered audit logs everytime. We have all the important features covered in our logging module. 

> It only logs the actions of non whitelisted users. Hence, Anti-Nuke must be enabled for logging to work.

## Basic
If you've already used the command `/setup` then logging is probably already enabled. 

## Logged Events
  
 * Ban
 * Kick
 * Unban
 * Bot Add
 * Guild Update
 * Role Create 
 * Role Update
 * Role Delete
 * Channel Create
 * Channel Update
 * Channel Delete

## Commands (3)

### logging enable
Enables logging.  
Required permission: Ownership  
Usage: `/logging enable <#channel>`

### logging disable
Disables logging.  
Required permission: Ownership  
Usage: `/logging disable`

### logging set
Set a log channel.  
Required permission: Ownership  
Usage: `/logging set <#channel>`  

