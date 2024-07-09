# Autoduty

This is an attempt at creating a community wiki.

Assume anything you see here is named incorrectly for Autoduty, or numbered incorrectly. 

Anything here is for testing and finalizing to confirm things working appropriately in preparation for a cleaner pull request towards Autoduty.

Autoduty works in conjunction with Bossmod AI and Navmesh. Certain dungeons do not have an AI module created, thus causing wipes and deaths for DPS.

This will be updated to the best of my abilities as things appear. So they are not lost to discord history.

Assume any files that have been uploaded here are duplicates or broken. (And working!)

I take zero credit for creating any paths that have been created here. 

They are made by community members willing to share their work. 

If a dungeon is not here, it has not been shared. 

This work is not my own.


# A Realm Reborn

(1036) Sastasha
```
[ "DutySpecificCode|347.75, 44.14, -223.21|1", "DutySpecificCode|90.26, 27.20, -56.04|2", "DutySpecificCode|63.56, 32.83, -31.59|3", "Boss|71.80, 30.37, -44.91|", "Interactable|63.56, 32.83, -31.59|Inconspicuous Switch", "Boss|-27.17, 22.86, 56.34|", "Interactable|-91.82, 13.84, 145.88|Captain\u0027s Quarters Key", "Interactable|-95.15, 19.9, 171.10|Captain\u0027s Quarters", "Interactable|-95.15, 20.01, 190.03|Waverider Gate Key", "Interactable|-130.04, 16.34, 156.07|Waverider Gate", "Boss|-183.12, 6.38, 244.52|", "Boss|-332.47, 5.57, 317.23|" ]
```

(1037) The Tam-Tara Deepcroft
```
["MoveTo|4.35, 41.04, -77.92|","Boss|2.82, 29.55, -17.25|","Interactable|-8.22, 30.83, -16.46|Cultist Orb","Boss|-18.43, 23.41, 26.77|","Interactable|-23.07, 24.71, 20.42|Cultist Orb","Interactable|-178.90, 13.91, -5.14|Cultist Rosary","Interactable|-104.14, 13.92, 15.52|Sealed Barrier","Boss|-93.34, 13.86, 9.51|","Interactable|-94.66, 14.91, 3.94|Cultist Orb","Interactable|-89.51, 14.90, 13.71|Cultist Orb","Boss|-51.88, 14.05, -12.76|"]
```
```
["MoveTo|4.35, 41.04, -77.92|","Boss|2.82, 29.55, -17.25|","Interactable|-8.22, 30.83, -16.46|Cultist Orb","Boss|-18.43, 23.41, 26.77|","Interactable|-23.07, 24.71, 20.42|Cultist Orb","MoveTo|-177.97, 13.49, -5.13|","Interactable|0, 0, 0|Cultist Rosary","Interactable|-104.14, 13.92, 15.52|Sealed Barrier","Boss|-93.34, 13.86, 9.51|","Interactable|-94.66, 14.91, 3.94|Cultist Orb","Interactable|-89.51, 14.90, 13.71|Cultist Orb","Boss|-51.88, 14.05, -12.76|"]
```

(1038) Copperbell Mines
```
[ "Target|-222.18, 23.85, -208.19|Copper", "ChatCommand|0, 0, 0|/ac \"Auto-attack\"", "Wait|0, 0, 0|2000", "WaitFor|0, 0, 0|Combat", "Wait|0, 0, 0|1000", "Interactable|-222.18, 23.85, -208.19|Tiny Key", "Interactable|-206.30, 23.47, -208.46|Sealed Blasting Door", "Interactable|-184.08, 24.00, -206.39|Lift Lever", "Wait|0, 0, 0|10000", "MoveTo|-178.09, -6.52, -208.07|", "Interactable|51.89, -8.75, -136.52|Firesand", "Interactable|52.93, -3.92, -153.77|Firesand", "Interactable|43.98, -9.75, -128.93|Powder Chamber", "Interactable|42.08, -9.98, -135.22|Blasting Device", "Wait|42.08, -9.98, -135.22|2000", "Boss|42.98, -9.92, -89.63|", "Interactable|42.97, -9.92, -69.18|Tiny Key", "Interactable|43.18, -9.92, -58.98|Sealed Blasting Door", "Interactable|56.69, -8.25, 5.91|Lift Lever", "Wait|0, 0, 0|10000", "MoveTo|58.27, -38.69, 11.74|", "Interactable|91.78, -42.19, 41.22|Firesand", "Interactable|21.70, -42.69, 42.35|Firesand", "Interactable|58.89, -38.75, 54.16|Powder Chamber", "Interactable|57.48, -38.74, 47.62|Blasting Device", "Wait|0, 0, 0|2000", "Interactable|38.07, -38.69, 60.38|Firesand", "Boss|27.61, -38.00, 113.91|", "Interactable|8.15, -38.00, 113.01|Firesand", "Interactable|1.84, -37.98, 113.05|Powder Chamber", "Interactable|4.85, -38.02, 110.96|Blasting Device", "Wait|0, 0, 0|2000", "Boss|-98.82, -57.88, 6.80|" ]
```
```
["Target|-222.18, 23.85, -208.19|Copper","ChatCommand|0, 0, 0|/ac \u0022Auto-attack\u0022","WaitFor|0, 0, 0|Combat","Wait|0, 0, 0|1000","Wait|0, 0, 0|2000","Interactable|-222.18, 23.85, -208.19|Tiny Key","Interactable|-206.30, 23.47, -208.46|Sealed Blasting Door","Interactable|-184.08, 24.00, -206.39|Lift Lever","Wait|0, 0, 0|10000","MoveTo|-178.09, -6.52, -208.07|","Interactable|51.89, -8.75, -136.52|Firesand","Interactable|52.93, -3.92, -153.77|Firesand","Interactable|43.98, -9.75, -128.93|Powder Chamber","Interactable|42.08, -9.98, -135.22|Blasting Device","Wait|42.08, -9.98, -135.22|2000","Boss|42.98, -9.92, -89.63|","Interactable|42.97, -9.92, -69.18|Tiny Key","Interactable|43.18, -9.92, -58.98|Sealed Blasting Door","Interactable|56.69, -8.25, 5.91|Lift Lever","Wait|0, 0, 0|10000","MoveTo|58.27, -38.69, 11.74|","Wait|92.73, -42.09, 39.41|2000","Interactable|91.78, -42.19, 41.22|Firesand","Wait|19.62, -42.42, 40.48|3000","Interactable|21.70, -42.69, 42.35|Firesand","Interactable|58.89, -38.75, 54.16|Powder Chamber","Interactable|57.48, -38.74, 47.62|Blasting Device","Interactable|38.07, -38.69, 60.38|Firesand","Boss|27.61, -38.00, 113.91|","Interactable|8.15, -38.00, 113.01|Firesand","Interactable|1.84, -37.98, 113.05|Powder Chamber","Interactable|4.85, -38.02, 110.96|Blasting Device","Wait|0, 0, 0|2000","Wait|0, 0, 0|2000","Boss|-98.82, -57.88, 6.80|"]
```
```
["Target|-222.18, 23.85, -208.19|Copper","ChatCommand|0, 0, 0|/ac \u0022Auto-attack\u0022","WaitFor|0, 0, 0|Combat","Wait|0, 0, 0|1000","Wait|0, 0, 0|2000","Interactable|-222.18, 23.85, -208.19|Tiny Key","Interactable|-206.30, 23.47, -208.46|Sealed Blasting Door","Interactable|-184.08, 24.00, -206.39|Lift Lever","Wait|0, 0, 0|10000","MoveTo|-178.09, -6.52, -208.07|","Interactable|51.89, -8.75, -136.52|Firesand","Interactable|52.93, -3.92, -153.77|Firesand","Interactable|43.98, -9.75, -128.93|Powder Chamber","Interactable|42.08, -9.98, -135.22|Blasting Device","Wait|42.08, -9.98, -135.22|2000","Boss|42.98, -9.92, -89.63|","Interactable|42.97, -9.92, -69.18|Tiny Key","Interactable|43.18, -9.92, -58.98|Sealed Blasting Door","MoveTo|60.90, -9.92, -26.57|","Interactable|56.69, -8.25, 5.91|Lift Lever","Wait|0, 0, 0|10000","MoveTo|58.27, -38.69, 11.74|","Wait|92.73, -42.09, 39.41|2000","Interactable|91.78, -42.19, 41.22|Firesand","Wait|19.62, -42.42, 40.48|3000","Interactable|21.70, -42.69, 42.35|Firesand","Interactable|58.89, -38.75, 54.16|Powder Chamber","Interactable|57.48, -38.74, 47.62|Blasting Device","Interactable|38.07, -38.69, 60.38|Firesand","Boss|27.61, -38.00, 113.91|","Interactable|8.15, -38.00, 113.01|Firesand","Interactable|1.84, -37.98, 113.05|Powder Chamber","Interactable|4.85, -38.02, 110.96|Blasting Device","Wait|0, 0, 0|2000","Wait|0, 0, 0|2000","Boss|-98.82, -57.88, 6.80|"]
```

(162) Halatali
```
["Boss|23.53, 0.93, 134.44|","ChatCommand|0,0,0|/vnav aligncamera ","MoveTo|24.14, 0.93, 137.81|","MoveTo|25.30, 0.93, 136.84|","ChatCommand|0,0,0|/automove on","ChatCommand|0,0,0|/gaction jump","Wait|0,0,0|1000","ChatCommand|0,0,0|/automove off","ChatCommand|0,0,0|/vnav aligncamera","Interactable|31.55, 2.00, 131.69|Aetherial Flow","Interactable|74.97, -11.15, -105.97|Chain Winch","Interactable|42.69, -11.04, -86.07|Chain Winch","MoveTo|-21.74, 0.19, -132.75|","ChatCommand|0,0,0|/vnav aligncamera ","MoveTo|-20.17, -1.74, -134.42|","ChatCommand|0,0,0|/automove on","Wait|0,0,0|1000","ChatCommand|0,0,0|/automove off","ChatCommand|0,0,0|/vnav aligncamera","Interactable|16.77, -10.97, -189.37|Chain Winch","Interactable|-37.10, -11.07, -128.60|Chain Winch","Interactable|-81.47, -11.00, -112.56|Chain Winch","Boss|-180.33, -15.31, -130.19|","Interactable|-177.62, -15.31, -133.61|Aetherial Flow","Boss|0,0,0|","Interactable|-172.77, 12.66, 12.70|Ludus Door","ChatCommand|-244.12, 17.23, 18.17|/vbmai off","Boss|-262.84, 17.23, 20.59|"]
```

