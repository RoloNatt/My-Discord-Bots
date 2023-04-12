# Tourney Mod

[Tourney Mod Blog](https://rolocodes.hashnode.dev/tourney-mod-discord-bot)

[Tourney Mod invite link](https://discord.com/api/oauth2/authorize?client_id=1032932441167495189&permissions=560963046480&scope=bot%20applications.commands)

[Tourney Mod youtube video on how it works](https://www.youtube.com/watch?v=aj_XIuwCRCU)

Tourney Mod automates all the processes that a Tournament organizer or mod does in a discord server.

This bot lets a player register a team, add players, edit team. The registered teams go to the tournament organizers/mods that they can Approve or Decline.
On team approval, the bot automatically creates the team VC and give roles to the team members - also sends a DM to the player.

As the tournament proceeds, the mods can eliminate the teams (by simply pressing a button) that have not qualified for the next round - this will delete all the roles from the eliminated team players' and also delete their team VC.

The mods can get all the teams' details any time in an excel sheet.

-----------------------------------------------------------------------

## Bot features

1. Organizers can host tournaments directly in their discord server.
2. Players can register their teams.

-----------------------------------------------------------------------

## Mod Commands

### **start_tourney**
Start Tournament Registrations. This command must be used in the beginning by the server admin. All other commands can be used after this.

--------------------------------------
### **end_tourney**
End the Tournament. An excel sheet is uploaded with all the data and the same is deleted from the database. (Dangerous Command)

--------------------------------------
### **freeze_registrations**
No new teams can be registered and no changes can be made to the teams.

--------------------------------------
### **resume_registrations**
New teams can register again and changes can be made to the teams.

--------------------------------------
### **team_count**
Get the count of Total Registered Teams, Approved Teams, Declined Teams, Pending Teams.

--------------------------------------
### **archive_data**
Get a downloadable excel sheet containing the data of all Registered Teams and Players.

--------------------------------------
## Player Commands

### **create_team**
Register a New Team. (1st player is set as the captain)

--------------------------------------
### **pass_captain**
Transfer Captaincy to Another Player. Only Captains/Mods can use this command.

--------------------------------------
### **add_players**
Add Players to your Team. Only Captains/Mods can use this command.

--------------------------------------
### **remove_player**
Remove a Player from your Team. Only Captains/Mods can use this command.

--------------------------------------
### **add_ign**
Add your In-Game Name. Captain/Mods can add IGN for other players.

--------------------------------------
### **delete_team**
Delete your Team. Only Captains/Mods can use this command.

--------------------------------------
