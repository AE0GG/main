[Provide Feedback](https://forms.gle/VdfJDC5vi1kbXSSW6)

# Radio Resources

## Table of contents

--------------------
## Hot Items
**[`^        back to top        ^`](# Radio-Resources)**

## Recommended Meshtastic Configuration Settings
**NOTE**: Link or snip/screenshot for Discord; copy/paste looks ugly.<br/>
[Source](mtnmesh.github.io)

### Personal Mobile Nodes
  | Radio & LoRa | Value | Position & Telemetry | Value |
  | ------------ | ----- | -------------------- | ----- |
  | Region       | US    | Smart Position | True |
  | Device Role  | CLIENT or CLIENT_MUTE | Broadcast Interval | 10800 (3 hours) |
  | Modem Preset | MEDIUM_FAST | Fixed Position | False |
  | Frequency Slot | 45 | Device Metrics | Disabled |
  | NodeInfo Interval | 10800 (3 hours) | Env. Metrics | Disabled |
  | Hop Limit | 5 |
  | Ignore MQTT | True |
  | OK to MQTT | True |

### Personal/Local Infrastructure
| Radio & LoRa | Value | Position & Telemetry | Value |
| ------------ | ----- | -------------------- | ----- |
| Region | US | Smart Position | False |
| Device Role | CLIENT or CLIENT_BASE | Broadcast Interval | 21600 (6 hours) |
| Is Unmessagable | TRUE | Fixed Position | True (set coordinates |
| Modem Preset | MEDIUM_FAST | Device Metrics | 10800 (3 hours) |
| Frequency Slot | 45 | Env. Metrics | 10800 (3 hours) |
| NodeInfo Interval | 21600 (6 hours) |
| Hop Limit | 3 |
| Ignore MQTT | True |
| OK to MQTT | True |

### Coordinated Public Infrastructure
| Radio & LoRa | Value | Position & Telemetry | Value |
| ------------ | ----- | -------------------- | ----- |
| Region | US | Smart Position | False |
| Device Role | ROUTER_LATE | Broadcast Interval | 21600 (6 hours) |
| Modem Preset | MEDIUM_FAST | Fixed Position | True (set coordinates) |
| Frequency Slot | 45 | Device Metrics | 10800 (3 hours) |
| NodeInfo Interval | 21600 (6 hours) | Env. Metrics | 10800 (3 hours) |
| Rebroadcast Mode | CORE_PORTNUMS_ONLY |
| Hop Limit | 3 |
| Ignore MQTT | True |
| OK to MQTT | True |

## Upcoming Events
- ~~Saturday, February 28th, 2026~~	[Dalton Hamfest](https://www.arrl.org/hamfests/dalton-hamfest-14)

## Quick Links

### Maps
- [MeshMap (Meshtastic)](https://meshmap.net/)
- [Meshtastic Map by Liam Cottle](https://meshtastic.liamcottle.net/)
- [Mountain Mesh Map](https://view.mtnme.sh/map)
- [MeshSense Map](https://meshsense.affirmatech.com/)
- [MeshCore Map](https://meshcore.co.uk/map.html)
- [Reticulum Map](https://rmap.world/)
- [SpecFive Map](https://specfive.com/pages/meshmap)

### Meshtastic
- [Official Website](https://meshtastic.org/)
- [Web Flasher](https://flasher.meshtastic.org/)
- [Web Client](https://client.meshtastic.org/)
- [Web Client (TEST)](https://client-test.meshtastic.org/)
- [MeshMap](https://meshmap.net/)
- [Map created by Liam Cottle](https://meshtastic.liamcottle.net/)
- [Official Discord](https://discord.gg/pVsRh9FEme)
- [Discover Local Groups](https://meshtastic.org/docs/community/local-groups/)
- [Reddit](https://www.reddit.com/r/meshtastic/)
- MQTT Settings
  - Server: `mqtt.meshtastic.org`
  - Username: `meshdev`
  - Password: `large4cats`
  - Enable `Uplink` on public channels

### MeshCore
- [Official Website](https://meshcore.nz/)
- [Web Flasher](https://flasher.meshcore.co.uk/)
- [Web Client](https://app.meshcore.nz/)
- [Web Client by Liam Cottle](https://meshcore.liamcottle.net/)
- [Map](https://meshcore.co.uk/map.html)
- [Reddit](https://www.reddit.com/r/meshcore/)
- [Initial Setup (soon)]()

## Online Stores
- [Amazon (Meshtastic search)](https://www.amazon.com/lora-meshtastic/s?k=lora+meshtastic)
- [Atlavox (expensive)](https://atlavox.com/)
- [eBay (Meshtastic search)](https://www.ebay.com/shop/meshtastic?_nkw=meshtastic)
- [LilyGo](https://lilygo.cc/en-us/collections/lilygo-with-meshtastic)
- [MeshCore](https://store.meshcore.co.uk/collections/all)
- [muzi.works](https://muzi.works/collections/all)
- [RAKwireless](https://store.rakwireless.com/collections/meshtastic)
- [Rokland](https://store.rokland.com/pages/meshtastic-hardware-rak-lilygo)
- [Seeed Studio](https://www.seeedstudio.com/meshtastic-products?srsltid=AfmBOooGyXmTdZQ6f6lQ_gboLLOsWvEhU60B_Ni6kJAXCIcJmSvm9C2V)
- [SpecFive (expensive)](https://specfive.com/collections/all)
## Radio Tools
- [Line-of-Sight Visualization](https://www.heywhatsthat.com/)

-Supporting Information
-TBD: Antennas, planning, calculators, 

-Desktop Software
-[MeshSense](https://affirmatech.com/meshsense) (Meshtastic)

# Communities

## Chattanooga Amateur Radio Club (CARC)
- [W4AM.net](http://W4AM.net)

## Tri-States Amateur Radio Club (TSARC)
- [TriStatesARC.com](http://tristatesarc.com)

## Ham Radio Crash Course
*Amateur Radio YouTuber*
- [Website](https://hamradiocrashcourse.com/)
- [YouTube Channel](https://www.youtube.com/@HamRadioCrashCourse)
- [Discord](https://discord.gg/X6H8Z9AmNg)

## TNMesh
*General Mesh, Greater Chattanooga, TN area*
- [Discord](https://discord.gg/ZjY8dTbeGn)

## Mountain Mesh
*General Mesh, North Georgia / East Tennessee area*
- [Website](https://mtnme.sh/)
- [Map](https://view.mtnme.sh/map)
- [Metrics](https://malla.mtnme.sh)
- [Discord](https://discord.gg/fddwJHN6jf)
- MQTT Settings
  - Server: `mqtt.mtnme.sh`
  - Username: `meshdev`
  - Password: `large4cats`
  - Topic:    `mtnme.sh/GA` OR `mtnme.sh/TN `
  - Enable `Uplink` on public channels

## Nash Mesh
*General Mesh, Nashville, TN*
- [Map](https://potato.tnmesh.org/)
- [Discord](https://discord.gg/5PFqMD62TF)

## TheCommsChannel
*MeshCore, local Youtuber*
- [Website](https://www.thecommschannel.com/)
- [YouTube Channel](https://www.youtube.com/@The_Comms_Channel)
- [Discord](https://discord.gg/pVsRh9FEme)
