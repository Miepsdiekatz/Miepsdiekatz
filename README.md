- 👋 Hi, I’m @Miepsdiekatz
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Miepsdiekatz/Miepsdiekatz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
options :
  g: &7[&b&lGerry&7]

  on rightclick on entity:
    if entity's display name is "&b&lGerry":
      send "{@g}"&f: Hellow %player%!"to player

  on rightclick on entity:
    if entity's display name is "&b&lspawn":
      make player execute "spawn"

   on rightclick on entity:
     if entity's display name is "&b&lGUI":
       open virtual chest inventory with size 3 named "&4GUI" to player
       format gui slot 11 of player with grass block named "&2Survival"  witch lore "&6Change gamemode to:" and
       "&62Survival" to run:
         set player's gamemode to survival
         close player's inventory
       format gui slot 15 player with bedrock names "&2Creative" with lore "&6Change" to:" and "&6Change"
       to run:
         set player's gamemode to creative 
         close player's inventory 
       format gui slot 22 of player with barrier named "&4Close" to run:
         close player's inventory
          
