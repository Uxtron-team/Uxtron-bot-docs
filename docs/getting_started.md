# Getting started
###### Uxtron is a powerful multipurpose discord bot that provides countless features to aid you in the creation in your discord server as well as enhancing the experience for everyone.
## 1) Adding Uxtron
To add Uxtron to your server, click [here](https://discord.com/api/oauth2/authorize?client_id=882000000000000000&permissions=8&scope=bot%20applications.commands) and select the server you want to add Uxtron to. If you are not the server owner, you will need the `Manage Server` permission to add Uxtron to the server. You can also try Uxtron Premium for free with our free trial that lasts for 2 weeks (14 days). To try Uxtron Premium, click [here](https://discord.com/api/oauth2/authorize?client_id=882000000000000000&permissions=8&scope=bot%20applications.commands&guild_id=882000000000000000&disable_guild_select=true).
## 2) Setting up Uxtron
To set up Uxtron, you can run the `/activate` command. This will start the setup process. You can also run the `/activate` command to verify all settings and fix any incorrect or corrupt settings, roles and permissions. Please note that the `Adminstrator` permission will be required when activating Uxtron. To automatically setup Uxtron based on your desired settings and preferences, you can run type in the following:
```text
ux> activate --auto 
```
This will ask you a few questions to make sure that what it sets up is what you desire.
## 3) Setting up Uxtron's permissions
After you have added Uxtron to your server, you will need to make sure that Uxtron's permissions are all correct. By default, inviting Uxtron to your server will grant Uxtron the `Adminstrator` permission in your server. If you do not wish for Uxtron to have the `Adminstrator` permission, you can change Uxtron's permissions by following the steps below:
1. Go to your server's settings.
2. Go to the `Roles` tab.
3. Find the role named `Uxtron` and click on it.
4. Click on the `Permissions` tab.
5. Make sure that the `Administrator` permission is **not** checked.
6. Add your own permissions you would like Uxtron to have. **Note that you must give it the following permissions for it to function properly:**
   - `Send Messages`
   - `Send Messages In Threads`
   - `Add Reactions`
   - `Use External Emojis`
   
Note that the permissions listed above are just basic permissions to make sure that the general features work. Some commands will require more permissions. For example, the `/purge` command will require the `Manage Messages` permission to function.

> **Note**
> By revoking the `Adminstrator` permission, you will need to manually add the permissions required to allow commands to work properly. It is therefore advised that you keep the `Adminstrator` permission.

## 4) WIP