(1039) The Thousand Maws of Toto-Rak
```
["Boss|-112.77, -4.13, 111.97|","Boss|-79.82, -8.13, -48.07|","Boss|222.07, -39.29, -144.12|"]
```

(1040) Haukke Manor
```
["Interactable|70.33, 0, 29.12|Tiny Key","Interactable|0.55, -2.14, 56.86|Locked Door","Interactable|-26.22, 0, 50.81|Tiny Key","Boss|7.83, 0, 0.06|","Interactable|0, 0, 0|Green Key","Interactable|-47.81, 0, -0.04|Ivy Door","Interactable|-1.87, -18.79, 34.30|Locked Door","Interactable|-12.14, -18.79, 51.88|Yellow Key","Interactable|-25.43, -18.79, 0|Carnation Door","Boss|14.58, -18.67, 0.05|","Wait|0, 0, 0|2000","Interactable|0, 0, 0|Bloody Parchment","Interactable|14.57, -18.68, -0.02|Aetherial Flow","Interactable|46.69, 9.87, -0.08|Sealed Barrier","Wait|22.76, 17, -0.24|5000","Boss|-10.65, 17, -0.01|"]
```
```
["Interactable|70.33, 0, 29.12|Tiny Key","Interactable|0.55, -2.14, 56.86|Locked Door","MoveTo|0.56, -0.00, 57.01|","Interactable|0.56, -0.00, 57.01|Locked Door","Interactable|-26.22, 0, 50.81|Tiny Key","Boss|7.83, 0, 0.06|","Interactable|0, 0, 0|Green Key","Interactable|-47.81, 0, -0.04|Ivy Door","Interactable|-11.26, -18.80, -50.04|Tiny Key","Interactable|-1.87, -18.79, 34.30|Locked Door","Interactable|-12.14, -18.79, 51.88|Yellow Key","Interactable|-25.43, -18.79, 0|Carnation Door","Boss|14.58, -18.67, 0.05|","Wait|0, 0, 0|5000","Interactable|0, 0, 0|Bloody Parchment","MoveTo|11.87, -18.80, 5.32|","Interactable|11.87, -18.80, 5.32|Bloody Parchment","Interactable|14.57, -18.68, -0.02|Aetherial Flow","Interactable|46.69, 9.87, -0.08|Sealed Barrier","Wait|22.76, 17, -0.24|5000","Boss|-10.65, 17, -0.01|"]
```

(1041) Brayflox's Longstop
```
["Interactable|21.82, 7.10, 27.40|Goblin Pathfinder","Interactable|105.56, -0.13, 12.14|Runstop Headgate","Boss|112.59, -2.44, -12.91|","Boss|-5.17, 5.74, -83.51|","Boss|-107.99, -2.38, -26.81|","Interactable|-90.04, 10.93, -95.78|Longstop Gutgate","Boss|-27.24, 35.5, -236.09|"]
```

The Sunken Temple of Qarn

Cutter's Cry

(1042) The Stone Vigil
```
["Boss|-0.05, 0.01, 116.13|","Boss|46.11, 4.00, -80.16|","Interactable|0.00, 4.00, -214.98|Strongroom Gate","Boss|0.05, 0.04, -247.95|"]
```

Dzemael Darkhold

(172) The Aurum Vale
```
["MoveTo|120.76, -9.31, 37.99|","MoveTo|110.63, -8.75, 39.70|","Wait|0, 0, 0|2000","MoveTo|86.21, -8.64, 34.64|","MoveTo|81.39, -7.51, 20.98|","MoveTo|62.93, -9.14, 6.80|","Boss|35.25, -9.34, 2.70|","Interactable|15.31, -10.07, -43.92|Morbol Fruit","Boss|-158.74, -30.50, -141.24|","MoveTo|-210.27, -26.01, -177.75|","MoveTo|-221.18, -25.74, -176.30|","MoveTo|-230.55, -26.72, -178.32|","MoveTo|-240.34, -26.37, -177.88|","MoveTo|-337.09, -32.16, -143.79|","MoveTo|-337.54, -33.03, -127.61|","Boss|-405.21, -33.46, -125.36|"]
```

(1043) Castrum Meridianum
```
["Boss|17.66, 70.17, -40.17|","Interactable|41.65, 71.25, -11.35|Disposal Chute","Boss|-12.56, 70.09, 34.26|","Boss|-97.93, 72, -33.13|"]
```

(1044) The Praetorium
```
["Interactable|196.74, 186.00, -5.11|Magitek Terminal","Interactable|172.81, 156.00, -25.49|Magitek Transporter","Boss|191.97, 76.00, 0.02|","Interactable|174.78, 76.00, 3.76|Magitek Terminal","DutySpecificCode|174.68, 102.00, -66.46|1","MoveTo|229.97, 64.39, 66.59|","Wait|83.61, -107.99, -31.14|5000","Target|83.61, -107.99, -31.14|Proto Ultima Arm Unit","Wait|51.00, -107.99, -72.18|2000","Target|51.00, -107.99, -72.18|Proto Ultima Arm Unit","Wait|-24.32, -104.00, 0.08|2000","Target|-65.00, -103.97, 0.24|Cermet Blast Door","DutySpecificCode|-83.86, -103.94, -0.08|2","Boss|-164.13, -104.40, -0.09|","Interactable|-238.41, -104.00, -19.20|Magitek Terminal","Boss|-562.17, -268.00, 220.06|"]
```
```
["MoveTo|176.10, 186.00, -18.58|","MoveTo|197.44, 186.00, -24.11|","Interactable|196.78, 186.00, -4.75|\u9B54\u5C0E\u30BF\u30FC\u30DF\u30CA\u30EB","Wait|0,0,0|1500","MoveTo|241.56, 154.84, -48.62|","MoveTo|188.13, 152.43, -79.54|","MoveTo|148.66, 154.44, -56.09|","Interactable|173.46, 156.00, -25.01|\u9B54\u5C0E\u30C8\u30E9\u30F3\u30B9\u30DD\u30FC\u30BF\u30FC","Wait|0,0,0|1500","Boss|192.98, 76.00, -0.08|","Interactable|174.63, 76.00, 3.66|\u9B54\u5C0E\u30BF\u30FC\u30DF\u30CA\u30EB","Wait|0,0,0|3000","MoveTo|175.10, 103.42, -91.13|","MoveTo|168.47, 100.35, -103.29|","MoveTo|97.62, 66.58, -13.64|","MoveTo|98.13, 66.38, 22.36|","MoveTo|169.91, 66.38, 93.91|","MoveTo|239.49, 66.98, 81.76|","MoveTo|231.28, 64.87, 66.68|","MoveTo|41.47, -107.40, -71.66|","MoveTo|12.70, -107.87, -70.33|","MoveTo|11.99, -106.94, -29.78|","MoveTo|12.33, -103.84, -0.79|","MoveTo|-27.22, -104.00, -0.92|","MoveTo|-66.55, -103.81, -0.02|","Interactable|-69.60, -103.81, -0.46|\u8D85\u786C\u30B5\u30FC\u30E1\u30C3\u30C8\u5BFE\u7206\u9694\u58C1","MoveTo|-84.42, -103.87, -0.45|","Boss|-162.17, -104.40, -0.27|","MoveTo|-222.22, -104.00, -1.93|","Interactable|-238.49, -104.00, -18.95|\u9B54\u5C0E\u30BF\u30FC\u30DF\u30CA\u30EB","Wait|-0,0,0|1000","Boss|-560.51, -268.00, 219.96|","Interactable|-779.06, -344.00, 0.08|\u8131\u51FA\u5730\u70B9"]
```
```
["MoveTo|200.91, 186.00, -18.81|","MoveTo|196.25, 186.00, -5.76|","Interactable|196.74, 186.00, -5.33|Magitek Terminal","Interactable|172.81, 156.00, -25.49|Magitek Transporter","Boss|191.97, 76.00, 0.02|","Interactable|174.78, 76.00, 3.76|Magitek Terminal","DutySpecificCode|174.68, 102.00, -66.46|1","MoveTo|230.78, 65.42, 67.5|","Wait|-24.32, -104.00, 0.08|2000","Target|-65.00, -103.97, 0.24|Cermet Blast Door","DutySpecificCode|-83.86, -103.94, -0.08|2","Boss|-164.13, -104.40, -0.09|","MoveTo|-211.25, -104.00, -0.44|","Interactable|-238.41, -104.00, -19.20|Magitek Terminal","Boss|-562.17, -268.00, 220.06|"]
```

The Wanderer's Palace

Amdapor Keep

Pharos Sirius

Copperbell Mines (Hard)

Haukke Manor (Hard)

The Lost City of Amdapor

Halatali (Hard)

(362) Brayflox's Longstop (Hard)
```
["Interactable|-3.68, -2.38, -5.96|Tiny Key","MoveTo|21.82, 7.10, 27.40|","MoveTo|64.63, 3.37, -7.75|","Interactable|105.56, -0.13, 12.14|Runstop Headgate","Boss|112.59, -2.44, -12.91|","MoveTo|89.52, 4.72, -100.15|","MoveTo|39.34, 5.90, -92.07|","MoveTo|34.50, 7.05, -125.09|","WaitFor|45.29, 7.02, -129.71|10000","MoveTo|44.67, 7.02, -131.59|","MoveTo|-41.32, 18.65, -119.77|","Interactable|94.96, 12.90, -122.70|Tiny Key","Interactable|-94.96, 12.90, -122.70|Swiftmake Checkgate","Interactable|-101.39, 20.74, -178.08|Tiny Key","Interactable|-101.76, 20.97, -186.69|Swiftmake Checkgate","Boss|-27.24, 35.5, -236.09|"]
```

Hullbreaker Isle

The Tam-Tara Deepcroft (Hard)

The Stone Vigil (Hard)

(1062) Snowcloak
```
["Interactable|71.93, 5.68, -44.44|Tiny Key","Interactable|55.74, 4.48, -46.58|Door to Silence","Boss|56.21, -2.50, -88.61|","Boss|-99.25, 10.50, -117.27|","Boss|-57.98, 28.40, -8.94|","Interactable|-71.10, 40.74, 65.24|Finger of the Apostate","Interactable|-51.00, 40.45, 64.94|Door to Oblivion","Boss|1.61, 40.07, 66.47|"]
```

