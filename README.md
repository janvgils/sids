
## Simple Downlink Share Convention (SiDS)

### Some history

In the beginning there was:

> Nothing, and somebody needed to bring ideas and people together. Below an image created during one of the brainteam sessions from the ESTCube team (University of Tartu).

![In the beginning](images/Brainstorm-session.jpg)

### Preliminary sources

The idea is, to share history, current state and possible new options in regard to SiDS on this repository, in the meantime the following can be used as some base for getting an idea what SiDS is, and how it can support the question of: "How to store telemetry received by multiple stations, all over the world".

[Simple Downlink Share Convention v0.9 - SiDS](docs/Dombrovski-SIDS-Simple-Downlink-Share-Convention.pdf)\
Author Slavi Dombrovski / University of Würzburg (Germany)\
Created 15 January 2015

### Online sources

Windows based [Software to decode telemetry that is transmitted by satellites](https://www.pe0sat.vgnet.nl/decoding/tlm-decoding-software/dk3wn/) created by DK3WN.\
Telemetry submission when using [gr-satellites ](https://gr-satellites.readthedocs.io/en/latest/command_line.html?highlight=sids#telemetry-submission).

### Available SIDS enabled servers

The following organisations and universities have SIDS servers available online:

```
SatNOGS   : https://db.satnogs.org/api/telemetry/
TU Berlin : http://fachgebiet.rft.tu-berlin.de/ham/telemetry/send
AMSAT-F   : https://amsat.electrolab.fr/api/V2/SIDS
```
### Frame example send by GetKiss+

Below an example where a GRIZU-263A frame is decoded with the help of an UZ7HO sound-modem.
The sound-modem application intefaces via a kiss session towards GetKiss+ and forwards the frames to the destination sids server.

```
noradID=51025&source=[CALL]&timestamp=2022-02-10T10:56:02.800Z&frame=3C594D3256525A160203091A0687080000DC080000C8080000EE0A0000F00A0000E80A0000F10A00008C03ABFD38FFE0FC0000FFFF7DFF000001000000&locator=longLat&longitude=[LONG]&latitude=[LAT]&version=1.3.12
```
