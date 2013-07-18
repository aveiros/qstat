QStat - Real-time game server stats
=====

SVN version from http://sourceforge.net/projects/qstat/

Install
-------

	./configure
	make && make install

Version
-------

	qstat --json-version
    
``` json
{
    "version": "2.12"
}
```

Protocols
-------

    qstat --json-protocols
    
``` json
{
    "a2s": "Half-Life 2 new",
	"ams": "America's Army v2.x",
	"bfbc2": "Battlefield Bad Company 2",
	"bfs": "BFRIS",
	"crysis": "Crysis",
	"cube2": "Sauerbraten",
	"d3g": "Descent3 Gamespy Protocol",
	"d3m": "Descent3 Master (PXO)",
	"d3p": "Descent3 PXO protocol",
	"d3s": "Descent3",
	"dm3m": "Doom 3 Master",
	"dm3s": "Doom 3",
	"efm": "Star Trek: Elite Force",
	"efs": "Star Trek: Elite Force",
	"etqws": "QuakeWars",
	"eye": "All Seeing Eye Protocol",
	"fcs": "FarCry",
	"fls": "Frontlines-Fuel of War",
	"gps": "Gamespy Protocol",
	"grs": "Ghost Recon",
	"gs2": "Gamespy V2 Protocol",
	"gs3": "Gamespy V3 Protocol",
	"gs4": "Gamespy V4 Protocol",
	"gsm": "Gamespy Master",
	"h2s": "Hexen II",
	"hazes": "Haze Protocol",
	"hl2s": "Half-Life 2",
	"hlm": "Half-Life Master",
	"hls": "Half-Life",
	"hrs": "Heretic II",
	"hwm": "HexenWorld Master",
	"hws": "HexenWorld",
	"jk3m": "Jedi Knight: Jedi Academy",
	"jk3s": "Jedi Knight: Jedi Academy",
	"kps": "Kingpin",
	"mumble": "Mumble",
	"ottdm": "openTTD Master",
	"ottds": "OpenTTD",
	"preys": "PREY",
	"prs": "Pariah",
	"q2m": "Quake II Master",
	"q2s": "Quake II",
	"q3m": "Quake III Master",
	"q3s": "Quake III: Arena",
	"q4m": "Quake 4 Master",
	"q4s": "Quake 4",
	"qs": "Quake",
	"qwm": "QuakeWorld Master",
	"qws": "QuakeWorld",
	"rss": "Ravenshield",
	"rwm": "Return to Castle Wolfenstein Master",
	"rws": "Return to Castle Wolfenstein",
	"sas": "Savage",
	"sfs": "Soldier of Fortune",
	"sgs": "Shogo: Mobile Armor Division",
	"sns": "Sin",
	"stm": "Steam Master",
	"t2m": "Tribes 2 Master",
	"t2s": "Tribes 2",
	"tbm": "Tribes Master",
	"tbs": "Tribes",
	"tee": "Teeworlds",
	"terraria": "Terraria",
	"tm": "TrackMania",
	"ts2": "Teamspeak 2",
	"ts3": "Teamspeak 3",
	"uns": "Unreal",
	"ut2004m": "UT2004 Master",
	"ut2s": "Unreal Tournament 2003",
	"ventrilo": "Ventrilo",
	"wics": "World in Conflict",
	"wolfs": "Wolfenstein"
}
```

Query
-----

    qstat -json -a2s XX.XX.XX.XX:27015

``` json
[
    {
		"protocol": "a2s",
		"address": "XX.XX.XX.XX:27015",
		"status": "online",
		"hostname": "XX.XX.XX.XX:27015",
		"name": "Dummy Server",
		"gametype": "cstrike",
		"map": "de_dust",
		"numplayers": 24,
		"maxplayers": 62,
		"numspectators": 0,
		"maxspectators": 0,
		"ping": 31,
		"retries": 0
	}
]
```
