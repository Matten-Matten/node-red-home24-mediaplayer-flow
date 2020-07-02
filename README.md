![Logo](https://lh3.googleusercontent.com/RPzIxiY8DEC6DKp7RlkT-cB1MoDjuZsTGKMzXzWD8YeBk9fT7hFxMuV83ymCvCaet3Q=s80-rw)
[Home24-MediaPlayer](http://www.home-24.net/index.php?app=media)
# **NodeRed Home24 Mediaplayer Subflow**

 ![picture](https://avatars3.githubusercontent.com/u/5375661?s=50&v=4)
 
 - Subflow for Nodered to send commands to Home24 Mediaplayer App.
 - (DE) Subflow für Nodered um Befehle an die Home24 Mediaplayer App zu senden
 
### Forum: https://homematic-forum.de/forum/viewtopic.php?f=77&t=59572


### Subflow: https://github.com/Matten-Matten/node-red-home24-mediaplayer-flow/blob/master/home24-mediaplayer-SUB-Flow.json

---
## Beispiel:

![picture](https://raw.githubusercontent.com/Matten-Matten/node-red-home24-mediaplayer-flow/master/picture/Node-RED_home24-mediaplayer.png)

---
## Config overview:

![picture](https://raw.githubusercontent.com/Matten-Matten/node-red-home24-mediaplayer-flow/master/picture/Node-RED_home24-mediaplayer-Settings.png)

---
![picture](https://raw.githubusercontent.com/Matten-Matten/node-red-home24-mediaplayer-flow/master/picture/Node-RED_home24-mediaplayer-Settings1.png)

---
![picture](https://raw.githubusercontent.com/Matten-Matten/node-red-home24-mediaplayer-flow/master/picture/Node-RED_home24-mediaplayer-Settings2.png)

---
# **INPUT:**

`msg.payload`

---
# **COMMANDS:**
---
## LED
 - led=red / led=red&flash
 - led=green / led=green&flash
 - led=yellow / led=yellow&flash
 - led=blue / led=blue&flash
 - led=white / led=white&flash
 - led=magenta / led=magenta&flash
 - led=cancel


## Vibrate
 - vibrate


## Statusbar
 - statusbar=Hello Android
 - statusbar=cancel


## Text
 - textsmall=Hallo, weiterer Text
 - textmedium=Hallo, weiterer Text
 - textlarge=Hallo, weiterer Text
 - text=close


## Infobox
 - infobox=Hello Android


## TTS
 - tts=Hallo HomeMatic
 
(bei einigen Geräten ist keine Sprache für TTS vorinstalliert. Kontrollieren oder nachinstallieren können Sie diese unter "Einstellungen" -> "Sprache und Eingabe "-> "Text in Sprache" )


## Volume
 - volume=10 (1-15)


## Call
 - call=0421123456
 - dial=0421123456
 - sms=0150123456&message=Hallo (GSM Modul im Geräte vorausgesetzt und nur bis Version 1.25 da Google die Funktion nicht mehr erlaubt)


## App
 - Starte Standard-Apps ab Android 4.0.3
 - appbrowser
 - appcalendar
 - appappcontacts
 - appgallery
 - appmail
 - appmaps
 - appmessaging
 - appmusic


## Screen
 - screenon (continual)
 - screenoff
 - screentimeout=10 in sec


## Color Screen
 - colorscreen=red
 - colorscreen=green
 - colorscreen=yellow
 - colorscreen=blue
 - colorscreen=white
 - colorscreen=magenta
 - colorscreen=black
 - colorscreen=ltgray
 - colorscreen=gray
 - colorscreen=dkgray
 - colorscreen=cyan
 - colorscreen=close


## Tasker
 - tasker="Name des Task"


## Track
 - track="beispiel.mp3"

---

## Changelog

### 0.0.2 (2020-06-29)
* (Matten-Matten)       add: `bugfix`

### 0.0.1 (2020-06-28)
* (Matten-Matten)       add: `first publication`

---
made by [Matten Matten](https://github.com/Matten-Matten)
