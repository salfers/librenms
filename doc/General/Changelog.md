## 24.6.0
*(2024-06-16)*

A big thank you to the following 20 contributors this last month:

  - [murrant](https://github.com/murrant) (13)
  - [VVelox](https://github.com/VVelox) (7)
  - [PipoCanaja](https://github.com/PipoCanaja) (3)
  - [dependabot](https://github.com/apps/dependabot) (2)
  - [Npeca75](https://github.com/Npeca75) (2)
  - [ashwath129](https://github.com/ashwath129) (2)
  - [electrocret](https://github.com/electrocret) (2)
  - [scamp](https://github.com/scamp) (1)
  - [nicolasberens](https://github.com/nicolasberens) (1)
  - [sorano](https://github.com/sorano) (1)
  - [GonBlank](https://github.com/GonBlank) (1)
  - [jepke](https://github.com/jepke) (1)
  - [EinGlasVollKakao](https://github.com/EinGlasVollKakao) (1)
  - [Cougar](https://github.com/Cougar) (1)
  - [whitej46](https://github.com/whitej46) (1)
  - [cadirol](https://github.com/cadirol) (1)
  - [santiag0z](https://github.com/santiag0z) (1)
  - [rons4](https://github.com/rons4) (1)
  - [freddy36](https://github.com/freddy36) (1)
  - [cjsoftuk](https://github.com/cjsoftuk) (1)

Thanks to maintainers and others that helped with pull requests this month:

  - [murrant](https://github.com/murrant) (18)
  - [Jellyfrog](https://github.com/Jellyfrog) (12)
  - [electrocret](https://github.com/electrocret) (9)
  - [PipoCanaja](https://github.com/PipoCanaja) (1)

#### Feature
* ESRI ArcGIS geo map support ([#16059](https://github.com/librenms/librenms/pull/16059)) - [murrant](https://github.com/murrant)

#### Device
* Update Dell MIBs ([#16120](https://github.com/librenms/librenms/pull/16120)) - [murrant](https://github.com/murrant)
* Add TI-G102i (.46) and TI-PG1284i (.34) ([#16099](https://github.com/librenms/librenms/pull/16099)) - [nicolasberens](https://github.com/nicolasberens)
* Add "Bullet Camera" in Axis discovery. ([#16098](https://github.com/librenms/librenms/pull/16098)) - [sorano](https://github.com/sorano)
* [vlans] Add VLANs information to Huawei VRP os ([#16089](https://github.com/librenms/librenms/pull/16089)) - [Npeca75](https://github.com/Npeca75)
* Cisco Catalyst 1300 recognition ([#16080](https://github.com/librenms/librenms/pull/16080)) - [jepke](https://github.com/jepke)
* Fix Ruckus Unleashed product ID for OS detection ([#16067](https://github.com/librenms/librenms/pull/16067)) - [Cougar](https://github.com/Cougar)
* Fix error in riverbed ([#16066](https://github.com/librenms/librenms/pull/16066)) - [murrant](https://github.com/murrant)
* Update Hatteras DSLAM name ([#16054](https://github.com/librenms/librenms/pull/16054)) - [cadirol](https://github.com/cadirol)
* Add initial support for socomec-ups ([#16018](https://github.com/librenms/librenms/pull/16018)) - [Npeca75](https://github.com/Npeca75)
* Fix bdcom/pbn neighbour discovery ([#15935](https://github.com/librenms/librenms/pull/15935)) - [freddy36](https://github.com/freddy36)
* Add support for new sensors on Firebrick 9000 models. ([#15842](https://github.com/librenms/librenms/pull/15842)) - [cjsoftuk](https://github.com/cjsoftuk)

#### Webui
* Fix popup toast messages (Remove Flasher) ([#16090](https://github.com/librenms/librenms/pull/16090)) - [murrant](https://github.com/murrant)
* Handle $app_data['disks'] not being set for SMART app page display ([#16087](https://github.com/librenms/librenms/pull/16087)) - [VVelox](https://github.com/VVelox)
* Edit Current Map menu entry ([#16084](https://github.com/librenms/librenms/pull/16084)) - [murrant](https://github.com/murrant)
* Fix device summary widget alignment and dropdown color on dark theme ([#16083](https://github.com/librenms/librenms/pull/16083)) - [GonBlank](https://github.com/GonBlank)
* Fix duplicate maps in relationship ([#16081](https://github.com/librenms/librenms/pull/16081)) - [murrant](https://github.com/murrant)
* Manage Maps limit width ([#16055](https://github.com/librenms/librenms/pull/16055)) - [murrant](https://github.com/murrant)
* Widget hot refresh & worldmap cleanup ([#16053](https://github.com/librenms/librenms/pull/16053)) - [murrant](https://github.com/murrant)
* Align the buttons (Edit and Delete) to the right in Map Management ([#16052](https://github.com/librenms/librenms/pull/16052)) - [santiag0z](https://github.com/santiag0z)

#### Alerting
* AlertOps alert transport ([#16050](https://github.com/librenms/librenms/pull/16050)) - [ashwath129](https://github.com/ashwath129)
* SIGNL4 Alert Transport ([#16037](https://github.com/librenms/librenms/pull/16037)) - [rons4](https://github.com/rons4)

#### Applications
* Fix display of graphs on the multi-server app page for Mojo CAPE Submit ([#16094](https://github.com/librenms/librenms/pull/16094)) - [VVelox](https://github.com/VVelox)
* Two minor fixes for sagan ([#16082](https://github.com/librenms/librenms/pull/16082)) - [VVelox](https://github.com/VVelox)
* Fix path related issues for ss and systemd applications ([#16045](https://github.com/librenms/librenms/pull/16045)) - [VVelox](https://github.com/VVelox)
* Add Suricata 7 support to Suricata ([#16044](https://github.com/librenms/librenms/pull/16044)) - [VVelox](https://github.com/VVelox)

#### Api
* Return error when no device ports found ([#16043](https://github.com/librenms/librenms/pull/16043)) - [murrant](https://github.com/murrant)

#### Settings
* Add nfsen_base to config_definitions.json ([#16065](https://github.com/librenms/librenms/pull/16065)) - [whitej46](https://github.com/whitej46)
* Remove device_perf_purge ([#16057](https://github.com/librenms/librenms/pull/16057)) - [electrocret](https://github.com/electrocret)
* Remove enable_ports_poe ([#16056](https://github.com/librenms/librenms/pull/16056)) - [electrocret](https://github.com/electrocret)

#### Bug
* Bug - Sorting FDB table by devices ([#16116](https://github.com/librenms/librenms/pull/16116)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix typo in device edit page ([#16096](https://github.com/librenms/librenms/pull/16096)) - [murrant](https://github.com/murrant)
* Fix fping bulk ([#16085](https://github.com/librenms/librenms/pull/16085)) - [murrant](https://github.com/murrant)
* Fix duplication of processor entries & limit length of type ([#16075](https://github.com/librenms/librenms/pull/16075)) - [EinGlasVollKakao](https://github.com/EinGlasVollKakao)

#### Refactor
* Rename index_string to str_index_as_numeric ([#15916](https://github.com/librenms/librenms/pull/15916)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Documentation
* Note the suffix/prefix stuff for LDAP auth ([#16091](https://github.com/librenms/librenms/pull/16091)) - [VVelox](https://github.com/VVelox)
* Clean up SMART docs a bit ([#16086](https://github.com/librenms/librenms/pull/16086)) - [VVelox](https://github.com/VVelox)
* Update Transports.md to add documentation for AlertOps ([#16058](https://github.com/librenms/librenms/pull/16058)) - [ashwath129](https://github.com/ashwath129)

#### Misc
* Don't run poller validations when there are no devices ([#16088](https://github.com/librenms/librenms/pull/16088)) - [murrant](https://github.com/murrant)

#### Mibs
* Fix ECS4120 MIB, resolves #16093 ([#16101](https://github.com/librenms/librenms/pull/16101)) - [scamp](https://github.com/scamp)

#### Dependencies
* Bump braces from 3.0.2 to 3.0.3 ([#16105](https://github.com/librenms/librenms/pull/16105)) - [dependabot](https://github.com/apps/dependabot)
* Bump composer/composer from 2.7.1 to 2.7.7 ([#16104](https://github.com/librenms/librenms/pull/16104)) - [dependabot](https://github.com/apps/dependabot)


## 24.5.0
*(2024-05-19)*

A big thank you to the following 23 contributors this last month:

  - [murrant](https://github.com/murrant) (24)
  - [santiag0z](https://github.com/santiag0z) (5)
  - [eskyuu](https://github.com/eskyuu) (3)
  - [sogadm](https://github.com/sogadm) (2)
  - [Jarod2801](https://github.com/Jarod2801) (2)
  - [Pikamander2](https://github.com/Pikamander2) (1)
  - [scamp](https://github.com/scamp) (1)
  - [ottorei](https://github.com/ottorei) (1)
  - [whitej46](https://github.com/whitej46) (1)
  - [sonic45132](https://github.com/sonic45132) (1)
  - [fbouynot](https://github.com/fbouynot) (1)
  - [EinGlasVollKakao](https://github.com/EinGlasVollKakao) (1)
  - [h-barnhart](https://github.com/h-barnhart) (1)
  - [sarabveer](https://github.com/sarabveer) (1)
  - [netravnen](https://github.com/netravnen) (1)
  - [jthiltges](https://github.com/jthiltges) (1)
  - [hatboxen](https://github.com/hatboxen) (1)
  - [electrocret](https://github.com/electrocret) (1)
  - [washcroft](https://github.com/washcroft) (1)
  - [Npeca75](https://github.com/Npeca75) (1)
  - [paulierco](https://github.com/paulierco) (1)
  - [drshawnkwang](https://github.com/drshawnkwang) (1)
  - [systeembeheerder](https://github.com/systeembeheerder) (1)

Thanks to maintainers and others that helped with pull requests this month:

  - [murrant](https://github.com/murrant) (22)
  - [Jellyfrog](https://github.com/Jellyfrog) (13)
  - [electrocret](https://github.com/electrocret) (3)
  - [ottorei](https://github.com/ottorei) (1)
  - [PipoCanaja](https://github.com/PipoCanaja) (1)

#### Feature
* Custom Maps: geo map and color backgrounds ([#16020](https://github.com/librenms/librenms/pull/16020)) - [murrant](https://github.com/murrant)
* Show custom maps in device overview ([#15985](https://github.com/librenms/librenms/pull/15985)) - [murrant](https://github.com/murrant)
* New Map Menu ([#15969](https://github.com/librenms/librenms/pull/15969)) - [murrant](https://github.com/murrant)
* Mysql PDO options to support SSL/TLS client communication ([#15832](https://github.com/librenms/librenms/pull/15832)) - [drshawnkwang](https://github.com/drshawnkwang)
* Snmpscan.py output errors and nodns ([#15673](https://github.com/librenms/librenms/pull/15673)) - [murrant](https://github.com/murrant)

#### Breaking Change
* Linux MegaRAID SAS fixes ([#15566](https://github.com/librenms/librenms/pull/15566)) - [eskyuu](https://github.com/eskyuu)

#### Device
* Use null coalescing on Panos.php ([#16019](https://github.com/librenms/librenms/pull/16019)) - [ottorei](https://github.com/ottorei)
* Improved powerwalker sensors ([#15999](https://github.com/librenms/librenms/pull/15999)) - [EinGlasVollKakao](https://github.com/EinGlasVollKakao)
* Added initial support for ULAF+ devices ([#15997](https://github.com/librenms/librenms/pull/15997)) - [Jarod2801](https://github.com/Jarod2801)
* Correct swapped SET and WHERE parameters in bgp-peers/dell-os10.inc.php ([#15983](https://github.com/librenms/librenms/pull/15983)) - [jthiltges](https://github.com/jthiltges)
* Added FibroLAN devices ([#15967](https://github.com/librenms/librenms/pull/15967)) - [Jarod2801](https://github.com/Jarod2801)
* New velocloud devices ([#15958](https://github.com/librenms/librenms/pull/15958)) - [paulierco](https://github.com/paulierco)

#### Webui
* Fix issue loading session preferences ([#16041](https://github.com/librenms/librenms/pull/16041)) - [murrant](https://github.com/murrant)
* Device location map zoom out when location N/A ([#16034](https://github.com/librenms/librenms/pull/16034)) - [murrant](https://github.com/murrant)
* Added read permission test to the custom map model ([#16030](https://github.com/librenms/librenms/pull/16030)) - [eskyuu](https://github.com/eskyuu)
* Do not allow the legend nodes to trigger the node edit modal ([#16026](https://github.com/librenms/librenms/pull/16026)) - [eskyuu](https://github.com/eskyuu)
* Mobile menu full height ([#16011](https://github.com/librenms/librenms/pull/16011)) - [murrant](https://github.com/murrant)
* Map Management: Show Groups ([#16005](https://github.com/librenms/librenms/pull/16005)) - [murrant](https://github.com/murrant)
* Change custom map editor icon ([#16004](https://github.com/librenms/librenms/pull/16004)) - [murrant](https://github.com/murrant)
* Custom Map: Show crosshairs when adding ([#15978](https://github.com/librenms/librenms/pull/15978)) - [murrant](https://github.com/murrant)
* On-demand map menu items ([#15971](https://github.com/librenms/librenms/pull/15971)) - [murrant](https://github.com/murrant)
* Custom Maps: make edit title clickable ([#15965](https://github.com/librenms/librenms/pull/15965)) - [murrant](https://github.com/murrant)
* [webui] sort ports in VLANs blade ([#15960](https://github.com/librenms/librenms/pull/15960)) - [Npeca75](https://github.com/Npeca75)

#### Graphs
* Fix icmp ping y-axis over 1000ms ([#16039](https://github.com/librenms/librenms/pull/16039)) - [murrant](https://github.com/murrant)
* Fix graph_type variable (svg / png) ([#15972](https://github.com/librenms/librenms/pull/15972)) - [washcroft](https://github.com/washcroft)

#### Snmp Traps
* SNMP Traps - Ciena AAA ([#15998](https://github.com/librenms/librenms/pull/15998)) - [h-barnhart](https://github.com/h-barnhart)

#### Bug
* Fix downtime in corner cases ([#16040](https://github.com/librenms/librenms/pull/16040)) - [murrant](https://github.com/murrant)
* Fix WirelessSensor incorrect model ([#16016](https://github.com/librenms/librenms/pull/16016)) - [whitej46](https://github.com/whitej46)
* Merge duplicate toBytes functions ([#15994](https://github.com/librenms/librenms/pull/15994)) - [murrant](https://github.com/murrant)
* Fix systemd graphs using wrong rrd filename variable ([#15988](https://github.com/librenms/librenms/pull/15988)) - [sarabveer](https://github.com/sarabveer)
* Rrd source does not work with rrdcached ([#15974](https://github.com/librenms/librenms/pull/15974)) - [murrant](https://github.com/murrant)
* Git ignore custom map images ([#15966](https://github.com/librenms/librenms/pull/15966)) - [murrant](https://github.com/murrant)
* Packet_loss macros quick fix ([#15961](https://github.com/librenms/librenms/pull/15961)) - [murrant](https://github.com/murrant)

#### Cleanup
* Fix incorrect number of seconds in a day ([#16042](https://github.com/librenms/librenms/pull/16042)) - [Pikamander2](https://github.com/Pikamander2)

#### Documentation
* [DOC] Update Customizing-the-Web-UI.md ([#16025](https://github.com/librenms/librenms/pull/16025)) - [santiag0z](https://github.com/santiag0z)
* [DOC] Install LibreNMS: add Icons ([#16017](https://github.com/librenms/librenms/pull/16017)) - [santiag0z](https://github.com/santiag0z)
* Set httpd_cache_t type to /opt/librenms/cache ([#16000](https://github.com/librenms/librenms/pull/16000)) - [fbouynot](https://github.com/fbouynot)
* Update to Material for MkDocs 8.3.9 -\> 9.5.20 ([#15996](https://github.com/librenms/librenms/pull/15996)) - [santiag0z](https://github.com/santiag0z)
* Update link to LibreNMS origin blog post ([#15981](https://github.com/librenms/librenms/pull/15981)) - [hatboxen](https://github.com/hatboxen)
* Remove poller_name from docs ([#15979](https://github.com/librenms/librenms/pull/15979)) - [electrocret](https://github.com/electrocret)
* Update packet_loss docs ([#15962](https://github.com/librenms/librenms/pull/15962)) - [murrant](https://github.com/murrant)
* Update Dispatcher-Service.md ([#15705](https://github.com/librenms/librenms/pull/15705)) - [systeembeheerder](https://github.com/systeembeheerder)

#### Translation
* Massive changes to the Chinese interface translation. ([#16009](https://github.com/librenms/librenms/pull/16009)) - [sogadm](https://github.com/sogadm)
* Chinese translation fixesChinese translation fixes ([#15991](https://github.com/librenms/librenms/pull/15991)) - [sogadm](https://github.com/sogadm)

#### Tests
* Always run tests ([#16024](https://github.com/librenms/librenms/pull/16024)) - [murrant](https://github.com/murrant)

#### Mibs
* Update MIB for Edge-Core ECS4120-Series ([#16023](https://github.com/librenms/librenms/pull/16023)) - [scamp](https://github.com/scamp)
* Update to latest revision ([#15984](https://github.com/librenms/librenms/pull/15984)) - [netravnen](https://github.com/netravnen)


## 24.4.0
*(2024-04-19)*

A big thank you to the following 18 contributors this last month:

  - [murrant](https://github.com/murrant) (8)
  - [PipoCanaja](https://github.com/PipoCanaja) (4)
  - [xorrkaz](https://github.com/xorrkaz) (2)
  - [moisseev](https://github.com/moisseev) (1)
  - [VVelox](https://github.com/VVelox) (1)
  - [Taarek](https://github.com/Taarek) (1)
  - [Melhuig](https://github.com/Melhuig) (1)
  - [dependabot](https://github.com/apps/dependabot) (1)
  - [Lollbrant](https://github.com/Lollbrant) (1)
  - [HolgerHees](https://github.com/HolgerHees) (1)
  - [voileux](https://github.com/voileux) (1)
  - [hvanderheide](https://github.com/hvanderheide) (1)
  - [jasoncheng7115](https://github.com/jasoncheng7115) (1)
  - [h-barnhart](https://github.com/h-barnhart) (1)
  - [Jellyfrog](https://github.com/Jellyfrog) (1)
  - [CTV-2023](https://github.com/CTV-2023) (1)
  - [fbouynot](https://github.com/fbouynot) (1)
  - [OSIRIS-REx](https://github.com/OSIRIS-REx) (1)

Thanks to maintainers and others that helped with pull requests this month:

  - [Jellyfrog](https://github.com/Jellyfrog) (13)
  - [murrant](https://github.com/murrant) (9)
  - [PipoCanaja](https://github.com/PipoCanaja) (8)
  - [electrocret](https://github.com/electrocret) (1)

#### Feature
* Improved Latency graph ([#15940](https://github.com/librenms/librenms/pull/15940)) - [murrant](https://github.com/murrant)

#### Security
* Fix Graph date selector ([#15956](https://github.com/librenms/librenms/pull/15956)) - [murrant](https://github.com/murrant)
* Fix JS injection in Service Templates ([#15954](https://github.com/librenms/librenms/pull/15954)) - [murrant](https://github.com/murrant)
* Fix SQL injection issues in packages search ([#15950](https://github.com/librenms/librenms/pull/15950)) - [murrant](https://github.com/murrant)
* Improve order validation in list_devices ([#15885](https://github.com/librenms/librenms/pull/15885)) - [Jellyfrog](https://github.com/Jellyfrog)

#### Device
* ILO storage: fix malformed snmp data parsing ([#15931](https://github.com/librenms/librenms/pull/15931)) - [HolgerHees](https://github.com/HolgerHees)
* Add Fortigate HA state sensor definition ([#15924](https://github.com/librenms/librenms/pull/15924)) - [hvanderheide](https://github.com/hvanderheide)
* Devices - Ciena RLS 6500 ([#15909](https://github.com/librenms/librenms/pull/15909)) - [h-barnhart](https://github.com/h-barnhart)
* Cumulus mellanox discovery ([#15732](https://github.com/librenms/librenms/pull/15732)) - [fbouynot](https://github.com/fbouynot)
* Added support for new device OS Westermo WeOS ([#15674](https://github.com/librenms/librenms/pull/15674)) - [OSIRIS-REx](https://github.com/OSIRIS-REx)

#### Webui
* Fix null in services ([#15945](https://github.com/librenms/librenms/pull/15945)) - [murrant](https://github.com/murrant)

#### Alerting
* Pretty up Slack formatting. ([#15898](https://github.com/librenms/librenms/pull/15898)) - [xorrkaz](https://github.com/xorrkaz)

#### Graphs
* Fix typo ([#15952](https://github.com/librenms/librenms/pull/15952)) - [Taarek](https://github.com/Taarek)
* Fix graph selection when to/from missing from url ([#15946](https://github.com/librenms/librenms/pull/15946)) - [murrant](https://github.com/murrant)

#### Applications
* For gzip+base64 compressed json, don't call stripslashes ([#15953](https://github.com/librenms/librenms/pull/15953)) - [VVelox](https://github.com/VVelox)
* Fix PDNS recursor error ([#15942](https://github.com/librenms/librenms/pull/15942)) - [murrant](https://github.com/murrant)

#### Api
* Add type property to Device class to update it by API ([#15930](https://github.com/librenms/librenms/pull/15930)) - [voileux](https://github.com/voileux)
* Add support for a maintenance boolean in API results. ([#15904](https://github.com/librenms/librenms/pull/15904)) - [xorrkaz](https://github.com/xorrkaz)

#### Bug
* Skip rrd sources that do not exist ([#15959](https://github.com/librenms/librenms/pull/15959)) - [murrant](https://github.com/murrant)
* Bug - Cisco NAC key error ([#15934](https://github.com/librenms/librenms/pull/15934)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - typo for request rate + sanity on numerical not_null values ([#15919](https://github.com/librenms/librenms/pull/15919)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - vrp - fix signed-tinyint overloaded with disabled radios ([#15917](https://github.com/librenms/librenms/pull/15917)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Documentation
* Add missing p5-File-Slurp dependency ([#15955](https://github.com/librenms/librenms/pull/15955)) - [moisseev](https://github.com/moisseev)
* Fix "lnms config:set" command syntax ([#15949](https://github.com/librenms/librenms/pull/15949)) - [Melhuig](https://github.com/Melhuig)
* Graylog how to set up non-admin user ([#15938](https://github.com/librenms/librenms/pull/15938)) - [Lollbrant](https://github.com/Lollbrant)
* Documentation - opcache issue on Debian 12 ([#15870](https://github.com/librenms/librenms/pull/15870)) - [CTV-2023](https://github.com/CTV-2023)

#### Translation
* Fix wrong terminology ([#15920](https://github.com/librenms/librenms/pull/15920)) - [jasoncheng7115](https://github.com/jasoncheng7115)

#### Dependencies
* Bump tecnickcom/tcpdf from 6.6.5 to 6.7.4 ([#15948](https://github.com/librenms/librenms/pull/15948)) - [dependabot](https://github.com/apps/dependabot)


## 24.3.0
*(2024-04-01)*

A big thank you to the following 24 contributors this last month:

  - [rpardim](https://github.com/rpardim) (4)
  - [dependabot](https://github.com/apps/dependabot) (3)
  - [electrocret](https://github.com/electrocret) (3)
  - [bionicman](https://github.com/bionicman) (2)
  - [PipoCanaja](https://github.com/PipoCanaja) (2)
  - [eskyuu](https://github.com/eskyuu) (2)
  - [Walkablenormal](https://github.com/Walkablenormal) (2)
  - [bnerickson](https://github.com/bnerickson) (2)
  - [rudybroersma](https://github.com/rudybroersma) (2)
  - [d-k-7](https://github.com/d-k-7) (1)
  - [murrant](https://github.com/murrant) (1)
  - [czarnian](https://github.com/czarnian) (1)
  - [dmbokhan](https://github.com/dmbokhan) (1)
  - [TheMysteriousX](https://github.com/TheMysteriousX) (1)
  - [msaringer](https://github.com/msaringer) (1)
  - [Didr](https://github.com/Didr) (1)
  - [vhuk](https://github.com/vhuk) (1)
  - [Jellyfrog](https://github.com/Jellyfrog) (1)
  - [KingDaveRa](https://github.com/KingDaveRa) (1)
  - [Npeca75](https://github.com/Npeca75) (1)
  - [dethmetaljeff](https://github.com/dethmetaljeff) (1)
  - [blknight88](https://github.com/blknight88) (1)
  - [gunkaaa](https://github.com/gunkaaa) (1)
  - [pjordanovic](https://github.com/pjordanovic) (1)

Thanks to maintainers and others that helped with pull requests this month:

  - [Jellyfrog](https://github.com/Jellyfrog) (25)
  - [electrocret](https://github.com/electrocret) (7)
  - [PipoCanaja](https://github.com/PipoCanaja) (5)
  - [murrant](https://github.com/murrant) (2)
  - [laf](https://github.com/laf) (2)
  - [mpikzink](https://github.com/mpikzink) (1)
  - [VVelox](https://github.com/VVelox) (1)

#### Feature
* Support for InfluxDB V2 API ([#15861](https://github.com/librenms/librenms/pull/15861)) - [Walkablenormal](https://github.com/Walkablenormal)

#### Breaking Change
* Wireguard application graph cleanup and new wireguard interface/global metrics. ([#15847](https://github.com/librenms/librenms/pull/15847)) - [bnerickson](https://github.com/bnerickson)

#### Device
* Fix catos discovery ([#15915](https://github.com/librenms/librenms/pull/15915)) - [d-k-7](https://github.com/d-k-7)
* Add health sensors ([#15910](https://github.com/librenms/librenms/pull/15910)) - [murrant](https://github.com/murrant)
* Add support for Huawei YunShan OS ([#15903](https://github.com/librenms/librenms/pull/15903)) - [czarnian](https://github.com/czarnian)
* Add support for Ubiquiti Unifi USP-RPS device ([#15900](https://github.com/librenms/librenms/pull/15900)) - [bionicman](https://github.com/bionicman)
* Add support for Ubiquiti Unifi LTE devices. ([#15899](https://github.com/librenms/librenms/pull/15899)) - [bionicman](https://github.com/bionicman)
* Checkpoint Gaia PowerSupply state sensor ([#15882](https://github.com/librenms/librenms/pull/15882)) - [rpardim](https://github.com/rpardim)
* Add support for Cisco FTD 3105 ([#15881](https://github.com/librenms/librenms/pull/15881)) - [msaringer](https://github.com/msaringer)
* Fix for Checkpoint Gaia VPN state sensor ([#15878](https://github.com/librenms/librenms/pull/15878)) - [rpardim](https://github.com/rpardim)
* Support for Forcepoint NGFW 6.11 and later ([#15872](https://github.com/librenms/librenms/pull/15872)) - [vhuk](https://github.com/vhuk)
* A10 ACOS version, state and count sensors ([#15871](https://github.com/librenms/librenms/pull/15871)) - [rpardim](https://github.com/rpardim)
* F5 BIG-IP state and count sensors ([#15865](https://github.com/librenms/librenms/pull/15865)) - [rpardim](https://github.com/rpardim)
* Supermicro bmc updates ([#15862](https://github.com/librenms/librenms/pull/15862)) - [dethmetaljeff](https://github.com/dethmetaljeff)
* YAMLized version of previous PR for Ericsson SSR 80xx routers ([#15834](https://github.com/librenms/librenms/pull/15834)) - [rudybroersma](https://github.com/rudybroersma)
* Fix for FortiSwitch RPM/percentage fans ([#15829](https://github.com/librenms/librenms/pull/15829)) - [rudybroersma](https://github.com/rudybroersma)
* Move sentry3 current/voltage/power sensors to YAML ([#15715](https://github.com/librenms/librenms/pull/15715)) - [gunkaaa](https://github.com/gunkaaa)
* Device - EPSON DS-860 + Network Interface Unit DSBXNW1 ([#15420](https://github.com/librenms/librenms/pull/15420)) - [pjordanovic](https://github.com/pjordanovic)

#### Applications
* Systemd Application Code Cleanup and new Systemd Unit State Metrics. ([#15848](https://github.com/librenms/librenms/pull/15848)) - [bnerickson](https://github.com/bnerickson)

#### Discovery
* Bug - Fix OSes 'Junos' and 'Hirschmann' misuse of entPhysicalIndex ([#15886](https://github.com/librenms/librenms/pull/15886)) - [TheMysteriousX](https://github.com/TheMysteriousX)

#### Bug
* Fix Vrf Table ([#15912](https://github.com/librenms/librenms/pull/15912)) - [electrocret](https://github.com/electrocret)
* Fix for explicit timezone selection ([#15890](https://github.com/librenms/librenms/pull/15890)) - [eskyuu](https://github.com/eskyuu)
* Bug - fix extra fields in DB entry create/update ([#15883](https://github.com/librenms/librenms/pull/15883)) - [PipoCanaja](https://github.com/PipoCanaja)
* Remove config_bgp config check in bird2 app ([#15877](https://github.com/librenms/librenms/pull/15877)) - [Didr](https://github.com/Didr)
* Custommap label fixes ([#15875](https://github.com/librenms/librenms/pull/15875)) - [eskyuu](https://github.com/eskyuu)
* [ipv4] fix /32 addresses discovery ([#15863](https://github.com/librenms/librenms/pull/15863)) - [Npeca75](https://github.com/Npeca75)

#### Refactor
* Refactor - remove unused entPhysicalIndex_measured ([#15892](https://github.com/librenms/librenms/pull/15892)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Documentation
* Added additional lines for selinux config to work with RHEL8 ([#15864](https://github.com/librenms/librenms/pull/15864)) - [KingDaveRa](https://github.com/KingDaveRa)
* Fix @signedGraphTag documention ([#15853](https://github.com/librenms/librenms/pull/15853)) - [blknight88](https://github.com/blknight88)

#### Tests
* Bump Github Actions to Node.JS 20. ([#15873](https://github.com/librenms/librenms/pull/15873)) - [Walkablenormal](https://github.com/Walkablenormal)

#### Dependencies
* Bump express from 4.18.2 to 4.19.2 ([#15913](https://github.com/librenms/librenms/pull/15913)) - [dependabot](https://github.com/apps/dependabot)
* Bump webpack-dev-middleware from 5.3.3 to 5.3.4 ([#15907](https://github.com/librenms/librenms/pull/15907)) - [dependabot](https://github.com/apps/dependabot)
* Bump follow-redirects from 1.15.4 to 1.15.6 ([#15897](https://github.com/librenms/librenms/pull/15897)) - [dependabot](https://github.com/apps/dependabot)
* Update dependencies ([#15869](https://github.com/librenms/librenms/pull/15869)) - [Jellyfrog](https://github.com/Jellyfrog)


## 24.2.0
*(2024-02-27)*

A big thank you to the following 46 contributors this last month:

  - [rudybroersma](https://github.com/rudybroersma) (14)
  - [Npeca75](https://github.com/Npeca75) (10)
  - [eskyuu](https://github.com/eskyuu) (6)
  - [electrocret](https://github.com/electrocret) (5)
  - [PipoCanaja](https://github.com/PipoCanaja) (5)
  - [Jellyfrog](https://github.com/Jellyfrog) (5)
  - [vhuk](https://github.com/vhuk) (5)
  - [murrant](https://github.com/murrant) (5)
  - [bnerickson](https://github.com/bnerickson) (3)
  - [fbouynot](https://github.com/fbouynot) (3)
  - [FlyveHest](https://github.com/FlyveHest) (2)
  - [nickhilliard](https://github.com/nickhilliard) (2)
  - [dependabot](https://github.com/apps/dependabot) (2)
  - [richard-ririe](https://github.com/richard-ririe) (2)
  - [laf](https://github.com/laf) (2)
  - [SourceDoctor](https://github.com/SourceDoctor) (2)
  - [VVelox](https://github.com/VVelox) (2)
  - [VoipTelCH](https://github.com/VoipTelCH) (1)
  - [fabriciotm](https://github.com/fabriciotm) (1)
  - [dirkx](https://github.com/dirkx) (1)
  - [swerveshot](https://github.com/swerveshot) (1)
  - [jmesserli](https://github.com/jmesserli) (1)
  - [lrizzi](https://github.com/lrizzi) (1)
  - [Personwho](https://github.com/Personwho) (1)
  - [OSIRIS-REx](https://github.com/OSIRIS-REx) (1)
  - [xorrkaz](https://github.com/xorrkaz) (1)
  - [jcostom](https://github.com/jcostom) (1)
  - [tevkar](https://github.com/tevkar) (1)
  - [descilla](https://github.com/descilla) (1)
  - [arjitc](https://github.com/arjitc) (1)
  - [My-Random-Thoughts](https://github.com/My-Random-Thoughts) (1)
  - [dlangille](https://github.com/dlangille) (1)
  - [blknight88](https://github.com/blknight88) (1)
  - [z0d1ac-RU](https://github.com/z0d1ac-RU) (1)
  - [lferrerfmv](https://github.com/lferrerfmv) (1)
  - [gil-obradors](https://github.com/gil-obradors) (1)
  - [gunkaaa](https://github.com/gunkaaa) (1)
  - [TvL2386](https://github.com/TvL2386) (1)
  - [santiag0z](https://github.com/santiag0z) (1)
  - [EinGlasVollKakao](https://github.com/EinGlasVollKakao) (1)
  - [kakohegyi](https://github.com/kakohegyi) (1)
  - [i4networks](https://github.com/i4networks) (1)
  - [Bierchermuesli](https://github.com/Bierchermuesli) (1)
  - [mhamzak008](https://github.com/mhamzak008) (1)
  - [nicklockhart-fullfibre](https://github.com/nicklockhart-fullfibre) (1)
  - [LoveSkylark](https://github.com/LoveSkylark) (1)

Thanks to maintainers and others that helped with pull requests this month:

  - [PipoCanaja](https://github.com/PipoCanaja) (35)
  - [Jellyfrog](https://github.com/Jellyfrog) (30)
  - [electrocret](https://github.com/electrocret) (26)
  - [laf](https://github.com/laf) (21)
  - [murrant](https://github.com/murrant) (11)
  - [mpikzink](https://github.com/mpikzink) (1)
  - [rudybroersma](https://github.com/rudybroersma) (1)
  - [ottorei](https://github.com/ottorei) (1)
  - [vhuk](https://github.com/vhuk) (1)

#### Feature
* Additional custom map features ([#15806](https://github.com/librenms/librenms/pull/15806)) - [eskyuu](https://github.com/eskyuu)
* Add/Remove devices from static devicegroups ([#15775](https://github.com/librenms/librenms/pull/15775)) - [richard-ririe](https://github.com/richard-ririe)
* Option to ignore device status ([#15697](https://github.com/librenms/librenms/pull/15697)) - [SourceDoctor](https://github.com/SourceDoctor)
* Add functionality for custom maps (weathermaps) ([#15633](https://github.com/librenms/librenms/pull/15633)) - [eskyuu](https://github.com/eskyuu)
* Alert Rule Editor: new notes field & SQL field improove ([#15631](https://github.com/librenms/librenms/pull/15631)) - [Bierchermuesli](https://github.com/Bierchermuesli)
* NAC - Improve search in WebUI - Keep Historical data ([#15629](https://github.com/librenms/librenms/pull/15629)) - [PipoCanaja](https://github.com/PipoCanaja)

#### Security
* Fix XSS in default example plugin ([#15711](https://github.com/librenms/librenms/pull/15711)) - [murrant](https://github.com/murrant)

#### Device
* Updated SLA poller for Cisco Nexus 9000 ([#15855](https://github.com/librenms/librenms/pull/15855)) - [FlyveHest](https://github.com/FlyveHest)
* Update geist-watchdog.yaml ([#15851](https://github.com/librenms/librenms/pull/15851)) - [fabriciotm](https://github.com/fabriciotm)
* Correctly identify FS Datacenter Switch N8560-48BC ([#15837](https://github.com/librenms/librenms/pull/15837)) - [rudybroersma](https://github.com/rudybroersma)
* Konica printers additional counters ([#15826](https://github.com/librenms/librenms/pull/15826)) - [Npeca75](https://github.com/Npeca75)
* Add HSRP state sensors for Cisco IOSXE on L3 switches ([#15823](https://github.com/librenms/librenms/pull/15823)) - [rudybroersma](https://github.com/rudybroersma)
* Add HSRP Sensor support for IOSXR ([#15821](https://github.com/librenms/librenms/pull/15821)) - [electrocret](https://github.com/electrocret)
* Add support for Cisco IE1000 ([#15820](https://github.com/librenms/librenms/pull/15820)) - [rudybroersma](https://github.com/rudybroersma)
* Initial support for Eltex mes24xx ([#15816](https://github.com/librenms/librenms/pull/15816)) - [Npeca75](https://github.com/Npeca75)
* Add support for Cadant E6000 ([#15813](https://github.com/librenms/librenms/pull/15813)) - [nickhilliard](https://github.com/nickhilliard)
* Add LRT-C / LCM-B / LRS-D / LCM-B modules to Luminato model ([#15812](https://github.com/librenms/librenms/pull/15812)) - [nickhilliard](https://github.com/nickhilliard)
* Add HSRP state sensors for Cisco IOS on L3 switches ([#15809](https://github.com/librenms/librenms/pull/15809)) - [rudybroersma](https://github.com/rudybroersma)
* [rfc1628] Add UPS Test (battery test) status sensor ([#15802](https://github.com/librenms/librenms/pull/15802)) - [Npeca75](https://github.com/Npeca75)
* Add build 22631 as Windows 11 23H2 ([#15800](https://github.com/librenms/librenms/pull/15800)) - [vhuk](https://github.com/vhuk)
* Zyxel ZynOS PoE Budget sensor support ([#15798](https://github.com/librenms/librenms/pull/15798)) - [rudybroersma](https://github.com/rudybroersma)
* Add Procurve NAC support ([#15794](https://github.com/librenms/librenms/pull/15794)) - [vhuk](https://github.com/vhuk)
* Add ArubaOS-CX VSF state sensor support ([#15793](https://github.com/librenms/librenms/pull/15793)) - [rudybroersma](https://github.com/rudybroersma)
* Support for new os/devices, CTS ([#15790](https://github.com/librenms/librenms/pull/15790)) - [OSIRIS-REx](https://github.com/OSIRIS-REx)
* Support for new Lancom devices ([#15779](https://github.com/librenms/librenms/pull/15779)) - [rudybroersma](https://github.com/rudybroersma)
* Add NAC support for Powerconnect ([#15778](https://github.com/librenms/librenms/pull/15778)) - [vhuk](https://github.com/vhuk)
* Detect UniFi U7 APs as UniFi AP type ([#15776](https://github.com/librenms/librenms/pull/15776)) - [jcostom](https://github.com/jcostom)
* FS.com S5810 Discovery fix ([#15765](https://github.com/librenms/librenms/pull/15765)) - [rudybroersma](https://github.com/rudybroersma)
* Device - webpower smart II snmp UPS card ([#15764](https://github.com/librenms/librenms/pull/15764)) - [Npeca75](https://github.com/Npeca75)
* Support for temp sensors - WUT Thermometers - W57605 and W57614 ([#15757](https://github.com/librenms/librenms/pull/15757)) - [rudybroersma](https://github.com/rudybroersma)
* Initial support for Supermicro BMC ([#15750](https://github.com/librenms/librenms/pull/15750)) - [Npeca75](https://github.com/Npeca75)
* ArubaOS-CX PSU state sensor support & OS and serial detection ([#15738](https://github.com/librenms/librenms/pull/15738)) - [rudybroersma](https://github.com/rudybroersma)
* Add FortiSwitch PSU state sensor support ([#15735](https://github.com/librenms/librenms/pull/15735)) - [rudybroersma](https://github.com/rudybroersma)
* Added support for Dlink dgs-1250-28x ([#15734](https://github.com/librenms/librenms/pull/15734)) - [Npeca75](https://github.com/Npeca75)
* Add FortiGate DHCP Scope usage percentage sensors ([#15727](https://github.com/librenms/librenms/pull/15727)) - [rudybroersma](https://github.com/rudybroersma)
* Added MES 2348B ([#15725](https://github.com/librenms/librenms/pull/15725)) - [z0d1ac-RU](https://github.com/z0d1ac-RU)
* Add FortiGate license status sensors ([#15722](https://github.com/librenms/librenms/pull/15722)) - [rudybroersma](https://github.com/rudybroersma)
* Handle icmpjitter SLA parsing for iosxe ([#15707](https://github.com/librenms/librenms/pull/15707)) - [FlyveHest](https://github.com/FlyveHest)
* Zyxel Wireless Controller OS ( Zyxel NXC series ) ([#15694](https://github.com/librenms/librenms/pull/15694)) - [kakohegyi](https://github.com/kakohegyi)
* Device - fix Counter64 octets value in 32bit column bgpPeerInTotalMessages ([#15621](https://github.com/librenms/librenms/pull/15621)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix tp-link jetstream FDB discovery ([#14321](https://github.com/librenms/librenms/pull/14321)) - [Npeca75](https://github.com/Npeca75)

#### Webui
* Disable Page Refresh on Oxidized Tools Page ([#15831](https://github.com/librenms/librenms/pull/15831)) - [electrocret](https://github.com/electrocret)
* Modify the date selector to use the session timezone ([#15783](https://github.com/librenms/librenms/pull/15783)) - [eskyuu](https://github.com/eskyuu)
* Switch bill_notes input to textarea ([#15749](https://github.com/librenms/librenms/pull/15749)) - [arjitc](https://github.com/arjitc)
* Sort smart app disks by label ([#15686](https://github.com/librenms/librenms/pull/15686)) - [SourceDoctor](https://github.com/SourceDoctor)

#### Alerting
* Add support for Webex max message length. ([#15789](https://github.com/librenms/librenms/pull/15789)) - [xorrkaz](https://github.com/xorrkaz)
* Rename JiraServiceManagement.php to Jiraservicemanagement.php ([#15717](https://github.com/librenms/librenms/pull/15717)) - [gil-obradors](https://github.com/gil-obradors)
* Add JiraServiceManagement Transport ([#15593](https://github.com/librenms/librenms/pull/15593)) - [mhamzak008](https://github.com/mhamzak008)
* Transport - Jira transport rewrite ([#15561](https://github.com/librenms/librenms/pull/15561)) - [LoveSkylark](https://github.com/LoveSkylark)

#### Graphs
* Fixed graphs for icmp service showing PL 4 times ([#15856](https://github.com/librenms/librenms/pull/15856)) - [VoipTelCH](https://github.com/VoipTelCH)
* Socket Statistic Application cleanup and application page graph fixes. ([#15845](https://github.com/librenms/librenms/pull/15845)) - [bnerickson](https://github.com/bnerickson)

#### Applications
* Deliver output for a specific memcached instance ([#15759](https://github.com/librenms/librenms/pull/15759)) - [tevkar](https://github.com/tevkar)
* Update nvidia.inc.php ([#15756](https://github.com/librenms/librenms/pull/15756)) - [descilla](https://github.com/descilla)
* Add BorgBackup monitoring support ([#15591](https://github.com/librenms/librenms/pull/15591)) - [VVelox](https://github.com/VVelox)
* Add dhcp-stats tests and update for v3 of the extend ([#15378](https://github.com/librenms/librenms/pull/15378)) - [VVelox](https://github.com/VVelox)

#### Billing
* Updated bill_data table, alter indexes and add new column ([#15751](https://github.com/librenms/librenms/pull/15751)) - [laf](https://github.com/laf)

#### Api
* Add API endpoints to update and delete Device Groups ([#15774](https://github.com/librenms/librenms/pull/15774)) - [richard-ririe](https://github.com/richard-ririe)
* Add port description API endpoints and documentation ([#15578](https://github.com/librenms/librenms/pull/15578)) - [nicklockhart-fullfibre](https://github.com/nicklockhart-fullfibre)

#### Settings
* Fix twofactor default value ([#15772](https://github.com/librenms/librenms/pull/15772)) - [murrant](https://github.com/murrant)
* Add isis module to os schema ([#15710](https://github.com/librenms/librenms/pull/15710)) - [murrant](https://github.com/murrant)

#### Discovery
* Fall back to IPV6-MIB IPv6 address discovery if IP-MIB IPv6 address discovery doesn't return any valid addresses ([#15714](https://github.com/librenms/librenms/pull/15714)) - [gunkaaa](https://github.com/gunkaaa)

#### Oxidized
* Add PollerGroup as an option for OxidizedMap ([#15696](https://github.com/librenms/librenms/pull/15696)) - [electrocret](https://github.com/electrocret)

#### Bug
* Update Port Real Time Graph error ([#15846](https://github.com/librenms/librenms/pull/15846)) - [electrocret](https://github.com/electrocret)
* [bugfix] Fix json-app-tool.php to work with Oid class. ([#15844](https://github.com/librenms/librenms/pull/15844)) - [bnerickson](https://github.com/bnerickson)
* Fix for linkDown/linkUp ifOperStatus ([#15835](https://github.com/librenms/librenms/pull/15835)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fix "Tempurature" Typo ([#15811](https://github.com/librenms/librenms/pull/15811)) - [lrizzi](https://github.com/lrizzi)
* Bug fixes for the custom maps ([#15810](https://github.com/librenms/librenms/pull/15810)) - [eskyuu](https://github.com/eskyuu)
* Remove dumpRawSql() function in AlertUtil.php ([#15803](https://github.com/librenms/librenms/pull/15803)) - [Personwho](https://github.com/Personwho)
* Make all image URLs absolute and fix path for viewer ([#15788](https://github.com/librenms/librenms/pull/15788)) - [eskyuu](https://github.com/eskyuu)
* Prevent ansi colors in key:generate output ([#15773](https://github.com/librenms/librenms/pull/15773)) - [Jellyfrog](https://github.com/Jellyfrog)
* VRP - avoid emptying bgpPeers description at discovery when manually set ([#15713](https://github.com/librenms/librenms/pull/15713)) - [PipoCanaja](https://github.com/PipoCanaja)
* OSPF instances and missing mandatory fields fix attempt ([#15712](https://github.com/librenms/librenms/pull/15712)) - [PipoCanaja](https://github.com/PipoCanaja)
* Fixed typo in misc/alert_rules.json with regards to "Space on ..." alerts ([#15708](https://github.com/librenms/librenms/pull/15708)) - [TvL2386](https://github.com/TvL2386)
* Don't escape leaflet tile url in location edit map ([#15695](https://github.com/librenms/librenms/pull/15695)) - [EinGlasVollKakao](https://github.com/EinGlasVollKakao)
* Show error if "Check Type" field is empty when creating new service template ([#15685](https://github.com/librenms/librenms/pull/15685)) - [vhuk](https://github.com/vhuk)

#### Refactor
* Rewrite ups-nut discovery to SnmpQuery:: ([#15850](https://github.com/librenms/librenms/pull/15850)) - [Npeca75](https://github.com/Npeca75)
* Rewrite lmsensors discovery to SnmpQuery:: ([#15833](https://github.com/librenms/librenms/pull/15833)) - [Npeca75](https://github.com/Npeca75)
* Rewrite ipv4 address discovery to Eloquent ([#15830](https://github.com/librenms/librenms/pull/15830)) - [Npeca75](https://github.com/Npeca75)

#### Documentation
* Applications.md formatting update for better readability. ([#15849](https://github.com/librenms/librenms/pull/15849)) - [bnerickson](https://github.com/bnerickson)
* Update Images.md ([#15824](https://github.com/librenms/librenms/pull/15824)) - [swerveshot](https://github.com/swerveshot)
* More precise OAuth group/role claim information ([#15817](https://github.com/librenms/librenms/pull/15817)) - [jmesserli](https://github.com/jmesserli)
* Add selinux open directory permission for rrdcached in RRDCached.md ([#15755](https://github.com/librenms/librenms/pull/15755)) - [fbouynot](https://github.com/fbouynot)
* Missing dir read permission in sepolicy in RRDCached.md ([#15754](https://github.com/librenms/librenms/pull/15754)) - [fbouynot](https://github.com/fbouynot)
* Update SQL override section after switch to SQL strict mode ([#15736](https://github.com/librenms/librenms/pull/15736)) - [blknight88](https://github.com/blknight88)
* Add CentOS option to SMART dependency install ([#15704](https://github.com/librenms/librenms/pull/15704)) - [fbouynot](https://github.com/fbouynot)

#### Misc
* Add kelvin to celcius conversion ([#15836](https://github.com/librenms/librenms/pull/15836)) - [dirkx](https://github.com/dirkx)

#### Mibs
* Update watchguard MIBs ([#15719](https://github.com/librenms/librenms/pull/15719)) - [lferrerfmv](https://github.com/lferrerfmv)

#### Dependencies
* Bump composer/composer from 2.6.6 to 2.7.0 ([#15808](https://github.com/librenms/librenms/pull/15808)) - [dependabot](https://github.com/apps/dependabot)
* Update PHP dependencies ([#15737](https://github.com/librenms/librenms/pull/15737)) - [murrant](https://github.com/murrant)
* Bump follow-redirects from 1.15.3 to 1.15.4 ([#15724](https://github.com/librenms/librenms/pull/15724)) - [dependabot](https://github.com/apps/dependabot)


## 24.1.0
*(2024-01-07)*

A big thank you to the following 37 contributors this last month:

  - [PipoCanaja](https://github.com/PipoCanaja) (12)
  - [murrant](https://github.com/murrant) (7)
  - [laf](https://github.com/laf) (5)
  - [electrocret](https://github.com/electrocret) (3)
  - [peejaychilds](https://github.com/peejaychilds) (3)
  - [Jellyfrog](https://github.com/Jellyfrog) (2)
  - [vhuk](https://github.com/vhuk) (2)
  - [MittWillson](https://github.com/MittWillson) (2)
  - [Bierchermuesli](https://github.com/Bierchermuesli) (2)
  - [netravnen](https://github.com/netravnen) (1)
  - [iliessens](https://github.com/iliessens) (1)
  - [sarcastic6](https://github.com/sarcastic6) (1)
  - [SourceDoctor](https://github.com/SourceDoctor) (1)
  - [altf4arnold](https://github.com/altf4arnold) (1)
  - [robje](https://github.com/robje) (1)
  - [rudybroersma](https://github.com/rudybroersma) (1)
  - [mtentilucci](https://github.com/mtentilucci) (1)
  - [tuxgasy](https://github.com/tuxgasy) (1)
  - [craig-nokia](https://github.com/craig-nokia) (1)
  - [brianegge](https://github.com/brianegge) (1)
  - [amyjohn000](https://github.com/amyjohn000) (1)
  - [VirTechSystems](https://github.com/VirTechSystems) (1)
  - [atj](https://github.com/atj) (1)
  - [lhwolfarth](https://github.com/lhwolfarth) (1)
  - [bonzo81](https://github.com/bonzo81) (1)
  - [Sweeny42](https://github.com/Sweeny42) (1)
  - [jduke-halls](https://github.com/jduke-halls) (1)
  - [pjordanovic](https://github.com/pjordanovic) (1)
  - [dependabot](https://github.com/apps/dependabot) (1)
  - [TheMysteriousX](https://github.com/TheMysteriousX) (1)
  - [swiftnode-linden](https://github.com/swiftnode-linden) (1)
  - [cguillaumie](https://github.com/cguillaumie) (1)
  - [luc-ass](https://github.com/luc-ass) (1)
  - [VVelox](https://github.com/VVelox) (1)
  - [Leo-FJ](https://github.com/Leo-FJ) (1)
  - [MaxPecc](https://github.com/MaxPecc) (1)
  - [jerji](https://github.com/jerji) (1)

Thanks to maintainers and others that helped with pull requests this month:

  - [Jellyfrog](https://github.com/Jellyfrog) (20)
  - [murrant](https://github.com/murrant) (16)
  - [PipoCanaja](https://github.com/PipoCanaja) (15)
  - [electrocret](https://github.com/electrocret) (12)
  - [craig-nokia](https://github.com/craig-nokia) (1)
  - [ottorei](https://github.com/ottorei) (1)

#### Device
* Ignore nameless health sensors for Fortigate ([#15678](https://github.com/librenms/librenms/pull/15678)) - [iliessens](https://github.com/iliessens)
* Add support for RoomAlert 32S device ([#15676](https://github.com/librenms/librenms/pull/15676)) - [sarcastic6](https://github.com/sarcastic6)
* Device - Add Cisco REP Segment state sensor ([#15666](https://github.com/librenms/librenms/pull/15666)) - [rudybroersma](https://github.com/rudybroersma)
* Added better support for some HiveOS Wireless devices ([#15661](https://github.com/librenms/librenms/pull/15661)) - [laf](https://github.com/laf)
* Fix HPE iLO CPU Status Sensor Description ([#15660](https://github.com/librenms/librenms/pull/15660)) - [mtentilucci](https://github.com/mtentilucci)
* Fix OcNOS detection for recent firmware versions ([#15642](https://github.com/librenms/librenms/pull/15642)) - [murrant](https://github.com/murrant)
* Add support for Fortinet FortiAPs ([#15641](https://github.com/librenms/librenms/pull/15641)) - [atj](https://github.com/atj)
* Fixing memory scale for datacom-dmos devices ([#15640](https://github.com/librenms/librenms/pull/15640)) - [lhwolfarth](https://github.com/lhwolfarth)
* Bug - Fix Cisco NTP values ([#15639](https://github.com/librenms/librenms/pull/15639)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add support for Forcepoint NGFW 6.10 and older ([#15632](https://github.com/librenms/librenms/pull/15632)) - [vhuk](https://github.com/vhuk)
* Bug - timos MPLS - more poller fixes ([#15624](https://github.com/librenms/librenms/pull/15624)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add memory readings for Draytek OS ([#15618](https://github.com/librenms/librenms/pull/15618)) - [Sweeny42](https://github.com/Sweeny42)
* Updated support for HiveOS Wireless newer models ([#15610](https://github.com/librenms/librenms/pull/15610)) - [laf](https://github.com/laf)
* Add HPE iLO 6 to discovery ([#15607](https://github.com/librenms/librenms/pull/15607)) - [jduke-halls](https://github.com/jduke-halls)
* Incorrect discovery APC Smart-UPS RT 3000 XL 4.1 ( APC Web/SNMP Management Card (AP9619 MB:v4.1.1 PF:v3.9.4) as multi-phase ups ([#15602](https://github.com/librenms/librenms/pull/15602)) - [pjordanovic](https://github.com/pjordanovic)
* Device - McAfee Web Gateway -\> SkyHigh Web Gateway ([#15596](https://github.com/librenms/librenms/pull/15596)) - [PipoCanaja](https://github.com/PipoCanaja)
* Add and extend support for Hirshmann devices ([#15588](https://github.com/librenms/librenms/pull/15588)) - [cguillaumie](https://github.com/cguillaumie)
* Updated regex for HWG STE2 r2 to better detect hardware and software version ([#15573](https://github.com/librenms/librenms/pull/15573)) - [luc-ass](https://github.com/luc-ass)
* Update entity-sensor.inc.php for xos' os ([#15552](https://github.com/librenms/librenms/pull/15552)) - [Leo-FJ](https://github.com/Leo-FJ)
* Added support of new OS for NTP/PTP systems: Meinberg OS, Safran (Orolia), Oscilloquartz (Adva) ([#15453](https://github.com/librenms/librenms/pull/15453)) - [MaxPecc](https://github.com/MaxPecc)
* Zhone health ([#15276](https://github.com/librenms/librenms/pull/15276)) - [jerji](https://github.com/jerji)
* Fix wrong ASN discovery on non-BGP Devices ([#14948](https://github.com/librenms/librenms/pull/14948)) - [Bierchermuesli](https://github.com/Bierchermuesli)

#### Webui
* Clarify In/Out on Ports table. ([#15680](https://github.com/librenms/librenms/pull/15680)) - [electrocret](https://github.com/electrocret)
* WebUI - Filter FDB and ARP tabs in port page if empty ([#15653](https://github.com/librenms/librenms/pull/15653)) - [PipoCanaja](https://github.com/PipoCanaja)
* Update Pushover.php ([#15652](https://github.com/librenms/librenms/pull/15652)) - [brianegge](https://github.com/brianegge)
* Mark old alert email settings as deprecated ([#15650](https://github.com/librenms/librenms/pull/15650)) - [murrant](https://github.com/murrant)
* Add bad port settings to webui ([#15649](https://github.com/librenms/librenms/pull/15649)) - [murrant](https://github.com/murrant)
* Bug - FDB Table - allow empty searchby as well ([#15626](https://github.com/librenms/librenms/pull/15626)) - [PipoCanaja](https://github.com/PipoCanaja)
* Update alertlog query to be more efficient ([#15622](https://github.com/librenms/librenms/pull/15622)) - [laf](https://github.com/laf)
* Add vendor to searchby rules function ([#15619](https://github.com/librenms/librenms/pull/15619)) - [bonzo81](https://github.com/bonzo81)
* Fix grabled characters when oid already UTF-8 ([#15615](https://github.com/librenms/librenms/pull/15615)) - [MittWillson](https://github.com/MittWillson)

#### Graphs
* Change default graph image to SVG ([#15586](https://github.com/librenms/librenms/pull/15586)) - [electrocret](https://github.com/electrocret)

#### Api
* API add_device: Add ping_ping fallback option ([#15637](https://github.com/librenms/librenms/pull/15637)) - [murrant](https://github.com/murrant)
* More filter options for the BGP peer API endpoint ([#15599](https://github.com/librenms/librenms/pull/15599)) - [Bierchermuesli](https://github.com/Bierchermuesli)

#### Discovery
* Set array before use to stop discovery erroring ([#15604](https://github.com/librenms/librenms/pull/15604)) - [laf](https://github.com/laf)

#### Authentication
* Add support for Okta Group claims to set Roles ([#15592](https://github.com/librenms/librenms/pull/15592)) - [peejaychilds](https://github.com/peejaychilds)
* Output Roles in auth_test script ([#15587](https://github.com/librenms/librenms/pull/15587)) - [peejaychilds](https://github.com/peejaychilds)

#### Bug
* Fix Rancid error messages ([#15683](https://github.com/librenms/librenms/pull/15683)) - [vhuk](https://github.com/vhuk)
* Fix smart application parsing ([#15672](https://github.com/librenms/librenms/pull/15672)) - [SourceDoctor](https://github.com/SourceDoctor)
* Fix pagination in alert rules page ([#15659](https://github.com/librenms/librenms/pull/15659)) - [tuxgasy](https://github.com/tuxgasy)
* Bug - "null" checks for SAR 7705 release 8.X ([#15657](https://github.com/librenms/librenms/pull/15657)) - [craig-nokia](https://github.com/craig-nokia)
* Bug - missing "use" statement in NTP Cisco ([#15656](https://github.com/librenms/librenms/pull/15656)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - TPLink - fix null exception for LLDP discovery WIP ([#15628](https://github.com/librenms/librenms/pull/15628)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - bgp-peers error in Timos -\> dbFacile cleanup ([#15620](https://github.com/librenms/librenms/pull/15620)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - ADSL ifIndex to port error not handled ([#15617](https://github.com/librenms/librenms/pull/15617)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - XDSL adslAtucCurrOutputPwr exception (Cisco CSCvj53634) ([#15614](https://github.com/librenms/librenms/pull/15614)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - null checks in Nokia MPLS polling ([#15613](https://github.com/librenms/librenms/pull/15613)) - [PipoCanaja](https://github.com/PipoCanaja)
* Bug - Nokia discovery protocols ([#15606](https://github.com/librenms/librenms/pull/15606)) - [PipoCanaja](https://github.com/PipoCanaja)
* Make vminfo.vmwVmGuestOS wider ([#15595](https://github.com/librenms/librenms/pull/15595)) - [TheMysteriousX](https://github.com/TheMysteriousX)
* Fixed state flag causing sql issues in test-template.php ([#15589](https://github.com/librenms/librenms/pull/15589)) - [laf](https://github.com/laf)

#### Documentation
* Add traceroute to the installed packages doc ([#15645](https://github.com/librenms/librenms/pull/15645)) - [VirTechSystems](https://github.com/VirTechSystems)
* Fix documentation formatting ([#15635](https://github.com/librenms/librenms/pull/15635)) - [Jellyfrog](https://github.com/Jellyfrog)
* Fix formatting in OAuth-SAML.md ([#15616](https://github.com/librenms/librenms/pull/15616)) - [peejaychilds](https://github.com/peejaychilds)
* Update Debian 12 Installation Instructions. ([#15590](https://github.com/librenms/librenms/pull/15590)) - [swiftnode-linden](https://github.com/swiftnode-linden)
* Add Debian 12 to install docs ([#15559](https://github.com/librenms/librenms/pull/15559)) - [VVelox](https://github.com/VVelox)

#### Misc
* Updating the logo to higher resolution one ([#15669](https://github.com/librenms/librenms/pull/15669)) - [altf4arnold](https://github.com/altf4arnold)
* Update the type of nummonbssid column in the access_points table ([#15647](https://github.com/librenms/librenms/pull/15647)) - [amyjohn000](https://github.com/amyjohn000)
* Fix device format missing display field ([#15623](https://github.com/librenms/librenms/pull/15623)) - [MittWillson](https://github.com/MittWillson)
* Link Model ([#15611](https://github.com/librenms/librenms/pull/15611)) - [murrant](https://github.com/murrant)
* Add space to Oxidized error msg ([#15603](https://github.com/librenms/librenms/pull/15603)) - [electrocret](https://github.com/electrocret)

#### Internal Features
* New utility Number::constrainInteger() ([#15663](https://github.com/librenms/librenms/pull/15663)) - [murrant](https://github.com/murrant)

#### Mibs
* Update MIKROTIK-MIB ([#15690](https://github.com/librenms/librenms/pull/15690)) - [netravnen](https://github.com/netravnen)

#### Dependencies
* Update javascript dependencies ([#15651](https://github.com/librenms/librenms/pull/15651)) - [murrant](https://github.com/murrant)
* Bump phpseclib/phpseclib from 3.0.21 to 3.0.34 ([#15600](https://github.com/librenms/librenms/pull/15600)) - [dependabot](https://github.com/apps/dependabot)

---

##[Old Changelogs](https://github.com/librenms/librenms/tree/master/doc/General/Changelogs)
