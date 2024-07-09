
# RaidMode

**What is raidmode?**  
Raidmode is a module created to enable when your server has a potential threat to be raided. While it is enabled, any joining member will be kicked.  
It is automatically enabled for few minutes when a raid is detected by the [antiraid module](). You can set the auto duration.  
> The kicked users will recieve a message stating the reason why they were kicked. The message looks like this: 

## Commands (3)

### raidmode enable
Enables raidmode.    
Required permission: Ownership  
Usage: `/raidmode enable`
> ‼️ Enable it only when your server has a raid threat. Else it will affect your server's new members.


### raidmode disable
Disables raidmode.  
Required permission: Ownership  
Usage: `/raidmode disable`

### raidmode auto_duration
Sets the duration for which raidmode is enabled by the antiraid module.  
Default Value: 5 minutes (Recommended)  
Range of Value: 5 to 30 minutes.  
Required permission: Ownership  
Usage: `/raidmode duration <minutes>`  
**Examples:**
`/raidmode duration 15`


