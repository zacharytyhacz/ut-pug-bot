Discord pug bot for UT99

commands: 

admin commands:
# add new game modes 
.new <gamemode> <max_players> <teams>  <OPTIONAL_server> 
.new ctf 12 2 12.345.678:7777

# edit existing game mode
.edit <gamemode>

# reset a picking session
.reset <gamemode> 
.reset ctf
#( if in a picking session, '.reset' will reset joined pug

# remove player from gamode 
.remove <id tag> <gamemode> 
.remove @troublemaker ctf 


general commands:
# show gamemodes and player count 
.list
.ls

# show all gamemodes and players counts
.lsa

#show players in a gamemode
.list <gamemode>
.ls <gamemode>

# join a gamemode
.join <gamemode>
.j <gamemode>

# leave a gamemode
.lv <gamemode>
.leave <gamemode>

# leave all gamemodes 
.lva 

# show last game 
.last <OPTIONAL_gamemode>
.lastt
.lasttt

# promote
.promote <gamemode>
.p <gamemode>

# get stats like pugs played and average pick, captained, etc 
.stats <player_id/tag>


picking mode if gamemode has multiple teams:
# don't get picked for captain
.nocaptain 
.nocap 

# captain up
.captain 
.cap 

#pick a player form list 
.pick <number>

# reset picking 
.reset 