(387) Sastasha (Hard)
```
["MoveTo|225.21, 40.06, -166.83|","MoveTo|188.06, 31.07, -25.83|","MoveTo|180.92, 32.95, -25.00|","Interactable|180.92, 32.95, -25.00|Drainage Pump","MoveTo|162.88, 13.92, -78.56|","Boss|162.94, 13.92, -78.76|","MoveTo|75.22, 14.19, -81.11|","MoveTo|-23.79, 12.19, -26.42|","MoveTo|-90.44, 7.38, 10.05|","MoveTo|-96.55, 15.45, 88.79|","Interactable|-96.55, 15.45, 88.79|Door to Dead Man\u0027s Drink","Boss|-102.73, 15.60, 122.99|","MoveTo|-107.01, 15.63, 137.60|","MoveTo|-162.72, 7.79, 183.02|","MoveTo|-182.02, 6.44, 248.98|","MoveTo|-289.47, 5.58, 267.48|","MoveTo|-312.54, 5.72, 309.92|","Boss|-312.54, 5.72, 309.92|"]
```

The Sunken Temple of Qarn (Hard)

(1063) The Keeper of the Lake
```
["Boss|18.66, 26.66, -17.03|","Wait|-12.55, 19.87, 0.05|2000","Interactable|-99.18, 329.47, -117.35|Imperial Identification Key","Interactable|-104.29, 329.10, -134.57|Magitek Terminal","MoveTo|-92.14, 338.62, -189.96|","MoveTo|-58.42, 338.34, -231.40|","Interactable|-58.42, 338.34, -231.40|Imperial Identification Key","Interactable|-33.73, 338.45, -201.01|Magitek Terminal","Boss|8.46, 346.02, -150.13|","Wait|7.02, 344.14, -112.82|2000","Wait|64.47, 608.26, -66.92|5000","Wait|-33.20, 638.24, -13.08|5000","Boss|-40.71, 641.04, -78.19|"]
```
```
["295.11136, 2.3483407, -151.5908","212.30943, 0.8723904, -106.01051","Wait|5000","165.59468, 5.1541157, -48.27684","161.26045, 5.471863, -40.774773","Wait|5000","164.77304, 5.146901, -47.98005","143.78868, 4.1165924, -39.83968","79.81876, 12.729249, -56.215054","Wait|5000","52.804844, 19.69826, -38.84805","16.13601, 26.628016, -15.234892","Boss|16.13601, 26.628016, -15.234892","12.686459, 26.668533, -16.096987","-0.48529375, 25.968586, -7.095806","-12.826353, 19.76488, -0.19067818","-100.614, 330.39816, -94.22878","-96.33697, 328.86478, -119.48783","Wait|5000","MoveToObject|Imperial Identification Key","Interactable|Imperial Identification Key","-104.69123, 329.09988, -134.82213","Interactable|Magitek Terminal","-98.387344, 329.0999, -132.65347","-98.66399, 333.84998, -150.8873","-122.47362, 338.6294, -150.85419","-111.35627, 338.7421, -164.8746","-95.69823, 338.61166, -173.85268","Wait|5000","-83.309044, 338.73236, -192.90518","-83.38446, 338.6219, -182.62679","-66.8497, 339.37894, -188.88374","-51.345333, 338.3606, -210.82307","Wait|5000","MoveToObject|Imperial Identification Key","Interactable|Imperial Identification Key","MoveToObject|Magitek Terminal","Interactable|Magitek Terminal","-38.916615, 338.27783, -208.5509","11.250461, 342.09818, -207.78284","9.643241, 346.0237, -162.36406","Boss|8.732609, 346.0237, -150.23384","9.177554, 346.0237, -135.18298","5.87831, 345.88342, -123.02076","6.4913063, 344.07587, -112.706604","64.34982, 596.3403, -113.4612","87.179146, 596.6038, -99.83239","83.55536, 600.53033, -86.212555","Wait|2000","68.803375, 606.531, -70.44663","Wait|2000","60.1182, 608.58124, -69.69179","42.72936, 614.5829, -47.857067","44.785336, 620.23376, -20.467966","22.919697, 626.2148, -19.182156","Wait|3000","22.574215, 626.2288, -20.019508","-29.674059, 637.6146, -9.883878","Wait|3000","-41.354164, 638.74817, -20.848434","-40.468258, 641.0469, -65.80406","Boss|-40.170887, 641.0593, -83.32377","-39.948494, 641.04767, -90.64508","ExitDuty|"]
```

Relies on Pandora Auto Interact option on

```
["295.11136, 2.3483407, -151.5908","212.30943, 0.8723904, -106.01051","Wait|5000","165.59468, 5.1541157, -48.27684","161.26045, 5.471863, -40.774773","Wait|5000","164.77304, 5.146901, -47.98005","143.78868, 4.1165924, -39.83968","79.81876, 12.729249, -56.215054","Wait|5000","52.804844, 19.69826, -38.84805","16.13601, 26.628016, -15.234892","Boss|16.13601, 26.628016, -15.234892","12.686459, 26.668533, -16.096987","-0.48529375, 25.968586, -7.095806","-12.826353, 19.76488, -0.19067818","-100.614, 330.39816, -94.22878","-96.33697, 328.86478, -119.48783","Wait|5000","MoveToObject|Imperial Identification Key","MoveToObject|Magitek Terminal","-98.387344, 329.0999, -132.65347","-98.66399, 333.84998, -150.8873","-122.47362, 338.6294, -150.85419","-111.35627, 338.7421, -164.8746","-95.69823, 338.61166, -173.85268","Wait|5000","-83.309044, 338.73236, -192.90518","-83.38446, 338.6219, -182.62679","-66.8497, 339.37894, -188.88374","-51.345333, 338.3606, -210.82307","Wait|5000","MoveToObject|Imperial Identification Key","MoveToObject|Magitek Terminal","-38.916615, 338.27783, -208.5509","11.250461, 342.09818, -207.78284","9.643241, 346.0237, -162.36406","Boss|8.732609, 346.0237, -150.23384","9.177554, 346.0237, -135.18298","5.87831, 345.88342, -123.02076","6.4913063, 344.07587, -112.706604","64.34982, 596.3403, -113.4612","87.179146, 596.6038, -99.83239","83.55536, 600.53033, -86.212555","Wait|2000","68.803375, 606.531, -70.44663","Wait|2000","60.1182, 608.58124, -69.69179","42.72936, 614.5829, -47.857067","44.785336, 620.23376, -20.467966","22.919697, 626.2148, -19.182156","Wait|3000","22.574215, 626.2288, -20.019508","-29.674059, 637.6146, -9.883878","Wait|3000","-41.354164, 638.74817, -20.848434","-40.468258, 641.0469, -65.80406","Boss|-40.170887, 641.0593, -83.32377","-39.948494, 641.04767, -90.64508","ExitDuty|"]
```

The Wanderer's Palace (Hard)

Amdapor Keep (Hard)

# A Realm Reborn Trials

(1048) The Porta Decumana
```
["Boss|-772.27, -400.06, -600.18|","Wait|-689.56, -185.73, 480.35|5000","Boss|-704.09, -185.66, 479.97|"]
```

# Heavensward

The Dusk Vigil

(1064) Sohm Al
```
["Boss|-125.32, 12.00, 166.79|","MoveTo|-91.34, 19.14, 123.99|","Wait|0, 0, 0|5000","Boss|158.88, 137.61, -91.59|","MoveTo|196.31, 140.77, -142.14|","Wait|0, 0, 0|5000","MoveTo|-90.99, 344.15, -358.78|","Wait|0, 0, 0|3000","MoveTo|-114.96, 344.22, -353.46|","Boss|-101.56, 348.15, -401.44|","Wait|0, 0, 0|10000"]
```
```
["Boss|-132.92, 12.00, 176.86|","MoveTo|-98.02, 18.01, 124.37|","MoveTo|-91.5, 19.5, 123.93|","MoveTo|279.77, 120.43, -95.68|","MoveTo|167.35, 135.61, -38.20|","Boss|160.14, 137.61, -78.23|","MoveTo|193.75, 140.02, -136.13|","MoveTo|196, 141, -142|","MoveTo|-212.22, 329.15, -292.08|","MoveTo|-88.54, 344.15, -358.79|","MoveTo|-90.08, 344.15, -360.40|","Boss|-106.10, 348.19, -387.05|"]
```

(1065) The Aery
```
["Boss|336.03, 94.00, -204.53|","MoveTo|290.71, 93.02, -175.11|","MoveTo|279.16, 91.38, -173.22|","MoveTo|224.79, 11.43, -164.67|","Boss|15.79, 60.00, 67.54|","MoveTo|-80.49, 92.95, -14.33|","MoveTo|-39.19, 109.96, -35.52|","MoveTo|-38.81, 108.16, -39.10|","MoveTo|85.12, 107.67, -49.41|","MoveTo|87.55, 109.71, -49.90|","Boss|34.63, 148.40, -263.18|"]
```

(1066) The Vault
```
["MoveTo|0.26, -299.98, -30.67|","Boss|-3.61, -291.94, -99.89|","MoveTo|105.60, -263.87, 0.02|","MoveTo|109.18, -263.98, -0.07|","Boss|-1.43, 0.00, 71.72|","MoveTo|-109.52, 0.13, -0.05|","MoveTo|-117.50, 0.09, 0.08|","Boss|0.04, 300.00, 2.99|"]
```
```
["Boss|-0.04, -291.94, -100.00|","MoveTo|74.65, -263.98, -31.55|","MoveTo|68.79, -263.98, -13.62|","MoveTo|96.58, -263.98, -0.02|","MoveTo|109.44, -263.87, -0.30|","Wait|60.12, -0.00, 59.93|10000","Boss|-0.08, 0.00, 71.76|","MoveTo|-11.22, 0.00, 72.03|","MoveTo|-78.67, 0.00, -14.27|","MoveTo|-113.83, 0.13, -0.12|","MoveTo|-115, 0.13, -0.12|","MoveTo|-59.91, 285.00, -18.38|","MoveTo|-60.32, 291.00, 53.62|","Boss|0.03, 300.00, 4.11|"]
```

(1109) The Great Gubal Library

Needs some manual input for the first boss

```
["Boss|-3.70, 0.00, -0.48|","MoveTo|74.57, -8.00, 71.08|","Wait|75.65, -8.00, 70.78|2000","Boss|177.79, -7.43, 29.85|","Boss|374.56, -39.00, -59.86|"]
```

