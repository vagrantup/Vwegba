
# TOWER-RECORDS-MUSIC-Downloader
[TOWER RECORDS MUSIC](https://dereferer.me/?https://music.tower.jp/home/) downloader written in Go.
![](https://i.imgur.com/m5I6WYP.png)
[Windows, Linux and macOS binaries](https://github.com/Sorrow446/TOWER-RECORDS-MUSIC-Downloader/releases)

# Setup
Input credentials into config file.
Configure any other options if needed.
|Option|Info|
| --- | --- |
|email|Email address.
|password|Password.
|format|Download quality. 1 = AAC 128, 2 = AAC 320.
|outPath|Where to download to. Path will be made if it doesn't already exist.
|trackTemplate|Track filename naming template. Vars: album, albumArtist, artist, title, track, trackPad, trackTotal, year.
|lyrics|Get lyrics if available.
|recochokuAccount|Set to true if your account is a Recochoku one.
