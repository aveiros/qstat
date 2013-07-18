QStat - Real-time game server stats
=====

SVN version from http://sourceforge.net/projects/qstat/

Install
-------

	./configure
	make && make install
	
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
	"cod2m": "Call of Duty 2 Master",
	"cod2s": "Call of Duty 2",
	"cod4m": "Call of Duty 4 Master",
	"cod4s": "Call of Duty 4",
	"codm": "Call of Duty Master",
	"cods": "Call of Duty",
	"crs": "Command and Conquer: Renegade",
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
	"hla2s": "Half-Life",
	"hla2sm": "Steam Master",
	"hlm": "Half-Life Master",
	"hlqs": "Half-Life",
	"hls": "Half-Life",
	"hrs": "Heretic II",
	"hwm": "HexenWorld Master",
	"hws": "HexenWorld",
	"iourtm": "ioUrbanTerror Master",
	"iourts": "ioUrbanTerror",
	"jk3m": "Jedi Knight: Jedi Academy",
	"jk3s": "Jedi Knight: Jedi Academy",
	"kps": "Kingpin",
	"maqs": "Medal of Honor: Allied Assault (Q)",
	"mas": "Medal of Honor: Allied Assault",
	"mhs": "Medal of Honor: Allied Assault",
	"mumble": "Mumble",
	"netp": "NetPanzer",
	"netpm": "NetPanzer Master",
	"nexuizm": "Nexuiz Master",
	"nexuizs": "Nexuiz",
	"openarenam": "OpenArena Master",
	"openarenas": "OpenArena",
	"ottdm": "openTTD Master",
	"ottds": "OpenTTD",
	"preym": "Prey Master",
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
	"sms": "Serious Sam",
	"sns": "Sin",
	"sof2m": "SOF2 Master",
	"sof2m1.0": "SOF2 Master (1.0)",
	"sof2s": "Soldier of Fortune 2",
	"stm": "Steam Master",
	"stma2s": "Steam Master for A2S",
	"stmhl2": "Steam Master for HL2",
	"t2m": "Tribes 2 Master",
	"t2s": "Tribes 2",
	"tbm": "Tribes Master",
	"tbs": "Tribes",
	"tee": "Teeworlds",
	"terraria": "Terraria",
	"tm": "TrackMania",
	"tremulous": "Tremulous",
	"tremulousm": "Tremulous Master",
	"ts2": "Teamspeak 2",
	"ts3": "Teamspeak 3",
	"uns": "Unreal",
	"ut2004m": "UT2004 Master",
	"ut2004s": "UT2004",
	"ut2s": "Unreal Tournament 2003",
	"ut3s": "UT3",
	"ventrilo": "Ventrilo",
	"warsowm": "Warsow Master",
	"warsows": "Warsow",
	"waws": "Call of Duty World at War",
	"wics": "World in Conflict",
	"woetm": "Enemy Territory Master",
	"woets": "Enemy Territory",
	"wolfs": "Wolfenstein"
}
```