(1110) The Aetherochemical Research Facility
```
["MoveTo|-263.93, 401.86, -297.87|","MoveTo|-176.08, 398.19, -372.48|","Boss|-109.84, 395.05, -295.64|","MoveTo|-47.49, 389.76, -246.70|","ChatCommand|-47.49, 389.76, -246.70|/automove on","MoveTo|29.79, 212.09, 218.02|","ChatCommand|29.86, 212.07, 218.06|/targetenemy","ChatCommand|29.86, 212.07, 218.06|/ac Auto-attack","MoveTo|110.17, 222.05, 270.08|","ChatCommand|110.17, 222.05, 270.08|/targetenemy","ChatCommand|110.17, 222.05, 270.08|/ac Auto-attack","Boss|247.25, 225.14, 271.92|","MoveTo|324.80, 222.20, 271.98|","ChatCommand|324.80, 222.20, 271.98|/automove on","Interactable|-352.73, -299.98, -250.01|Lift Terminal","Wait|-360.42, -299.98, -250.03|10000","Wait|-362.95, -299.98, -255.14|10000","MoveTo|-362.95, -299.98, -255.14|","ChatCommand|-362.95, -299.98, -255.14|/automove on","Wait|308.07, -27.92, 275.07|5000","MoveTo|266.00, -27.94, 236.83|","MoveTo|219.27, -27.97, 224.06|","Interactable|202.77, -28.16, 195.56|Lift Terminal","Wait|202.77, -58.16, 195.56|8000","MoveTo|201.85, -58.93, 124.45|","Interactable|228.77, -59.27, 95.07|Lift Terminal","Wait|228.77, -59.27, 95.07|8000","MoveTo|227.97, -90.16, 49.87|","ChatCommand|227.97, -90.16, 49.87|/automove on","Boss|230.03, -96.46, -182.83|","Boss|229.89, -456.46, 79.02|"]
```

Neverreap

The Fractal Continuum

Saint Mocianne's Arboretum

(510) Pharos Sirius (Hard)
```
["MoveTo|0.01, 139.86, -29.29|","MoveTo|-0.11, 93.54, -26.13|","MoveTo|0.63, 90.07, -1.65|","MoveTo|-1.89, 40.00, -25.15|","MoveTo|0.22, 30.00, -53.00|","Interactable|0.22, 30.00, -53.00|Candlekeep Key","MoveTo|14.42, 30.00, -55.71|","Interactable|14.42, 30.00, -55.71|Locked Door","Boss|49.97, 30.00, -56.95|","MoveTo|67.95, 13.47, -56.08|","MoveTo|-85.90, 3.07, -190.18|","Wait|0, 0, 0|5","MoveTo|-123.99, 2.13, -164.21|","Wait|0, 0, 0|5","MoveTo|-110.87, 2.77, -212.91|","Wait|0, 0, 0|5","MoveTo|-95.10, -3.15, -237.39|","MoveTo|-96.14, -5.55, -268.56|","Boss|-96.10, -5.50, -293.21|","MoveTo|-96.10, -5.50, -293.21|"]
```
(1111) The Antitower
```
["MoveTo|-315.29, 221.73, 132.58|","MoveTo|-352.40, 259.83, -3.28|","MoveTo|-365.04, 292.52, -136.48|","Boss|-365.27, 325.00, -249.25|","MoveTo|-364.80, 325.50, -277.04|","MoveTo|191.54, 8.00, 231.29|","MoveTo|193.26, 2.01, 189.65|","MoveTo|150.87, -4.00, 167.90|","MoveTo|132.86, -15.99, 136.65|","Boss|184.97, -21.99, 136.50|"]
```

The Lost City of Amdapor (Hard)

Sohr Khai

Hullbreaker Isle (Hard)

(1113) Xelphatol
```
["Boss|-70.55, 28.00, -76.76|","MoveTo|154.25, 55.72, -47.43|","Interactable|158.27, 55.81, -50.32|Bone Key","Interactable|167.79, 55.75, -59.74|Imposing Gate","MoveTo|185.00, 55.69, -62.64|","Interactable|179.39, 56.75, -76.91|Lift Lever","Boss|245.76, 113.43, 13.05|","MoveTo|300.40, 143.87, -156.30|","Interactable|300.41, 143.87, -156.70|Airstone","MoveTo|336.60, 144.00, -150.98|","Interactable|341.53, 144.83, -163.95|Tailwind Relic","MoveTo|343.21, 145.41, -165.37|","MoveTo|403.19, 151.20, -253.75|","Wait|421.80, 150.23, -265.76|5000","Interactable|421.80, 150.23, -265.76|Airstone","MoveTo|412.25, 152.20, -300.51|","Interactable|412.25, 152.20, -300.51|Tailwind Relic","Boss|315.88, 166.66, -416.69|"]
```

The Great Gubal Library (Hard)

(1114) Baelsar's Wall

Stops after the 2nd boss because the last boss is impossible without a vbm module

```
["MoveTo|-185.13, -3.02, -119.53|","MoveTo|-144.20, -3.00, -88.66|","MoveTo|-168.70, -4.26, -63.97|","Wait|-166.80, -4.43, -64.21|10000","Interactable|-164.73, -4.47, -63.39|Imperial Identification Key","MoveTo|-205.75, -0.90, -57.79|","Interactable|-206.13, 1.90, -49.77|Security Terminal","Wait|-186.99, 1.89, -14.73|10000","Interactable|-185.10, 1.99, -16.70|Imperial Identification Key","MoveTo|-184.31, 2.14, 17.29|","Interactable|-187.16, 2.00, 18.15|Security Terminal","Boss|-173.96, 2.93, 72.69|","MoveTo|-133.63, 2.00, 73.91|","MoveTo|-13.34, -300.06, -0.33|","Interactable|-0.44, -300.00, 0.11|Control Panel","Wait|-1.43, -300.00, 0.08|300000","MoveTo|21.45, -299.97, 2.63|","MoveTo|88.08, -299.99, 0.81|","Boss|115.74, -299.97, -0.07|"]
```
```
["Interactable|-144.61, -4.94, -61.41|Imperial Identification Key","Interactable|-206.19, 1.90, -49.76|Security Terminal","Interactable|-191.11, 2.05, -18.15|Imperial Identification Key","Interactable|-186.96, 2.00, 18.15|Security Terminal","Boss|-174.02, 2.93, 73.77|","MoveTo|-136.64, 2.19, 73.03|","MoveTo|-134.00, 2.00, 73.04|","MoveTo|-13.44, -300.00, 13.17|","Interactable|-0.14, -300.00, 0.01|Control Panel","Wait|-0.14, -300.00, 0.01|10000","MoveTo|78.75, -299.84, 0.07|","Boss|117.45, -299.97, -0.11|","MoveTo|173.31, -299.18, -0.07|","MoveTo|175.94, -299.11, -0.07|","MoveTo|312.12, 168.98, 216.69|","Interactable|323.93, 168.84, 230.25|Imperial Identification Key","Interactable|320.95, 168.98, 243.09|Security Terminal","MoveTo|363.90, 203.00, 274.87|","MoveTo|384.87, 203.00, 332.35|","Boss|351.76, 212.00, 391.90|"]
```

Sohm Al (Hard)

# Heavensward Trials

# Stormblood

(1142) The Sirensong Sea
```
["4.183116, 16.372252, -416.25458","Wait|10000","0.043876395, 19.546753, -404.36078","0.0046891933, 29.453064, -379.5285","0.33962843, 19.890318, -370.6207","-20.123125, 6.493764, -340.8351","26.655516, 1.1919692, -294.39825","3.1567967, 2.7037718, -270.38876","-1.5786877, 2.8979619, -231.92506","Boss|-2.6846673, 2.9008512, -217.87889","-2.7677956, 2.9013357, -206.9862","TreasureCoffer|","2.9810126, 6.0421534, -98.03291","TreasureCoffer|","-71.03072, 14.457488, -30.080917","-83.927635, 12.484684, -29.361637","TreasureCoffer|","-58.48932, 21.081543, 9.833426","-56.646023, 18.35015, 14.176385","-22.42249, 16.352032, 20.006466","-10.048519, 7.7421446, 41.364223","-3.0033436, 4.433958, 62.52571","Boss|-7.61568, 4.440488, 83.50827","-7.9839616, 4.4466085, 88.57109","TreasureCoffer|","23.178974, -3.6826231, 225.95232","TreasureCoffer|","-25.384089, 9.750103, 349.2026","TreasureCoffer|","-44.121128, 5.8659496, 378.7256","Boss|-44.403072, 5.9980106, 391.04843","-44.57437, 7.751198, 441.86826","Boss|-44.189034, 7.751197, 464.47272","-44.494827, 7.751196, 472.98242","TreasureCoffer|","ExitDuty|"]
```
```
["Wait|5.35, 16.34, -426.29|10000","Wait|5.22, 16.34, -421.52|10000","Boss|-2.68, 2.90, -217.87|","MoveTo|2.81, 5.51, -113.69|","MoveTo|-71.03, 14.45, -30.08|","MoveTo|-74.17, 12.74, -28.65|","MoveTo|-58.48, 21.08, 9.83|","MoveTo|-56.64, 18.35, 14.17|","Boss|-7.61, 4.44, 83.50|","Boss|-44.18, 7.75, 464.47|"]
```
```
["Wait|5.35, 16.34, -426.29|10000","Wait|5.22, 16.34, -421.52|10000","Boss|-2.68, 2.90, -217.87|","MoveTo|2.81, 5.51, -113.69|","MoveTo|-67.06, 12.83, -38.99|","MoveTo|-72.73, 12.80, -29.27|","MoveTo|-58.48, 21.08, 9.83|","MoveTo|-56.64, 18.35, 14.17|","Boss|-7.61, 4.44, 83.50|","Boss|-44.18, 7.75, 464.47|"]
```

Shisui of the Violet Tides

(1143) Bardam's Mettle
```
["Boss|3.42, -0.50, 242.52|","MoveTo|3.87, -0.50, 229.99|","MoveTo|4.07, -0.32, 215.70|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|3000","ChatCommand|0, 0, 0|/automove off","MoveTo|-25.52, -32.15, 186.01|","MoveTo|-30.10, -44.18, 85.56|","MoveTo|-28.89, -45.00, -15.13|","Boss|-28.15, -45.00, -24.90|","MoveTo|-28.12, -45.00, -28.23|","MoveTo|-28.00, -45.40, -39.69|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|15000","ChatCommand|0, 0, 0|/automove off","MoveTo|-48.59, -163.02, -159.63|","MoveTo|-48.68, -162.77, -170.65|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|3500","ChatCommand|0, 0, 0|/automove off","MoveTo|-5.48, -185.75, -267.53|","MoveTo|24.49, -173.03, -385.83|","MoveTo|36.69, -172.68, -397.18|","MoveTo|24.20, -167.40, -452.65|","Boss|23.73, -167.60, -481.06|","MoveTo|23.94, -167.50, -483.28|"]
```

