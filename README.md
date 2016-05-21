BlackPlus > GitHub | Site | Channel
*New Bot For Manage Your SuperGroups.

*A Advanced Bot Based In Teleseed (Normal Groups)

BlackPlus Uses "Anticrash" & "Autolaunch" To Be Active All The Time
آموزش نصب سروس
کد زیر را در ترمینال وارد کنید.
sudo apt-get update; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev autoconf -y --force-yes && git clone https://github.com/mehdi-hs/BlackPlus.git && cd BlackPlus && chmod +x launch.sh && ./launch.sh install && ./launch.sh

2.بعد از چند دقیقه ربات از شما شماره ای میگیره که روبات روی اون نصب شه... بعد از وارد کردن شماره و وارد کردن کد در صورتی ربات در اکانت مورد نظر نصب شد ترمینال را ببندید و ترمینال جدید باز کنید سپس دستور زیر را بزنید...

cd BlackPlus

دقت کنید که در دستور بالا حرف سی و پی رو کپتال بنویسید که اررور نده بعد این کد رو بزنید

tmux new-session -s script "bash blackplus.sh -t"

(از آنتی کرش در سرور های مجانی نمیتوانید استفاده کنید)
بعد از چند ثانیه ربات ران میشه

قسمت دوم این آموزش برای فعال کردن آنتی کرش هست و از این به بعد اگر ربات آف شد مرحله 2 رو انجام دهید
برای سودو کردن خودتون هم در پوشه دیتا فیل کافیگ رو ادیت کنید و در قسمت سودو یوزر ایدی عددی خودتون رو بنویسید

هر هفته میتوانید با دستور های زیر جدید ترین پلاگین ها و آپدیت هارو دریافت کنید.

اول در ترمینال دستور زیر را تایپ کنید

cd BlackPlus

سپس این دستور را وارد کنید.

git pull

