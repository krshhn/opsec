
# AntiRaid

**What is antiraid?**  
Antiraid is a module created to prevent any raid attempts. When the server is raided (multiple accounts join the server in a short time span), the antiraid module kicks them and enables [raidmode]() for the next few minutes.  
> The kicked users will receive a message telling them why they were kicked.

## Basic
If you've already used the command `/setup` then antiraid is probably already enabled. You can check that by running the command `/antiraid config`.  

## Basic Terminology
### Threshold
It is the maximum join limit in the set time duration.  
Default Value: 10 (Recommended)

### Window
It is the time duration for the joins.  
Default Value: 15 seconds (Recommended)

### Explaination
**According to the values set above:**  
When there are 10 joins in 15 seconds, it will be considered a raid. 

## Commands (4)

### antiraid enable
Enables antiraid.   
Required permission: Ownership  
Usage: `/antiraid enable`

### antiraid disable
Disables antiraid.  
Required permission: Ownership  
Usage: `/antiraid disable`

### antiraid threshold
Sets the join threshold.  
Default Value: 10
Range of Value: 5 to 25
Required permission: Ownership  
Usage: `/antiraid threshold <integer>`  
**Examples:**
`/antiraid threshold 15`

### antiraid window
Sets the join window duration.  
Default Value: 30 seconds.  
Range of Value: 5 to 300 seconds.  
Required permission: Ownership  
Usage: `/antiraid duration <seconds>`  
**Examples:**
`/antiraid duration 60`