(1144) Doma Castle
```
["Boss|126.05, 40.57, 17.44|","Boss|-233.89, 45.49, 130.58|","Boss|-239.86, 67, -196.72|"]
```
```
["MoveTo|297.27, 24.75, 57.15|","MoveTo|301.85, 24.75, -6.34|","Boss|126.05, 40.57, 17.44|","Boss|-233.89, 45.49, 130.58|","Boss|-239.86, 67, -196.72|"]
```

(1145) Castrum Abania
```
["MoveTo|-429.22, -16.00, 294.30|","MoveTo|-378.71, -10.00, 243.85|","MoveTo|-337.09, -8.25, 202.81|","MoveTo|-337.70, -8.25, 164.74|","MoveTo|-297.97, -6.00, 124.92|","MoveTo|-230.24, -6.42, 58.27|","MoveTo|-212.85, -6.49, 79.51|","MoveTo|-213.16, -1.99, 188.57|","Boss|-212.36, -1.99, 190.71|","MoveTo|-213.08, -0.02, 247.16|","MoveTo|-178.62, 2.03, 280.31|","MoveTo|-147.89, 3.98, 310.80|","MoveTo|-101.46, 6.00, 311.28|","MoveTo|-54.34, 7.99, 310.78|","MoveTo|-32.58, 10.00, 279.38|","MoveTo|-20.90, 10.00, 278.14|","MoveTo|9.75, 11.99, 243.34|","MoveTo|0.02, 14.04, 186.56|"]
```
```
["MoveTo|-378.74, -10.00, 244.05|","MoveTo|-297.94, -6.00, 125.10|","MoveTo|-223.72, -6.42, 60.01|","Wait|0, 0, 0|2000","Boss|-213.02, -1.99, 189.93|","MoveTo|-212.91, -2.00, 204.69|","MoveTo|-167.76, 2.00, 275.88|","MoveTo|-101.64, 6.00, 311.02|","MoveTo|-101.56, 5.96, 282.46|","MoveTo|-3.48, 9.96, 297.11|","MoveTo|-25.87, 10.00, 265.96|","Boss|10.71, 14.07, 184.71|","MoveTo|28.33, 14.00, 186.25|","MoveTo|154.34, 20.05, 101.33|","MoveTo|177.60, 20.10, 86.58|","MoveTo|205.05, 20.05, 50.14|","MoveTo|272.13, 20.00, 55.66|","Boss|283.93, 20.04, -31.54|","MoveTo|285.78, 19.98, -39.86|"]
```

(1146) Ala Mhigo
```
["MoveTo|-342.11, 24.00, 151.78|","Wait|0, 0, 0|3750","MoveTo|-259.76, 27.00, 96.80|","MoveTo|-250.95, 27.00, 94.46|","MoveTo|-245.31, 31.00, 70.83|","Boss|-187.03, 34.87, 71.86|","MoveTo|-178.53, 34.87, 71.80|","MoveTo|-155.86, 34.87, 71.93|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|6500","MoveTo|255.71, 96.62, 66.22|","MoveTo|263.93, 106.40, -8.65|","MoveTo|281.94, 106.40, -24.08|","Boss|249.99, 106.45, -74.51|","MoveTo|250.00, 106.45, -85.17|","MoveTo|234.48, 110.00, -149.57|","MoveTo|134.20, 116.00, -212.37|","MoveTo|218.20, 120.00, -247.72|","MoveTo|282.11, 120.00, -264.05|","MoveTo|250.12, 122.00, -330.37|","Boss|250.02, 122.00, -357.45|","MoveTo|250.06, 122.00, -365.24|"]
```

Kugane Castle

The Temple of the Fist

The Drowned City of Skalla

Hells' Lid

The Fractal Continuum (Hard)

The Swallow's Compass

The Burn

Saint Mocianne's Arboretum (Hard)

The Ghimlyt Dark

# Stormblood Trials

# Shadowbringers

(837) Holminster Switch
```
["Boss|-14.34, 0, 237.75|","Boss|78.16, 0, -84.24|","Boss|133.05, 23, -459.12|"]
```

(821) Dohn Mheg
```
["MoveTo|-55.97, 8.13, 133.73|","MoveTo|-27.94, 8.10, 176.66|","MoveTo|54.17, 8.36, 134.92|","MoveTo|28.02, 8.28, 85.26|","Boss|-0.59, 6.85, 25.03|","MoveTo|-3.28, 0.62, -54.08|","MoveTo|-42.89, 1.87, -94.30|","MoveTo|-54.00, 1.77, -104.84|","MoveTo|-71.71, 16.37, -185.48|","MoveTo|-14.25, 12.40, -229.13|","MoveTo|5.48, 12.34, -233.65|","Boss|6.93, 23.10, -346.52|","MoveTo|7.92, 19.30, -452.47|","MoveTo|-176.77, -182.75, 32.24|","Interactable|-169.76, -178.75, -5.61|Shell Crown","MoveTo|-170.02, -167.49, -66.32|","MoveTo|-129.05, -167.75, -70.82|","MoveTo|-128.54, -167.49, -102.81|","MoveTo|-120.14, -156.01, -169.03|","Boss|-128.44, -144.54, -250.21|"]
```

(823) The Qitana Ravel
```
["Boss|0.10, -0.00, 640.07|","Boss|-0.00, 2.00, 432.30|","Boss|0.17, 5.35, 314.78|","Boss|62.64, -21.00, -34.68|","MoveTo|35.62, -70.15, -223.83|","MoveTo|17.62, -56.61, -428.52|","Boss|17.05, -77.00, -537.73|"]
```
```
["Boss|0.10, -0.00, 640.07|","RandomPull|6.13, 0.04, 510.64|","Boss|-0.00, 2.00, 432.30|","Boss|0.17, 5.35, 314.78|","TreasureCoffer|133.56, -8.57, 186.15|","TreasureCoffer|49.08, -11.00, 79.51|","Boss|62.64, -21.00, -34.68|","MoveTo|35.62, -70.15, -223.83|","TreasureCoffer|41.53, -60.00, -301.09|","MoveTo|14.75, -60.00, -337.56|","TreasureCoffer|-7.70, -57.00, -423.63|","MoveTo|17.22, -56.39, -420.77|","MoveTo|16.95, -58.51, -437.27|","Wait|0, 0, 0|10000","Boss|17.05, -77.00, -537.73|"]
```
```
["Boss|0.10, -0.00, 640.07|","Boss|-0.00, 2.00, 432.30|","Boss|0.17, 5.35, 314.78|","Boss|62.64, -21.00, -34.68|","MoveTo|16.95, -77.00, -521.10|","Boss|17.05, -77.00, -537.73|"]
```
```
["Boss|0.10, -0.00, 640.07|","Boss|-0.00, 2.00, 432.30|","Boss|0.17, 5.35, 314.78|","Boss|62.64, -21.00, -34.68|","MoveTo|16.80, -59.43, -438.25|","MoveTo|16.95, -77.00, -521.10|","Boss|17.05, -77.00, -537.73|"]
```

(836) Malikah's Well
```
["54.63291, 120.04448, 140.47295","24.553526, 120, 83.296455","-8.619109, 119.88, 39.103924","70.61039, 119.96999, -22.077547","119.754776, 119.79353, -92.94787","Wait|5000","Boss|278.19232, 16.99999, 203.73335","278.9439, 16.99999, 192.78336","TreasureCoffer|","202.1159, 12.0202875, 117.355194","196.27237, 12.0031595, 169.54373","156.58664, -10, 212.94595","149.55057, -9.77957, 230.38379","TreasureCoffer|","109.439316, -15.642281, 231.83002","130.83908, -20.101208, 276.4577","134.08733, -20.006788, 295.15488","TreasureCoffer|","144.56761, -20.000017, 289.00745","157.47504, -80.62904, 301.74847","Boss|207.8357, -86.00001, 272.62924","206.6569, -86.00001, 260.55807","TreasureCoffer|","213.57143, -83.99991, 208.4526","198.46141, -83.99991, 174.2193","205.79143, -83.99883, 123.7838","TreasureCoffer|","171.60432, -84.17387, 96.002174","191.02234, -80.20301, 39.323757","206.54454, -79.9999, 34.87955","TreasureCoffer|","200.26344, -69.611336, -28.638481","Boss|195.96968, -93.3999, -98.591","196.00066, -93.3999, -105.585075","TreasureCoffer|","ExitDuty|"]
```

(822) Mt. Gulg
```
["304.8271, -78.60709, 77.899025","337.63907, -82.03888, 7.3534465","337.55545, -76.84974, -42.038593","344.3003, -59.91755, -141.13329","312.6997, -53.77352, -163.42107","Boss|185.26382, -48.000004, -170.35974","170.22514, -48, -169.95364","TreasureCoffer|","101.66689, -46.661625, -199.22783","-4.5072765, -31, -196.24428","-38.17845, -23.52053, -198.61458","Wait|5000","-85.09147, 174.8378, -233.6684","-130.14206, 192.42393, -178.28888","-199.4669, 202.04999, -108.73894","-239.2851, 201.99959, -98.554276","TreasureCoffer|","Boss|-239.98972, 210, -46.359756","-240.1165, 210, -39.97446","TreasureCoffer|","-288.28586, 194, 41.170097","-288.12585, 194, 86.62224","TreasureCoffer|","-191.51337, 194, 99.35413","-253.9688, 202, 139.79968","TreasureCoffer|","-240.62009, 204.3701, 166.2764","-240.08275, 204.3701, 183.21916", "Wait|5000", "Boss|-239.76259, 210, 242.16539","-240.2041, 210, 246.0468","TreasureCoffer|","ExitDuty|"]
```

(838) Amaurot
```
["MoveTo|-0.11, 750.00, 342.57|","MoveTo|-60.32, 744.96, 151.43|","Boss|-80.35, 748.23, 81.87|","MoveTo|-76.50, 729.00, -98.63|","MoveTo|72.40, 729.66, -156.97|","MoveTo|58.35, 729.27, -205.24|","Boss|60.01, 728.00, -360.71|","Interactable|60.13, 728.00, -364.57|Aetherial Flow","MoveTo|-0.02, -740.08, 326.99|","Wait|0, 0, 0|3000","MoveTo|-0.06, -730.11, 176.95|","Wait|0, 0, 0|3000","MoveTo|-0.06, -732.16, 42.87|","Wait|0, 0, 0|3000","Boss|0.09, -720.00, -64.39|"]
```

