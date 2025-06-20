---
layout: default
title: Available Commands
---

# Basic Design

- [Basic Design](https://docs.google.com/document/d/e/2PACX-1vQRy2vSl1tzd4_FMRCcILB4qb8lcTMvoB7w8hNFotlLjBSn8Nz7eZfa6bZMWTRFwaMiod_KpwH6Pxyb/pub)

# Bot Commands

- **`!commands`** (`!command`, `!cmd`, `!help`)  
  Show link to this page with commands list.  
    
  このコマンド一覧ページへのリンクを表示。  

- **`!nickname <new_nickname>`** (`!nick`)  
  Update user's nickname in Chibi's memory.  
  *Example:* `!nickname tanuki` → The commenter's nickname will be `tanuki`.  
    
  Chibiがあなたの"呼び名・あだ名"を覚えるよ～  
  例：`!nickname tanuki` → Chibiが以降コメント投稿者を `tanuki` と認識するよ  

- **`!emote <EMOTE> <emote_description>`** (`!nick`)  
  Register an emote to help Chibi understand them. Chibi only "sees" the string representation, please help her by explaining what a particular emote means.  
  Especially helpful with custom channel emotes.  
  *Examples:*  
  > !emote ![LUL emote](https://static-cdn.jtvnw.net/emoticons/v2/425618/static/light/1.0) laugh  
  > !emote ![PogChamp emote](https://static-cdn.jtvnw.net/emoticons/v2/305954156/default/dark/1.0) excited  
    
  Chibiにはスタンプは文字列としてしか認識できないので、Chibiにスタンプの説明をしてね  

- **`!lurk`**  
  When you lurk, I guess. I heard people like this. (I don't understand...Is it modern?)  

- **`!rom`**  
  !lurk の日本語版。ROMる時に使えるらしい、知らんけど、どうぞ

## Additional Commands for Mods

- **`!instructions`**  
  Declare additional instructions for Chibi. Only effective during the session, it does not persist when Chibi reboots/restarts.  

  *Example:* `!instructions Only respond in Japanese`