Features
A powerful antispam system with custom sensitivity for each group
Multiple realms (admin groups)
Recalcitrant to any kind of spamming (X/Y bots, name/photo changers, etc.)
Global banning
Broadcast to all groups
Group and links
Kick, ban and unban by reply
Groups, ban and global ban list
Logging anything that happens in a group
Invitation by username
Group administration via private messages
Only mods, owner and admin can add bots in groups
Arabic lock
Lock TGService
Lock Link
Lock Flood/Spam
Lock Persian
Lock Member
Lock Sticker
Lock Contacts
Public On|Off
Mute Audio
Mute Photo
Mute All
Mute Video
Mute Gifs
Mute Dacuments
Mute Text
Tagall
AntiCrash
AutoLaunch
Qr Code Maker
Kick By Reply
Sticker To Image
Image To Sticker
Text to voice (# Debuged)
Advanced ID Plugin
Set PassWord For SuperGroups/Groups
Show Your Uptime Bot
Intagram Plugin
Aparat Plugin
Text To Sticker Plugin
Send Group request
inv bot sudo in SuperGroups
Chat list
And more!
Commands

BlackPlus has several commands that are only usable at certain ranks.

General Commands {#general_commands}

Command	Description
[#!/]id	Returns group/SuperGroup ID & more or user id in pm.
[#!/]black	Returns bot information.
Private Message Commands {#privmsg_commands}

Command	Description
[#!/]help	Returns help text.
[#!/]superhelp	Returns SuperGroup help text.
[#!/]chats	Returns public chats in a message(s).
[#!/]chatlist	Returns public chats in a .txt document.
[#!/]join [GroupID]	Join a public chat by id
Moderator commands {#moderator_commands}

Command	Description	Groups?	SuperGroups?
[#!/]info	Returns general info about the SuperGroup.	N	Y
[#!/]admins	Returns SuperGroup admins list.	N	Y
[#!/]modlist	Returns Moderator list.	Y	Y
[#!/]owner	Returns group/SuperGroup owner. Can be used by any user	Y	Y
[#!/]bots	Lists bots in SuperGroup.	N	Y
[#!/]who	Lists all users in group *SuperGroup returns .txt document list.	Y	Y
[#!/]wholist	Lists all users in group in .txt document.	Y	N
[#!/]block	Kicks a user from SuperGroup Adds user to blocked list.	N	Y
[#!/]kick	kicks user from group.	Y	N
[#!/]ban	Bans user from the group/SuperGroup.	Y	Y
[#!/]unban	Unbans user from group/SuperGroup.	Y	Y
[#!/]id [username|reply]	For userID's: !id @username (ONLY IN SuperSroups) or reply !id in any group.	Y	Y
[#!/]id from	Returns ID of user a message is forwarded from.	N	Y
[#!/]kickme	Kicks user from SuperGroup / In SuperGroup: Must be unblocked by owner or use #join by pm to return	Y	Y
[#!/]setowner	Sets group/SuperGroup owner.	Y	Y
[#!/]promote	Promote a group/SuperGroup moderator.	Y	Y
[#!/]demote	Demote a group/SuperGroup moderator.	Y	Y
[#!/]setname	Set group/SuperGroup name.	Y	Y
[#!/]setphoto	Set group/SuperGroup photo.	Y	Y
[#!/]setrules	Set group/SuperGroup rules.	Y	Y
[#!/]setabout	Sets the about section in chat info(members list)	N	Y
[#!/]set about		Y	N
[#!/]save [value]	Sets extra info for group/SuperGroup by value.	Y	Y
[#!/]get [value]	Returns extra info for group/SuperGroup by value.	Y	Y
[#!/]newlink	Generate a new group/SuperGroup link.	Y	Y
[#!/]setlink	Set a new SuperGroup link If bot is not creator.	N	Y
[#!/]link	Retrieves the group/SuperGroup link.	Y	Y
[#!/]rules	Retrieves the group/SuperGroup rules.	Y	Y
[#!/]lock setting	Lock group/SuperGroup settings.	Y	Y
[#!/]unlock setting	Unlock group/SuperGroup.	Y	Y
[#!/]mute mute	mute group message types.	Y	Y
[#!/]unmute mute	unmute group message types.	Y	Y
[#!/]setflood value	Set [value] as flood sensitivity.	Y	Y
[#!/]muteuser [username|id|reply]	Mute and unmute a user in chat. If a muted user posts a message, the message is deleted automaically only owners can mute | mods and owners can unmute	Y	Y
[#!/]mutelist	Returns list of muted users in group/SuperGroup.	Y	Y
[#!/]muteslist	Returns mutes for group/SuperGroup.	Y	Y
[#!/]settings	Returns a list of group/SuperGroup settings.	Y	Y
[#!/]stats	Returns simple message statistics in a .txt document.	Y	Y
[#!/]statslist	Returns simple message statistics in a message.	Y	Y
[#!/]banlist	Returns group/SuperGroup banlist.	Y	Y
[#!/]clean [rules|about|modlist|mutelist]	Clears rules, about, modlist, or mutelist	Y	Y
[#!/]del	Deletes a message by reply.	N	Y
[#!/]tosticker	Conv Photo To sticker	Y	Y
[#!/]tophoto	Conv sticker To photo	Y	Y
[#!/]vc	Conv text To voice	Y	Y
[#!/]qr [your text	link...]		Y
[#!/]tosticker	Conv Photo To sticker	Y	Y
[#!/]aparat [text]	Search your text in aparat	Y	Y
[#!/]tosticker	Conv Photo To sticker	Y	Y
[#!/]webshot [url]		Y	Y
[#!/]version	show bot version	Y	Y
[#!/]reqgp	send Request to admin for create group	Y	Y
[#!/]black	show bot info	Y	Y
[#!/]res [username]	Returns users name and id by username.	Y	Y
[#!/]log	Returns group logs.In SuperGroups: Search for kick reasons using [#RTL|#spam|#lockmember]	Y	Y
Owner commands {#moderator_commands}

Command	Description	groups/SuperGroups?	In private?
[#!/]muteuser [username|id|reply]	Mute and unmute a user in chat.If a muted user posts a message, the message is deleted automaically / only owners can mute / mods and owners can unmute		N
[#!/]owners [GroupID] [kick|ban|unban] [UserID]	Kick, ban, or unban a user from a group by GroupID and UserID.	N	Y
[#!/]owners [GroupID] clean [modlist|rules|about]	Clear options by GroupID.	N	Y
[#!/]owners [GroupID] setflood [value]	Set flood for a group by GroupID and a value [1-5].	N	Y
[#!/]owners [GroupID] lock [setting]	Lock settings for a group by GroupID.	N	Y
[#!/]owner [GroupID] unlock [setting]	Unlock settings for a group by GroupID.	N	Y
[#!/]owners [GroupID] new link	Create a new group link by GroupID.	N	Y
[#!/]owners [GroupID] get link	Returns group link by GroupID.	N	Y
[#!/]changename [GroupID] [name]	Change a group's name by GroupID.	N	Y
[#!/]changrules [GroupID] [rules]	Change a group's rules by GroupID.	N	Y
[#!/]changeabout [GroupID] [about]	Change a group's about by GroupID.	N	Y
[#!/]loggroup [GroupID]	get group logs by GroupID.	N	Y
Admin commands

Command	Description	Groups?	SuperGroups?	Realms?
[#!/]cgp [Name]	Create a group and add it to moderation.json.	Y	Y	Y
[#!/]createrealm [Name]	Create a realm and remove it from moderation.json.	Y	Y	Y
[#!/]add	Add a group to moderation.json.	Y	Y	Y
[#!/]rem	Remove a group from moderation.json.	Y	Y	Y
[#!/]rem [GroupID]	Remove a group from moderation by GroupID.	Y	Y	Y
[#!/]setname [Name]	Set realm name.	N	--	Y
[#!/]setabout [group|sgroup] [GroupID] [Text]	Set a group's about text.	Y	Y	Y
[#!/]setrules [group|sgroup] [GroupID] [Text]	Set a group's rules.	Y	Y	Y
[#!/]lock [GroupID] [setting]	Lock a group's setting.	Y	Y	Y
[#!/]lock [GroupID] [setting]	Lock a group's setting.	Y	Y	Y
[#!/]unlock [GroupID] [setting]	Unlock a group's setting.	Y	Y	Y
[#!/]who	Get a list of members in group/realm.	Y	Y	Y
[#!/]wholist	Get a .txt document list of members in group/realm.	Y	Y	Y
[#!/]type	Get group type.	Y	Y	Y
[#!/]addlog	Add a Log_SuperGroup for GBan log.	N	Y	N
[#!/]remlog	Remove a Log_SuperGroup for GBan log.	N	Y	N
[#!/]kill chat [GroupID]	Kick all users and remove a group from moderation.	Y	Y	Y
[#!/]kill realm [RealmID]	Kick all users and remove a realm from moderation.	Y	Y	Y
[#!/]banall [id|usename]	Ban a user from all moderated groups where bot is an admin (#global_ban)	Y	Y	Y
[#!/]unbanall [id|usename]	Unban a user from all moderated groups where bot is an admin (#global_ban)	Y	Y	Y
[#!/]gbanlist [id|usename]	Returns a list of all globally banned user	Y	Y	Y
[#!/]list groups	Returns a list of all groups.	Y	Y	Y
[#!/]list realms	Returns a list of all realms.	Y	Y	Y
[#!/]whitelist	User/Bot will not be subject to message checks.	Y	Y	Y
[#!/]support	Promote user to support.	Y	Y	Y
[#!/]-support	deomote user from support.	Y	Y	Y
[#!/]pm [UserID]	Sends a private message to a user by UserID.	Y	Y	Y
[#!/]import	Bot joins a group by GroupLink.	Y	Y	Y
[#!/]markread [on|off]	Toggle bot to doubble check or not doubble check messages.	Y	Y	Y
[#!/]contactlist	Bot will generate a list of all it's contacts***and send it by private message of command sender	Y	Y	Y
[#!/]dialoglist	Bot will generate a list of all it's private message users***and send it by private message of command sender	Y	Y	Y
[#!/]delcontact	Delete bot contact.	Y	Y	Y
[#!/]reload	Reloads all bot plugins	Y	Y	Y
[#!/]!bc [GroupID] [text]	This command will send text to [GroupID]	Y	Y	Y
[#!/]leave	Bot will leave that group and can only be re-invited by an admin with bot phone number	Y	Y	Y
[#!/]mp	(Mod Promote) Set user as a mod of supergroup. TESTING	N	Y	N
[#!/]md	(Mod demote) Removes user from mod of supergroup. TESTING	N	Y	N
Sudo Commands {#sudo_commands}

Command	Groups?	SuperGroups?	Realms?
[#!/]addadmin [id|username]	Set a user as bot admin.	Y	Y
[#!/]removeadmin [id|username]	Remove a user from bot admin.	Y	Y
Settings {#settings}

Command	Groups?	SuperGroups?
[#!/](un)lock links	Y	Y
[#!/](un)lock flood	Y	Y
[#!/]setflood [5-20]	Y	Y
[#!/](un)lock bots	Y	N
[#!/](un)lock spam	Y	Y
[#!/](un)lock arabic	Y	Y
[#!/](un)lock member	Y	Y
[#!/](un)lock leave	Y	N
[#!/](un)lock RTL	Y	Y
[#!/](un)lock tgservice	N	Y
[#!/](un)lock sticker	Y	Y
[#!/]public [yes|no]	Y	Y
[#!/](un)lock strict	N	Y
/lock [setting] and /unlock [setting]: sets allowed actions and content for groups/SuperGroups /lock strict in a supergroup, if strict is locked users will be kicked for violations of settings or mutes

/public [yes|no]: Set group/SuperGroup visibility in pm !chats or !chatlist commands.

Mutes {#mutes}

Command
[#!/]mute audio
[#!/]mute video
[#!/]mute photo
[#!/]mute documents
[#!/]mute gifs
[#!/]mute all
Groups: If "muted" message type: user is kicked if message type is posted

*SuperGroups: A "muted" message type is auto-deleted if posted *

Ranks {#ranks}

Rank	Description
Banned	Cannot enter the group(s).
User	Default rank.
Moderator	Can set settings and kick/ban/unban users from a group. Can unmute users.
Owner	Can mute users. Can promote/demote moderators. Can set SuperGroup admins.
Support	Can globally unban users. Acts as owner of all groups.
Administrator	Can globally ban/unban users. Can promote/demote owners.
Sudo	Can add[#!/]remove groups. Can broadcast. Can promote/demote administrators.
Each higher status inherits the privileges of the lower status.

**You can use "#", "!", or "/" to begin all commands

Installation
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev


# Let's install the bot.
cd $HOME
git clone https://github.com/mehdi-hs/BlackPlus.git
cd BlackPlus
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
One command

To install everything in one command (useful for VPS deployment) on Debian-based distros, use:

#https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get update; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev autoconf -y --force-yes && git clone https://github.com/mehdi-hs/BlackPlus.git && cd BlackPlus && chmod +x launch.sh && ./launch.sh install && ./launch.sh
Realm configuration

After you run the bot for first time, send it !id. Get your ID and stop the bot.

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:

  sudo_users = {
Your ID
  }
Then restart the bot.

Create a realm using the !createrealm command.

Creating a LOG SuperGroup -For GBan Log

1. Create a group using the `!cgp` command.
2. Add two members or bots, then use `#Upchat` to convert to a SuperSroup.
3. Use the `#addlog` command and your ***LOG SuperGroup(s)*** will be set.
Note: you can set multiple Log SuperGroups
Our team!

[Forwarded from Xx.🔜🏰 ™υЛłٍٍǪٍٍuΞٍٍ™ 🏰🔙.xX]
👤 ❗️ʍψ βø†❗️👤

⭕️ @BazZiKONAM_HaCker 💡
⭕️ @HF_uniQueBOT 💡
⭕️ @KZL_APIBOT 💡
⭕️ @lOl_APIBOT 💡
⭕️ @uniQue_Lord_BOT_MOSBAT 💡
⭕️ @uniQue_Lord_BOT_API_BOT 💡

⭕️ ΛÐMłЛ БФT⚠️🔝  @BaZziKONAM_HaCker  »ODIN«
🔴 ʍψ βø† 🔴 @CHANNEL_BaZziKONAM_BOT ©®🔚🔴

https://telegram.me/BaZziKONAM/16