The Twinning

Akadaemia Anyder

(884) The Grand Cosmos
```
["Boss|-0.11, 0.00, 186.82|","Boss|-0.24, -12.50, -69.54|","Boss|0.10, 8.00, -340.17|"]
```

(898) Anamnesis Anyder
```
["MoveTo|-97.24, 103.60, 373.24|","Wait|0, 0, 0|5000","MoveTo|-89.59, 103.59, 370.73|","MoveTo|-86.42, 103.42, 369.15|","Boss|-41.20, 95.00, 289.25|","Boss|19.82, 110.00, -81.68|","MoveTo|19.96, 90.80, -325.24|","Wait|0, 0, 0|5000","Boss|0.30, -200.00, -449.94|"]
```

(916) The Heroes' Gauntlet
```
["Boss|-679.60, -24.00, 443.89|","Wait|-679.83, -24.00, 443.25|5000","Interactable|-679.60, -24.00, 443.89|Fae Portal","Boss|-442.71, 0.00, -531.56|","MoveTo|-396.31, 0.89, -523.88|","MoveTo|524.47, 6.40, 498.98|","Boss|749.86, 8.00, 477.91|"]
```

(933) Matoya's Relict
```
["Wait|3.85, 8.50, 62.93|2000","Interactable|3.82, 8.50, 65.52|Earthy Portal","Wait|-211.68, -211.95, 31.25|5000","Wait|-180.21, -219.99, -77.07|5000","Boss|-179.55, -220.00, -150.35|","Wait|-179.55, -220.00, -150.17|2000","Interactable|-179.55, -220.00, -150.35|Interstice Portal","Wait|8.42, 8.50, 63.43|2000","Interactable|8.17, 8.50, 64.88|Watery Portal","MoveTo|55.72, 234.00, -181.34|","MoveTo|51.05, 220.00, -147.67|","MoveTo|33.27, 202.00, -104.66|","MoveTo|-2.19, 198.00, -153.72|","Wait|-17.82, 198.00, -180.80|","Wait|0, 0, 0|3000","MoveTo|-32.32, 202.00, -198.24|","MoveTo|-53.81, 202.00, -149.06|","MoveTo|-43.14, 188.00, -122.22|","MoveTo|-28.42, 169.90, -106.78|","MoveTo|-1.82, 169.90, -107.64|","Wait|0, 0, 0|3000","Boss|0.03, 150.00, -158.73|","Wait|-0.18, 150.00, -156.28|2000","Interactable|0.03, 150.00, -158.73|Interstice Portal","Wait|11.76, 8.50, 63.71|2000","Interactable|12.65, 8.50, 65.08|Fiery Portal","MoveTo|196.00, -598.34, 74.26|","Wait|161.50, -592.55, -149.47|10000","Interactable|160.60, -592.55, -148.55|Interstice Portal","Boss|0.16, 0.00, -10.22|"]
```

(938) Paglth'an
```
["Boss|-515.19, -0.03, 145.02|","Boss|-174.80, -25.00, 40.30|","Wait|-73.01, -25.17, -23.04|5000","Interactable|-73.01, -25.17, -23.04|Dragon","Wait|0, 0, 0|10000","Boss|798.45, -57.00, -97.25|"]
```
```
["Boss|-515.19, -0.03, 145.02|","Boss|-174.80, -25.00, 40.30|","Wait|-73.01, -25.17, -23.04|5000","Interactable|-73.01, -25.17, -23.04|Dragon","Wait|0, 0, 0|10000","Boss|798.45, -57.00, -97.25|","Wait|0, 0, 0|10000","MoveTo|798.50, -57.00, -98.38|"]
```

# Shadowbringers Trials

# Endwalker

(952) The Tower of Zot
```
["Boss|68.40, -442.97, -124.13|","MoveTo|61.97, -441.62, -183.75|","Boss|-257.53, -169.00, -27.28|","MoveTo|-263.15, -166.50, -91.89|","Boss|-28.70, 546.10, -48.30|"]
```
```
["Boss|68.40, -442.97, -124.13|","MoveTo|68.10, -442.97, -136.80|","MoveTo|66.77, -443.47, -170.92|","MoveTo|64.31, -443.36, -175.86|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|3000","MoveTo|-299.43, -184.96, 178.24|","MoveTo|-339.02, -180.98, 95.37|","MoveTo|-342.80, -180.83, 77.40|","MoveTo|-332.30, -181.01, 83.84|","MoveTo|-237.93, -171.85, 78.03|","MoveTo|-225.84, -171.83, 65.63|","MoveTo|-236.98, -172.05, 63.94|","Boss|-257.53, -169.00, -27.28|","MoveTo|-257.58, -169.00, -40.07|","MoveTo|-258.19, -167.92, -82.90|","MoveTo|-262.20, -167.75, -88.32|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|4000","Wait|0, 0, 0|5000","MoveTo|22.90, 535.60, -38.08|","MoveTo|39.99, 539.11, -100.02|","MoveTo|22.01, 538.33, -101.87|","Boss|-28.70, 546.10, -48.30|","MoveTo|-23.98, 546.10, -52.85|"]
```
```
["Boss|68.40, -442.97, -124.13|","MoveTo|68.10, -442.97, -136.80|","MoveTo|66.77, -443.47, -170.92|","MoveTo|64.31, -443.36, -175.86|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|3000","MoveTo|-299.43, -184.96, 178.24|","MoveTo|-339.02, -180.98, 95.37|","MoveTo|-342.80, -180.83, 77.40|","MoveTo|-332.30, -181.01, 83.84|","MoveTo|-237.93, -171.85, 78.03|","MoveTo|-225.84, -171.83, 65.63|","MoveTo|-236.98, -172.05, 63.94|","Boss|-257.53, -169.00, -27.28|","MoveTo|-257.58, -169.00, -40.07|","MoveTo|-258.19, -167.92, -82.90|","MoveTo|-262.20, -167.75, -88.32|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|4000","Wait|0, 0, 0|5000","MoveTo|0.08, 539.88, 47.14|","MoveTo|0.86, 534.74, 3.09|","MoveTo|29.56, 534.82, -29.66|","MoveTo|22.90, 535.60, -38.08|","MoveTo|39.99, 539.11, -100.02|","MoveTo|22.01, 538.33, -101.87|","Boss|-28.70, 546.10, -48.30|","MoveTo|-23.98, 546.10, -52.85|"]
```

(969) The Tower of Babil
```
["MoveTo|-268.08, -180.36, 322.30|","Wait|0, 0, 0|8000","MoveTo|-266.94, -180.50, 277.99|","MoveTo|-258.99, -200.00, 238.95|","Boss|-300.52, -175.00, 76.47|","MoveTo|-300.18, -175.00, 22.71|","Wait|0, 0, 0|7000","Interactable|400.17, 0.00, -174.92|Control Terminal","Wait|0, 0, 0|9000","Wait|0, 0, 0|10000","Wait|0, 0, 0|13000","Wait|0, 0, 0|8500","MoveTo|400.06, -0.00, -152.91|","Wait|0, 0, 0|5000","Boss|221.08, 1.00, 305.94|","MoveTo|152.00, 0.00, 199.34|","Wait|0, 0, 0|4500","Interactable|0.44, 500.00, 1.13|Control Terminal","Wait|0, 0, 0|14000","MoveTo|0.04, 493.00, -53.90|","MoveTo|21.70, 490.20, -54.08|","MoveTo|30.77, 487.51, -74.29|","MoveTo|-19.83, 487.00, -85.83|","MoveTo|-32.12, 484.51, -106.29|","Boss|0.00, 480.00, -180.31|"]
```

(970) Vanaspati
```
["MoveTo|-205.43, 15.48, 271.22|","Wait|0, 0, 0|5000","Boss|-375.01, 14.50, 81.24|","MoveTo|-330.68, 41.00, -146.37|","Wait|0, 0, 0|8000","Boss|-295.17, 41.50, -347.53|","MoveTo|-295.60, 44.40, -409.07|","Wait|0, 0, 0|2000","MoveTo|290.05, 56.79, -9.06|","MoveTo|309.66, 57.80, -66.89|","Boss|300.11, 55.01, -157.43|","MoveTo|299.47, 55.01, -169.85|"]
```

(974) Ktisis Hyperboreia
```
["Boss|-143.51, 496.00, 47.23|","MoveTo|-132.80, 501.52, 3.36|","Boss|0.37, 630.00, 48.82|","MoveTo|-0.23, 631.19, -10.95|","Wait|0, 0, 0|2000","MoveTo|0.64, -699.74, 1.33|","Wait|0, 0, 0|5000","MoveTo|29.47, -599.74, -71.00|","Wait|0, 0, 0|10000","MoveTo|-35.11, -138.83, -8.47|","Wait|0, 0, 0|5000","Boss|0.06, 0.00, -53.24|","MoveTo|1.14, 0.00, -59.84|"]
```
```
["Boss|-143.51, 496.00, 47.23|","MoveTo|-132.80, 501.52, 3.36|","Boss|0.37, 630.00, 48.82|","MoveTo|-0.23, 631.19, -10.95|","Wait|0, 0, 0|2000","MoveTo|0.64, -699.74, 1.33|","Wait|0, 0, 0|5000","MoveTo|19.94, -600.00, -45.01|","MoveTo|28.94, -599.74, -70.95|","Wait|0, 0, 0|13000","MoveTo|-35.11, -138.83, -8.47|","Wait|0, 0, 0|5000","Boss|0.06, 0.00, -53.24|","MoveTo|1.14, 0.00, -59.84|"]
```

(978) The Aitiascope
```
["Boss|-5.89, 164.00, 471.86|","Interactable|-6.34, 164.00, 468.71|Aether Current","Wait|0, 0, 0|5000","MoveTo|9.19, -182.78, 441.20|","MoveTo|-0.70, -202.18, 321.55|","Wait|0, 0, 0|5000","Boss|10.36, -211.41, 143.21|","MoveTo|12.40, -211.13, 86.98|","Wait|0, 0, 0|5000","Boss|10.85, -236.00, -494.57|"]
```

