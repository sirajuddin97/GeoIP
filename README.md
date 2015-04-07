SA-MP Geolocation
==========
Geographical IP based on MaxMind databases for SA-MP

Functions
----------
```C
GetPlayerCountry(playerid, string[], const len = sizeof(string));
GetPlayerISP(playerid, string[], const len = sizeof(string));
GetPlayerCity(playerid, string[], const len = sizeof(string));
GetPlayerGMT(playerid);

GetIPCountry(ip[], dest[], len = sizeof(dest));
GetIPISP(ip[], dest[], len = sizeof(dest));
GetIPCity(ip[], dest[], len = sizeof(dest));
GetIPGMT(ip[]);
```

Speed Test
----------
```C
[07:54:06] took 1 ms - GetPlayerCountry
[07:54:06] took 0 ms - GetPlayerCity
[07:54:06] took 17 ms - GetPlayerISP
```

Thanks to
----------
- Whitetiger
- RaekwonDaChef
- Y_Less
- Andreas Gohr