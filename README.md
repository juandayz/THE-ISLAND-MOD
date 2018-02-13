# THE-ISLAND-MOD

THIS TURN EPOCH IN A NEW MOD. AFTER A PLANE CRASH PLAYERS NEED SURVIVE IN AN ISLAND AND FIND A WAY TO LEAVE THIS ISLAND.

#FEATURES: 
```
THE ISLAND MOD USES EPOCH AND NAPF. SO PLAYERS ONLY NEEDS DOWNLOAD EPOCH 1.6.2 client files.
THERS NO ZOMBIES.
ONLY PISTOLS AS WEAPONS.
THE LOOT SYSTEM IS TOTALLY REWRITED FOR THE ISLAND MOD. ONLY SPAWN IN CRATES WHO COMES AT THE COAST WITH THE WAVES.
PLAYES CAN FIND LOOT IN DEAD PASSANGERS BODYS, AND IN SOME CRATES AROUND THE PLANE CRASH.
THE CRAFT SYSTEM WAS REWRITED FOR THE ISLAND MOD. PLAYERS CAN CRAFT A HOUSE,A WATER SOURCE, A BRIDGE IN THE WATER AND A BOAT TO LEAVE THE ISLAND.
SOMETIMES AI PASSANGERS GET CRAZY AND WANT TO KILL PLAYERS.
THE CHOPWOOD WAS REWRITED FOR THE ISLAND MOD. THIS DROPS ITEMSLOGS. VERY USEFULL DURING THE GAME.
PLAYERS CANNOT LEAVE THE ISLAND SWIMING.
PLAYERS CAN DRINK HIS BLOOD.
PLAYERS CAN EAT TREE BARKS.
PLAYERS CAN EAT DEAD BODYS.
```

***INSTALL FOR HOST LIKE GTX*** 

```
1.Open ...@DayZ_Epoch_Server_island\addons\ and drop dayz_server.pbo in your @DayZ_Epoch_Server\addons\ (remove your own first).

2.Open ...\MPMissions\ and drop DayZ_Epoch_24.Napf.pbo into your MPMissions folder. (remove your own first).

3.If ure using another map that is not Napf..

-Find this line: (the name of the line could change according to the map you are currently using)
template = "DayZ_Epoch_11.Chernarus";
-Change By:
template = "DayZ_Epoch_24.Napf";
```

***INSTALL FOR LOCAL PC OR VIRTUAL MACHINES*** 

```
1.Create a fresh database

2.Create in C:\ a folder called epochIsland. (do not change the paths other way you gonna need edit all paths.)

3.Drop all content of your arma2 into C:\epochIsland

4.Drop all content of your arma2oa into C:\epochIsland but without those folder who start with @. Example do not put @DayZ

5.Download epoch 1.6.2 client files and drop into C:\epochIsland\ Link: https://epochmod.com/a2dayzepoch.php

6.Drop all .Dlls provided here into C:\epochIsland\

7.Drop Keys folder into C:\epochIsland\

8.Drop MPMissions folder provided here into C:\epochIsland\

9.Drop @DayZ_Epoch_Server_island folder provided here into C:\epochIsland\

10.Drop DZE_Server_Config into C:\ (yes C:\ NOT! into C:\epochIsland)

11.Open C:\DZE_Server_Config\HiveExt.ini and put your owns database user and pass values
Database = yourDBname
Username = yourMYSQLusername
Password = yourMYSQLpass

12.Open C:\DZE_Server_Config\BattlEye\BEServer.cfg and entry your own battleye pass:
RConPassword PUTYOURPASS

13.Open C:\DZE_Server_Config\START_WITH_RESTART.bat  and entry your owns values for:
set DB_USERNAME="YourMysqlUser"
set DB_PASSWORD="YourMysqlPass"
set DB_NAME="YourDataBaseName"


Done. Click on START_WITH_RESTART.bat to start your server with autorestart.