(973) The Dead Ends
```
["MoveTo|401.82, 500.36, 134.83|","Boss|266.62, 501.01, -176.87|","Interactable|266.59, 500.40, -217.88|Spatial Distortion","Wait|0, 0, 0|6000","Boss|-104.99, 0.20, -205.90|","MoveTo|-107.66, -8.00, -284.57|","Wait|0, 0, 0|10000","Interactable|-107.66, -8.00, -284.57|Spatial Distortion","Wait|0, 0, 0|6300","MoveTo|-296.68, -610.15, 109.96|","Wait|0, 0, 0|5000","Boss|-380.39, -577.00, -132.68|"]
```

Smileton

The Stigma Dreamscape

(1050) Alzadaal's Legacy
```
["Boss|124.01, 303.00, -90.50|","Interactable|123.99, 305.60, -146.17|Salt-encrusted Teleporter","Wait|0, 0, 0|12000","MoveTo|-0.10, -7.90, -135.84|","Wait|0, 0, 0|2000","Boss|-0.11, -16.00, -182.38|","MoveTo|-0.03, -19.86, -247.31|","Wait|0, 0, 0|8000","Boss|109.94, -350.00, -67.31|"]
```

(1070) The Fell Court of Troia
```
["Boss|168.15, -700.00, 84.49|","MoveTo|268.00, -707.99, 90.01|","Wait|0, 0, 0|5000","Boss|0.14, -698.01, -149.65|","Wait|0, 0, 0|10000","MoveTo|-11.72, -682.19, -248.81|","Wait|0, 0, 0|6000","MoveTo|-35.68, 386.55, -242.09|","Wait|0, 0, 0|2000","Boss|-34.92, 385.00, -297.19|"]
```

(1097) Lapis Manalis
```
["MoveTo|46.94, 366.00, -576.15|","Wait|0, 0, 0|5000","MoveTo|45.84, 365.97, -585.71|","Boss|23.83, 386.06, -742.13|","MoveTo|-19.62, 398.27, -824.27|","Wait|0, 0, 0|4000","Boss|349.88, 34.00, -393.96|","MoveTo|342.74, 30.35, -463.19|","Wait|0, 0, 0|10000","Boss|-249.97, -173.00, 127.27|"]
```
```
["MoveTo|46.94, 366.00, -576.15|","Wait|0, 0, 0|5000","MoveTo|50.62, 365.49, -589.68|","MoveTo|-21.39, 390.37, -666.10|","MoveTo|26.97, 386.02, -687.94|","Boss|23.98, 386.02, -740.32|","MoveTo|-17.62, 398.30, -823.82|","MoveTo|305.89, 67.70, -168.14|","MoveTo|339.87, 53.98, -222.69|","MoveTo|344.34, 42.40, -291.33|","Wait|0, 0, 0|3000","MoveTo|386.78, 38.71, -284.64|","MoveTo|351.43, 34.03, -334.37|","MoveTo|341.31, 34.26, -335.94|","Wait|0, 0, 0|3000","Boss|349.69, 34.00, -394.59|","MoveTo|342.65, 28.39, -464.26|","Wait|0, 0, 0|10000","MoveTo|-385.24, -134.78, 303.72|","MoveTo|-351.10, -142.87, 260.26|","MoveTo|-342.71, -142.66, 255.77|","Wait|0, 0, 0|3000","MoveTo|-307.65, -149.86, 202.32|","MoveTo|-258.97, -165.38, 220.97|","MoveTo|-257.69, -165.62, 209.02|","Wait|0, 0, 0|3000","Boss|-250.72, -173.00, 131.46|","Wait|-249.59, -173.00, 117.29|3000"]
```

(1126) The Aetherfont
```
["MoveTo|-313.32, 19.87, 231.16|","Wait|0, 0, 0|10000","Boss|-323.64, -0.00, 120.80|","MoveTo|-322.01, 1.44, 82.51|","Wait|0, 0, 0|15000","MoveTo|270.67, 7.71, -8.83|","Wait|0, 0, 0|8000","MoveTo|397.46, 45.96, -144.88|","Wait|0, 0, 0|17000","Boss|425.12, 20.00, -439.80|","MoveTo|425.07, 20.47, -479.87|","Wait|0, 0, 0|20000","MoveTo|-394.99, -815.09, -184.95|","Wait|0, 0, 0|8000","Boss|-370.18, -873.00, -342.78|","MoveTo|-368.75, -873.00, -341.24|"]
```
```
["MoveTo|-313.32, 19.87, 231.16|","Wait|0, 0, 0|10000","Boss|-323.64, -0.00, 120.80|","MoveTo|-322.01, 1.44, 82.51|","Wait|0, 0, 0|15000","MoveTo|270.67, 7.71, -8.83|","Wait|0, 0, 0|8000","MoveTo|397.46, 45.96, -144.88|","Wait|0, 0, 0|17000","Boss|425.12, 20.00, -439.80|","MoveTo|425.07, 20.47, -479.87|","Wait|0, 0, 0|20000","MoveTo|-397.45, -815.00, -178.74|","MoveTo|-396.18, -815.18, -184.35|","Wait|0, 0, 0|10000","MoveTo|-369.88, -873.00, -348.50|","ChatCommand|0, 0, 0|/targetenemy","ChatCommand|0, 0, 0|/ac \u0022Auto-attack\u0022","Boss|-370.18, -873.00, -350.49|"]
```

(1164) The Lunar Subterrane
```
["MoveTo|-437.96, -448.65, 78.49|","Wait|-0,0,0|6000","MoveTo|-450.49, -505.99, -113.91|","Wait|-0,0,0|6000","Boss|-400.80, -550.70, -230|","MoveTo|-400.99, -554.40, -277.38|","Wait|-0,0,0|6000","MoveTo|-374.76, -567.34, -411.95|","Wait|-0,0,0|5500","Interactable|6.07, 232.89, 296.56|\u5B9D\u7BB1","Interactable|8.86, 208.00, 167.83|\u5B9D\u7BB1","Boss|0.12, 199.94, 69.34|","MoveTo|-0.16, 199.94, 44.74|","Interactable|-6.78, 200.22, -78.67|\u5B9D\u7BB1","Interactable|-34.83, 200.42, -274.47|\u5B9D\u7BB1","MoveTo|-0.64, 209.00, -323.12|","Wait|-0,0,0|5000","Boss|0.53, 219.90, -419.88|","Interactable|0.11, 219.90, -431.58|\u5B9D\u7BB1","Interactable|-0.16, 219.90, -438.59|\u8131\u51FA\u5730\u70B9"]
```
```
["-418.90576, -445.25, 149.25897","-428.62982, -448.87, 97.12054","-437.82544, -448.64932, 77.716125","Wait|5000","-465.80862, -506.27667, -82.89896","-450.15866, -505.9923, -114.287605","Wait|5000","Boss|-401.00604, -550.70404, -230.99074","-400.79047, -550.7041, -241.49683","TreasureCoffer|","-400.72797, -554.2923, -276.5595","Wait|5000","-373.6467, -567.31824, -423.42123","Wait|10000","6.301803, 232.88507, 296.02533","TreasureCoffer|","60.174183, 229.26036, 297.68973","61.950806, 225.16998, 266.03732","26.22483, 207.83707, 187.17375","0.38904482, 207.68756, 173.90552","-9.132276, 208.00198, 168.16913","TreasureCoffer|","0.04317872, 199.96854, 137.85301","Boss|0.29054812, 199.91771, 64.43494","0.16850013, 199.94507, 44.540936","TreasureCoffer|","-0.30816016, 199.9, -45.666824","-5.8084254, 200.31313, -79.901764","TreasureCoffer|","-0.42470053, 199.9, -94.08717","0.57478625, 199.9, -147.54762","0.591253, 200.06549, -203.03064","-21.056822, 199.84769, -228.667","-40.06059, 199.96078, -271.86844","TreasureCoffer|","-0.54051536, 210.24857, -334.55872","Wait|5000","Boss|0.12375674, 219.9001, -422.1799","-0.15350859, 219.90009, -432.2542","TreasureCoffer|","ExitDuty|"]
```
```
["MoveTo|-419.09, -445.25, 138.12|","MoveTo|-435.80, -448.87, 83.82|","MoveTo|-437.36, -448.87, 79.87|","ChatCommand|0, 0, 0|/automove","Wait|0, 0, 0|2000","ChatCommand|0, 0, 0|/automove","Wait|0, 0, 0|4000","MoveTo|-514.84, -502.34, -52.92|","MoveTo|-451.87, -506.28, -109.60|","MoveTo|-450.75, -506.23, -112.64|","MoveTo|-450.75, -506.23, -112.64|","ChatCommand|0, 0, 0|/automove","Wait|0, 0, 0|2000","ChatCommand|0, 0, 0|/automove","Wait|0, 0, 0|4000","Boss|-401.02, -550.70, -231.33|","MoveTo|-401.00, -550.70, -242.18|","MoveTo|-401.00, -554.57, -271.46|","MoveTo|-401.06, -554.52, -275.02|","ChatCommand|0, 0, 0|/automove","Wait|0, 0, 0|2000","ChatCommand|0, 0, 0|/automove","Wait|0, 0, 0|4000","MoveTo|-374.01, -567.34, -429.11|","Wait|0, 0, 0|5500","MoveTo|7.58, 232.91, 294.78|","MoveTo|60.72, 229.26, 296.72|","MoveTo|-9.05, 208.00, 167.70|","MoveTo|0.29, 199.66, 131.16|","Boss|-0.16, 199.95, 66.52|","MoveTo|0.00, 199.95, 43.93|","MoveTo|-6.18, 200.22, -78.95|","MoveTo|0.31, 200.07, -203.13|","MoveTo|-40.38, 199.96, -271.25|","MoveTo|-0.77, 209.00, -328.46|","Wait|0, 0, 0|5000","MoveTo|-0.08, 209.00, -330.89|","Boss|0.10, 219.90, -421.25|","MoveTo|0.04, 219.90, -432.06|","MoveTo|0.13, 219.90, -437.71|"]
```

# Endwalker Trials

# Variant Dungeons

# DawnTrail

