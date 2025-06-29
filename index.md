---
layout: default
title: Available Commands
---

# Basic Design

- [Basic Design](https://docs.google.com/document/d/e/2PACX-1vQRy2vSl1tzd4_FMRCcILB4qb8lcTMvoB7w8hNFotlLjBSn8Nz7eZfa6bZMWTRFwaMiod_KpwH6Pxyb/pub)

# Bot Commands

- **`!commands`** (`!command`, `!cmd`, `!help`)  
  Show a link to this page with the commands list.  
    
  このコマンド一覧ページへのリンクを表示。  

- **`!nickname <new_nickname>`** (`!nick`)  
  Update user's nickname in Chibi's memory.  
  *Example:* `!nickname tanuki` → The commenter's nickname will be `tanuki`.  
    
  Chibiがあなたの"呼び名・あだ名"を覚えるよ～  
  例：`!nickname tanuki` → Chibiが以降コメント投稿者を `tanuki` と認識するよ  

- **`!cheer <name> [/ <topic>]`** (`!boost`)  
  Cheer for a user in English. Optional \<topic\>.  
  *Example:* `!cheer AkkirOrihsam` → Cheers for AkkirOrihsam.  
  *Example:* `!cheer ShinraFN / Geoguessr duels` → Cheers for ShinraFN about "Geoguessr duels".  

  Defaults \<name\> to Zash if \<name\> is missing.  
  *Example:* `!cheer` → Cheers for Zash.  

- **`!ouen <name> [/ <topic>]`** (`!ganbare`)  
  指定したユーザーを日本語で応援するよ。\<name\>推奨、\<topic\>は任意。  
  *Example:* `!ouen キューさん` → キューさんを応援するよ。  
  *Example:* `!ouen すずめさん / 仕事の締め切り` → 「仕事の締め切り」までがんばれるようにすずめさんを応援するよ。  

  \<name\>が無い場合はザッシュを応援。  
  *Example:* `!ouen` → ザッシュを応援。  
  *Example:* `!ouen 決勝戦` → ザッシュの決勝戦を応援するよ。  

- **`!lurk`**  
  When you lurk, I guess. I heard people like this. (I don't understand...Is it modern?)  

- **`!rom`**  
  !lurk の日本語版。ROMる時に使えるらしい、知らんけど、どうぞ

- **`!emote <EMOTE> <emote_description>`** (`!nick`)  
  Register an emote to help Chibi understand them. Chibi only "sees" the string representation, please help her by explaining what a particular emote means.  
  Especially helpful with custom channel emotes.  
  *Examples:*  
  > !emote ![LUL emote](https://static-cdn.jtvnw.net/emoticons/v2/425618/static/light/1.0) laugh  
  > !emote ![PogChamp emote](https://static-cdn.jtvnw.net/emoticons/v2/305954156/default/dark/1.0) excited  
    
  Chibiにはスタンプは文字列としてしか認識できないので、Chibiにスタンプの説明をしてね  

## Additional Commands for Mods

- **`!instructions`**  
  Declare additional instructions for Chibi. Only effective during the session, it does not persist when Chibi reboots/restarts.  

  *Example:* `!instructions Only respond in Japanese`

- **`!othernickname`** (`!othernick`)
  Set a nickname for a specified user.

  > !othernickname <username> <new_nickname>
  > !othernickname 9dmg_pk キューさん