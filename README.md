# Gems-of-War-Macros
This repository will host AutoHotkey macros for use in Gems of War (Steam/PC Version).
Coded by Jaleen Mackay (April 9th, 2021) for Gems of War on Steam (e.g., the PC version).
Version 1.0 for 16:9 aspect ratio screens (1920x1080 and others).

This README is also duplicated in the AutoHotkey script and probably won't be updated unless someone requests that I make this script available for other aspect ratios.

**IMPORTANT**

YOU MAY BE BANNED SINCE GEMS OF WAR SAYS "NO" TO MACROS.

  • You are not allowed to "gain an unfair advantage against other players in the game" using various tools.
  
  • Read more here, if you like: https://gemsofwar.zendesk.com/hc/en-us/articles/360000348076-Hacking-or-cheating-in-Gems-of-War
  
  • As an avid player, I used this macro for a long time (circa 2018) to avoid getting carpal tunnel syndrome; I have not *personally* been banned. #noragrets 
  
  • I categorically *do not* take responsibility for anything the Gems of War devs do in their war against accessibility, hotkeys, or fun; it is not my fault if they swing the ban hammer.
  
  • C a v e a t    e m p t o r .  😗
  

**PURPOSE**

This script is intended for smart casting troop skills during combat as well as moving quickly through the post-battle "continue" menus:

(1) It increases accessibility for people with mobility challenges by limiting the amount of movement/clicking motions with the mouse hand, both in and out of combat.

(2) It enables all players to have hotkeys or "smart casts" for quickly using troop skills in combat.

(3) It enables veteran players to skip the reminder text and card image that come up when you select a troop skill.

(4) It generally speeds up gameplay and the "fun bits" by decreasing tedious and repetitive tasks in-game, like clicking the "continue" button when you just want to get to the next battle.

(5) Maybe it will inspire the devs to actually add hotkeys/accessibility options to their mouse-based game... 7 years later. 🙃
 

**HOW TO USE**

During battle, pressing 1/2/3/4 will click to activate the casts of Troops 1/2/3/4 respectively, then return your mouse to its original position.
After battle, pressing the space bar will hit "skip"; press again to hit "continue" and return your mouse to its original position.

**LIMITATIONS**

This script is *not* context sensitive, so it will limit your ability to type in global chat with 1/2/3/4 as well as use the space bar.

This script only works for 16:9 aspect ratio screens; the most common 16:9 resolution is 1920x1080 (which is what I use). Other common resolutions include 1024×576, 1152×648, 1280×720, 1366×768, 1600×900, 2560×1440, and 3840×2160.

**CUSTOMIZATION OPTIONS**

You can remove the space bar script by deleting the "CUSTOMIZATION OPTION" line and everything below it. This is useful, for example, if you regularly type in chat (and use the space bar like a normal person).

I suppose you could also delete all of the "smart casting" script by deleting everything from the "; PRESS 1" line down to the space before the "CUSTOMIZATION OPTION" line.

Want to change the keys used in the script, like changing the 1/2/3/4 keys to Q/W/E/R or something? Change the "#::" part of the script to "[new key]::" in each section. You can find a list of key options here: https://www.autohotkey.com/docs/KeyList.htm

**OTHER WORKAROUNDS**

If you want to type in global chat (using the space bar) but want to *keep* the space bar script, you can type by only pressing the space bar with another key pressed down. For example, I would always press CTRL + space bar to add spaces when quickly typing in chat. You could also hold down the CTRL key the whole time, if you like.

If you want to type 1/2/3/4 in chat, you can use the num pad keys without triggering the script.