(1167) Ihuykatumu
```
["Wait|-69.09, -194.00, -33.12|10000","Wait|-68.83, -194.00, -32.44|20000","Wait|-69.54, -194.00, -31.01|15000","Wait|-69.05, -194.00, -31.49|30000","Wait|-73.36, -194.00, -30.75|45000","MoveTo|-61.06, -194.00, -30.78|","ChatCommand|0, 0, 0|/automove on boat","Wait|0, 0, 0|2000","ChatCommand|0, 0, 0|/automove off","Boss|33.57, -202.93, -70.30| CP1","Boss|34.61, -203.00, -97.09|","MoveTo|150.12, -195.07, -20.24|","MoveTo|153.93, -195.20, -21.66|","ChatCommand|0, 0, 0|/automove on lad1","Wait|0, 0, 0|10000","Wait|203.71, -158.62, 104.86|3000","MoveTo|202.74, -158.66, 116.73|","Wait|140.82, -155.18, 110.85|2000","MoveTo|129.91, -154.36, 112.14|","ChatCommand|0, 0, 0|/automove on lad2","Wait|0, 0, 0|9500","Boss|81.93, -134.49, 86.29| CP2","Boss|80.00, -134.00, 48.50|","MoveTo|67.05, -134.00, 40.84|","MoveTo|44.76, -132.27, 37.23|","MoveTo|38.03, -130.60, 36.60|","ChatCommand|0, 0, 0|/automove on lad3","Wait|0, 0, 0|8500","MoveTo|11.05, -110.84, 149.36|","MoveTo|-97.43, -115.19, 336.73|","Boss|-106.73, -115.13, 294.72| CP3","Boss|-107.10, -118.00, 262.50|"]
```

(1193) Worqor Zormor
```
["Boss|-107.79, 10.82, 148.36| CP1","Boss|-108.06, 11.00, 118.30|","MoveTo|-145.12, 22.12, 75.04|","Wait|-72.13, 40.00, 54.97|1000","MoveTo|-64.07, 40.31, 52.89|","ChatCommand|0, 0, 0|/automove on Wind1","Wait|0, 0, 0|6000","Wait|-38.33, 55.08, 27.14|5000","MoveTo|-46.23, 55.13, 19.48|","Wait|-49.39, 55.61, 16.04|5000","MoveTo|-80.91, 85.14, 13.47|","MoveTo|-95.30, 78.16, 24.56|","Wait|-94.81, 70.00, 48.49|500","MoveTo|-96.64, 70.00, 41.58|","Wait|-103.14, 70.26, 42.74|500","ChatCommand|0, 0, 0|/automove on Wind3","Wait|0, 0, 0|6500","MoveTo|-160.96, 80.03, 34.28|","MoveTo|-63.50, 101.84, -15.99|","MoveTo|-59.52, 103.69, -18.22|","ChatCommand|0, 0, 0|/automove on Wind4","Wait|0, 0, 0|11000","Boss|-53.32, 321.29, -32.54| CP2","Boss|-53.21, 323.00, -57.42|","Wait|-121.52, 328.08, -78.02|2000","MoveTo|-153.23, 334.71, 0.86|","MoveTo|-69.37, 358.07, -91.81|","Boss|-53.94, 376.01, -159.15| CP3","Boss|-53.98, 378.00, -197.58|"]
```

(1194) The Skydeep Cenote
```
["MoveTo|32.35, -35.46, 1.86|","MoveTo|-104.28, -52.66, -84.07|","Boss|-105.21, -52.05, -139.21| CP1","Boss|-105.08, -52.00, -158.50|","MoveTo|-105.04, -52.00, -168.91|","MoveTo|-104.78, -51.95, -208.89|","MoveTo|-156.68, -51.71, -208.91|","ChatCommand|0, 0, 0|/automove on D1","Wait|0, 0, 0|5000","ChatCommand|0, 0, 0|/automove off D1","MoveTo|-216.64, -210.00, -49.38|","Wait|-84.25, -209.91, -62.04|6000","Wait|-75.80, -210.00, -65.22|2000","MoveTo|-78.21, -210.00, -92.33|","Boss|-84.90, -210.00, -123.53| CP2","Boss|-85.14, -210.00, -154.64|","MoveTo|-69.91, -210.00, -155.30|","MoveTo|38.56, -210.00, -155.22|","MoveTo|110.41, -189.75, -214.27|","MoveTo|101.95, -189.90, -227.82|","Wait|100.22, -189.90, -230.67|8500","MoveTo|137.06, -184.90, -335.19|","Boss|100.07, -195.00, -352.96| CP3","MoveTo|100.08, -194.90, -358.81|","MoveTo|100.06, -194.90, -361.61|","ChatCommand|0, 0, 0|/automove on Tr2","Wait|0, 0, 0|7000","Boss|99.52, -191.99, -430.83|","MoveTo|100.01, -191.99, -436.88|"]
```

(1198) Vanguard
```
["MoveTo|-100.27, 0.00, 263.57|","Boss|-100.30, 7.00, 238.13| CP1","Boss|-100.24, 7.00, 201.67|","MoveTo|-71.78, 7.01, 102.07|","MoveTo|-56.91, 7.00, 102.18|","MoveTo|-41.32, 7.05, 94.14|","MoveTo|-46.36, 7.05, -37.68|","MoveTo|0.06, 7.03, -38.12|","MoveTo|5.71, 7.00, -46.47|","Boss|-0.06, 7.03, -72.58| CP2","Boss|0.06, 7.00, -103.67|","MoveTo|19.05, 7.00, -327.04|","MoveTo|21.55, 7.03, -320.29|","MoveTo|99.11, 7.05, -347.91|","Boss|90.25, 11.97, -405.15| CP3","Boss|90.05, 12.00, -437.40|"]
```

(1208) Origenics
```
["MoveTo|29.84, 302.00, 126.74|","MoveTo|29.83, 302.00, 135.95|","ChatCommand|0, 0, 0|/automove on Tr1","Wait|0, 0, 0|6500","MoveTo|-169.74, -504.00, 15.90|","Interactable|0, 0, 0|Elevator Console","Wait|0, 0, 0|8000","MoveTo|-98.76, -500.00, 156.89|","Boss|-98.76, -500.00, 156.89| CP1","MoveTo|-98.80, -500.00, 152.33|","ChatCommand|0, 0, 0|/automove on Tr2","Wait|0, 0, 0|6000","Boss|-86.95, -120.00, -179.10|","MoveTo|-75.80, -120.00, -179.96|","MoveTo|-36.42, -120.00, -180.33|","MoveTo|44.58, -120.00, -129.21|","MoveTo|84.94, -120.00, -125.36|","MoveTo|85.12, -120.00, -116.10|","ChatCommand|0, 0, 0|/automove on Tr3","Wait|0, 0, 0|4000","MoveTo|-187.33, -94.00, -86.08|","Boss|-171.57, -94.00, -107.90| CP2","Boss|-172.06, -94.00, -146.50|","MoveTo|-172.06, -94.00, -160.17|","MoveTo|-171.92, -94.00, -215.20|","MoveTo|-172.11, -90.61, -227.50|","ChatCommand|0, 0, 0|/automove on Tr3","Wait|0, 0, 0|7000","MoveTo|118.70, 0.00, 196.30|","MoveTo|157.48, 0.00, 179.80|","MoveTo|189.81, 0.00, 64.66|","Boss|189.73, 0.00, 33.64| CP3","Boss|189.80, 0.00, -3.01|","MoveTo|189.92, 0.00, -12.38|"]
```

(1199) Alexandria
```
["Wait|0, 0, 0|1","MoveTo|-26.81, 492.66, 113.51|","StopForCombat|-111.75, 500.80, 75.56|True","StopForCombat|-115.67, 506.42, 27.67|True","MoveTo|-116.30, 506.42, -16.00|","ChatCommand|0, 0, 0|/automove on","Wait|-116.30, 506.42, -16.00|1","ChatCommand|0, 0, 0|/automove off","Boss|852.33, 46.00, 827.42|","TreasureCoffer|852.01, 46.00, 815.44|","Wait|848.72, 46.00, 809.76|2","MoveTo|781.63, 33.55, 735.12|","MoveTo|745.84, 33.56, 727.19|","MoveTo|790.41, 42.36, 680.82|","StopForCombat|790.41, 42.36, 680.82|True","MoveTo|779.71, 53.19, 619.42|","Wait|779.71, 53.19, 619.42|10","MoveTo|748.93, 64.79, 611.80|","TreasureCoffer|745.31, 64.79, 617.26|","MoveTo|744.10, 64.79, 612.70|","ChatCommand|0, 0, 0|/automove on","Wait|0, 0, 0|5","Boss|-533.03, -466.00, -368.11|","TreasureCoffer|-533.12, -466.00, -387.23|","StopForCombat|-590.15, -472.88, -441.35|True","StopForCombat|-583.65, -467.69, -478.37|True","TreasureCoffer|-584.64, -463.99, -509.77|","StopForCombat|-701.89, -470.96, -560.67|True","TreasureCoffer|-732.53, -474.35, -564.92|","StopForCombat|-732.79, -478.52, -590.39|True","MoveTo|-758.50, -474.28, -630.08|","Boss|-758.72, -474.00, -647.41|","TreasureCoffer|-759.11, -474.00, -658.35|"]
```
```
["MoveTo|-26.81, 492.66, 113.51|","StopForCombat|-111.75, 500.80, 75.56|True","StopForCombat|-115.67, 506.42, 27.67|True","Boss|-116.43, 506.42, -10.70| CP1","MoveTo|-116.30, 506.42, -16.00|","ChatCommand|0, 0, 0|/automove on Tr1","Wait|0, 0, 0|8000","Boss|852.33, 46.00, 827.42|","TreasureCoffer|852.01, 46.00, 815.44|","Wait|0, 0, 0|2000","MoveTo|807.99, 35.53, 724.31|","MoveTo|781.63, 33.55, 735.12|","MoveTo|745.84, 33.56, 727.19|","MoveTo|790.41, 42.36, 680.82|","StopForCombat|790.41, 42.36, 680.82|True","MoveTo|779.71, 53.19, 619.42|","Wait|0, 0, 0|10000","MoveTo|748.93, 64.79, 611.80|","TreasureCoffer|745.31, 64.79, 617.26|","Boss|747.20, 64.79, 612.33| CP2","MoveTo|744.10, 64.79, 612.70|","ChatCommand|0, 0, 0|/automove on Tr2","Wait|0, 0, 0|5000","Boss|-533.33, -466.00, -381.60|","TreasureCoffer|-533.12, -466.00, -387.23|","StopForCombat|-590.15, -472.88, -441.35|True","StopForCombat|-583.65, -467.69, -478.37|True","TreasureCoffer|-584.64, -463.99, -509.77|","StopForCombat|-701.89, -470.96, -560.67|True","TreasureCoffer|-732.53, -474.35, -564.92|","StopForCombat|-732.79, -478.52, -590.39|True","MoveTo|-758.50, -474.28, -630.08|","Boss|-758.72, -474.00, -647.41|","TreasureCoffer|-759.11, -474.00, -658.35|"]
```

() Tender Valley
```
```

() The Strayborough Deadwalk
```
```



