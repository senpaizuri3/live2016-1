# **Simon**
*All commands are case-insensitive.*

### Commands
* [```Searching cards```](#searching-cards)
* [```Opening packs```](#opening-packs)
* [```Trivia Game```](#trivia-game)

---

### **Searching cards**

>**Type `<card_name[, input_language][, output_language]>` to search for a Yu-Gi-Oh! card.**  
Searching with `{}` instead of `<>` results in a more compact response.

*`<Kuriboh>` gives the following result:*  
![Kuriboh](http://image.prntscr.com/image/72822c5ccc7c452e939ca83d5627f431.png)

>The following languages are available:  
English (en), German (de), French (fr), Italian (it), Spanish (es), Japanese (ja), Chinese (ch) and Taiwanese (tw).  

*`<Bunilla, en, ja>` accesses the japanese database by only giving the english card name:*  
![Bunilla](http://image.prntscr.com/image/43b3519b8db24684a14c25092d74bf4d.png)

---

### **Opening packs**

>**Type `.packopen [format] [language] [pack_name]` to open a pack.**  
Format: `TCG` or `OCG` (Default: `TCG`)  
Language: `en`, `de`, `fr`, `it`, `es`, `ja` or `cn` (Default: `en`)  
Pack name: The name of any Yu-Gi-Oh! pack.
Alias: `.po`  

`.po Breakers of Shadow` opens a pack with nine random cards, containing one holo, one rare and seven common cards:  
![Breakers of Shadow](http://image.prntscr.com/image/8d66b367c27d46b29e184cfcac39077b.png)

### **Trivia Game**

>**Type `.trivia [format] [end_score]` to play the trivia game.**  
The goal of the game is to guess the name of a card as fast as possible by only looking at its picture.  
Format: `Anime`, `TCG`, `OCG` (Default: all)  
End score: The number of points that are needed to win the game. A scoreboard is displayed after each card.
Alias: `.t`  

>**Type `.trivaquit` to stop the game.**  
Only the creator of the game and certain roles or users whitelisted in the server config are permitted to do this.  
Alias. `.tq`  

`.t 10` starts a game that ends when someone reached 10 points:  
