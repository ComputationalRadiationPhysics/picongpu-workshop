# Welcome the PIConGPU workshop webpage

The next PIConGPU user workshop will be held at [HZDR](https://www.hzdr.de) from 18th till 22nd of February 2019.  
The workshop schedule, the lectures, and exercises can be found below. If you have any questions, please contact [Marco Garten](mailto:m.garten@hzdr.de).

## Schedule overview

![schedule](/img/schedule.png)

**lecture**  *exercise*

### Monday 

**Particle-in-cell Theory and Methods**

**Working as a community: mail lists, Issues, help**

*terminal, picongpu.profile, first simulation*

### Tuesday

**PIConGPU: manual and input files**

*configure parameter and configuration files and understanding errors*

**Python postprocessing**

*openPMD, python reader, matplotlib, plugins*

### Wednesday

**Parameter scans with jupyter GUI**

*cmake flags, workflows, widgets, param.py*

**PIConGPU: particle species**

*attributes and flags, filter, multi-plugins*

### Thursday

**PIConGPU: Laser-ion simulation and doping**

*manipulator, complex targets, ionization*

**PIConGPU: in situ processing**

*radiation, probes, and tracer*

### Friday


*individual exercises** 


## Where is the workshop on the HZDR campus?

The workshop will be held in the library (building 104 on [this plan](https://www.hzdr.de/db/Cms?pOid=27940)) in room 215.



## How to get from Dresden city center to HZDR

This [HZDR webpage](https://www.hzdr.de/db/Cms?pOid=10261&pNid=281) describes how to reach the HZDR.

For those staing in Dresden: there exist only two bus lines that drive from Dresden to HZDR in the morning: Bus 261 and Bus 229.
The interactive schedule can be found on the [VVO webpage](https://www.vvo-online.de/en/index.cshtml).
Be aware that there a school holiday in Saxony during the workshop, thus not all departure times will be available.

### Bus 261
The bus drives once an hour. Depending on where you enter, the departure times differ:

| Stop | Departure |
|------|-----------|
| [Hauptbahnhof](https://www.google.com/maps/place/Dresden+Hauptbahnhof/@51.0392879,13.7328118,17z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c58ad36f6dbf:0x645c7d686f635c34!8m2!3d51.0399296!4d13.7341902) (main station) | 07:10, 07:40, 08:08, 08:10, 09:15 |
| [Walpurgisstraße](https://www.google.com/maps/place/Dresden+Walpurgisstra%C3%9Fe/@51.042816,13.7351828,17z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709cf5fc77b1e17:0xcc86940dc037e9a8!8m2!3d51.04355!4d13.7379762) | 07:12, 07:42, -, 08:12, 09:17 |
| [Pirnaischer Platz](https://www.google.com/maps/place/Dresden+Pirnaischer+Platz/@51.0498781,13.7443989,17z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709cf5c9ae4960b:0xe627eedc87a90c66!8m2!3d51.0495721!4d13.7458887) | 07:15, 07:45, -, 08:15, 09:20 |
| [Albertplatz[(https://www.google.com/maps/place/Dresden+Albertplatz/@51.0620977,13.7440019,17z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709cf4005648b39:0x8410ca27beec92a2!8m2!3d51.061517!4d13.7460389) | 07:20, 07:50, 08:18, 08:20, 09:25 | 
| [Waldschlößchen](https://www.google.com/maps/place/Dresden+Waldschl%C3%B6%C3%9Fchen/@51.066807,13.7749444,17z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709cf32cb52353d:0x9f40bed383eaa72b!8m2!3d51.0673767!4d13.777748) | 07:24, 07:55, 08:23, 08:24, 09:30 |
| [Angelikastraße](https://www.google.com/maps/place/Dresden+Angelikastra%C3%9Fe/@51.0669014,13.7818324,17z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c8cde1a6d137:0xc338090b93507f0b!8m2!3d51.0669528!4d13.7850369) | 07:25, 07:56, 08:24, 08:25, 09:31 |
| [Plattleite](https://www.google.com/maps/place/Dresden+Plattleite/@51.0634746,13.820483,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c8faa778b9bb:0x43c0ba88c617c0c7!8m2!3d51.0636199!4d13.8220011) | 07:31, 08:01, 08:29, 08:31, 09:36 |
| [Schwimmhalle Bühlau](https://www.google.com/maps/place/Dresden+Schwimmhalle+B%C3%BChlau/@51.0620013,13.8365762,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c85777fec9e3:0x3f3b41e04588417a!8m2!3d51.0622507!4d13.8388386) | 07:34, 08:03, 08:31, 08:34, 09:38 |
| [Bühlau Ullersdorfer Platz](https://www.google.com/maps/place/Dresden+B%C3%BChlau+Ullersdorfer+Platz/@51.0618901,13.8527607,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c84faa0475f9:0xe0e2a9f9a3382365!8m2!3d51.062083!4d13.8533581) | 07:37, 08:05, 08:33, 08:37, 09:40 |
| [Am Steinkreuz (Weißig)](https://www.google.com/maps/place/Wei%C3%9Fig+Am+Steinkreuz/@51.0600088,13.8762729,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c831c926cf85:0x3e04a95a2ea20105!8m2!3d51.0600268!4d13.8774671) | 07:39, 08:07, 08:35, 08:39, 09:42 |
| [Am Weißiger Bach (Weißig)](https://www.google.com/maps/place/Wei%C3%9Fig+Am+Wei%C3%9Figer+Bach/@51.0613574,13.8843786,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c82c10225f3b:0xd39b1542b94803d1!8m2!3d51.0620333!4d13.8862936) | 07:41, 08:08, 08:36, 08:41, 09:43 |
| [Bautzner Landstraße (Weißig)](https://www.google.com/maps/place/Wei%C3%9Fig+Bautzner+Landstr/@51.0609292,13.9162164,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709b7cb12c5f2df:0x930b4c815caae225!8m2!3d51.0607348!4d13.9185385) | 07:44, 08:11, 08:39, 08:44, 09:46 |
| [Schänkhübel (Rossendorf)](https://www.google.com/maps/place/Rossendorf+Sch%C3%A4nkh%C3%BCbel/@51.0631307,13.9326798,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709b64c7d5135e9:0xd4a861977a5bddc!8m2!3d51.0634745!4d13.9339451) | 07:45, 08:13, 08:41, 08:45, 09:48 |
| [Siedlung Rossendorf B6 (Rossendorf)](https://www.google.com/maps/place/Siedlung+Rossendorf+B+6/@51.0639533,13.9406781,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709b652153bc67d:0x46ffa63e47c60ec1!8m2!3d51.0637565!4d13.9424316) | 07:46, 08:15, 08:43, 08:46, 09:50 |
| [Forschungszentrum (Rossendorf)](https://www.google.com/maps/place/Rossendorf+Forschungszentrum/@51.0637713,13.9475607,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709b65403ea3235:0x4d59d84f334c6588!8m2!3d51.0639663!4d13.948718) | 07:47, 08:16, 08:44, 08:47, 09:51 |

### Bus 229

Due to the holidays, there is only one bus in the morning going to HZDR. It starts at 06:40 from [Bühlau Ullersdorfer Platz](https://www.google.com/maps/place/Dresden+B%C3%BChlau+Ullersdorfer+Platz/@51.0618901,13.8527607,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709c84faa0475f9:0xe0e2a9f9a3382365!8m2!3d51.062083!4d13.8533581) and arrives at 06:52 at [Forschungszentrum (Rossendorf)](https://www.google.com/maps/place/Rossendorf+Forschungszentrum/@51.0637713,13.9475607,18z/data=!4m13!1m7!3m6!1s0x4709cf3fe162dc7f:0x60e5b61002af9539!2sAlbertpl.,+Dresden!3b1!8m2!3d51.0634362!4d13.7459975!3m4!1s0x4709b65403ea3235:0x4d59d84f334c6588!8m2!3d51.0639663!4d13.948718).


