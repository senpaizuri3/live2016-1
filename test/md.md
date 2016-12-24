# **Simon**
[![YGOPro Percy](http://i.imgur.com/v732Scx.png)](https://discord.gg/XMTrt43)

*All commands are case-insensitive.*  
### Commands
* [```Card Search```](#card-search)
* [```Pack Opening```](#pack-opening)
* [```Trivia Game```](#trivia-game)
* [```Scripting Library```](#scripting-library)

---

### **Card Search**

>**Type `<card_name[, input_language][, output_language]>` to search for a Yu-Gi-Oh! card.**  
Searching with `{}` instead of `<>` results in a more compact response.

*`<Kuriboh>` gives the following result:*  
![Kuriboh](http://image.prntscr.com/image/72822c5ccc7c452e939ca83d5627f431.png)

>The following languages are available (Default: `en`):  
English (`en`), German (`de`), French (`fr`), Italian (`it`), Spanish (`es`), Japanese (`ja`), Chinese (`ch`) and Taiwanese (tw).  

*`<Bunilla, en, ja>` accesses the japanese database by only giving the english card name:*  
![Bunilla](http://image.prntscr.com/image/43b3519b8db24684a14c25092d74bf4d.png)

---

### **Pack Opening**

>**Type `.packopen [format] [language] [pack_name]` to open a pack.**  
Format: `TCG` or `OCG` (Default: `TCG`)  
Language: `en`, `de`, `fr`, `it`, `es`, `ja` or `cn` (Default: `en`).  
Pack name: The name of any Yu-Gi-Oh! pack.
Alias: `.po`  

*`.po Breakers of Shadow` opens a pack with nine random cards, containing one holo, one rare and seven common cards:*  
![Breakers of Shadow](http://image.prntscr.com/image/8d66b367c27d46b29e184cfcac39077b.png)

---

### **Trivia Game**

>**Type `.trivia [format] [end_score]` to play the trivia game.**  
The goal of the game is to guess the name of a card as fast as possible by only looking at its picture.  
Format: `Anime`, `TCG`, `OCG` (Default: all)  
End score: The number of points that are needed to win the game. A scoreboard is displayed after each card (Default: 1).   
Alias: `.t`  

>**Type `.trivaquit` to stop the game.**  
Only the creator of the game and certain roles or users whitelisted in the server config are permitted to do this.  
Alias. `.tq`  

*`.t 10` starts a game that ends when someone reached 10 points:*  
![Trivia Game](http://image.prntscr.com/image/9f22ade0b6f14bbe8757440d52f60419.png)

---

### Scripting Library

**Note:** This series of commands is dedicated to the scripters of the YGOPro game and those that want to be part of those.  
If you are interested in scripting Yu-Gi-Oh! cards join the `scripting_lua_101` channel on the YGOPro Percy server.  
An Invitation link can be found at the top of this file.  

>**Type `.function [keywords]`** to search for a Lua function.  
Keywords: The words that the your function contains.
Alias: `.f`  

`.function draw`:



















