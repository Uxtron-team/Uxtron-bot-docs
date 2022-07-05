# Moderation features & commands
It's never a good sign if someone starts disrespecting and spamming your server with bad comments. To deal with this problem, your server moderatiors will likely have to keep applying moderation actions to prevent this. Now, imagine if this happens daily. The staff members of your server would soon be tired from having to mute, ban and kick users every day. What if there was a way to stop this? Well, the Uxtron moderation features are there to help keep your server a safe place for your members to hang out!

## How to start
To start using these features, you have to first enable them. Some features are enabled by default but some, you have to manualy configure yourself. This can be achieved with the dashboard, or with `/cmdconfig` ([learn more](https://github.com/Uxtron-team/Uxtron-bot-docs/blob/main/docs/features_usage/setting_up.md#setting-up-these-featurescommands)). After setting up the features, they should work no problem. With commands however, saving your changes might take a while (a few seconds to 1min).

***

# Advanced section

## Basic user management 

###### General basic user management command structure (This is the general structure. Not the DEFINITE structure for all commands)
```
Command + [arguments]         <-- BOT COMMAND
├── Do action specified
|
V   
└── !ERROR!                   <-- ***No current known errors. CONTACT SUPPORT If an error occurs***
```

## Basic server management 

###### General basic server management command structure (This is the general structure. Not the DEFINITE structure for all commands)

> The command structure below is WIP (Work In Progress)

```
Command + [arguments]                         <-- BOT COMMAND
├── Confirmation message                      <-- Confirmation menu
|    ├── ## Await user input ##               
|    | 
|    ├── CONFIRM: Do action specified      
|    |
|    ├── CANCEL: Cancel action
|    |
|    └── User doesn't reply: Cancel action
|
V   
└── !ERROR!                   <-- ***No current known errors. CONTACT SUPPORT If an error occurs***
```
