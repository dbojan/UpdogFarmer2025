## Idle Daddy

#2025-12-17-1

fork of https://github.com/steevp/UpdogFarmer

Steam Trading Card farmer for Android

work in progress...

buildable in android studio, you have to enter you steam api instead of dymmy variable in gradle.properties


2025-12-18-1:

Idle Daddy settings:  
  
settings that work for me on Android 10:  
-Idle Daddy App properties/battery:   
Background restriction: App can use battery in the background  
Battery optimization: Optimizing battery use  
-Open Idle Daddy/settings/keep device awake = on  
  
-Login to Idle Daddy  
Go to games, select games to run, up to 32  
you will not see game time increase until: at least two minutes have passed, AND, you have deselected games in ID.  
if you don't check times, it will still be increasing, of course.  
DO NOT click on 'start farming' on the main page, it will switch app to 'card farming' mode  
If you go back to main screen in ID, it should say 'Logged in'  
  
-you can see game(s) you are currently playing in https://steamcommunity.com/id/your_steam_name/, 'Currently In-Game', press f5 to refresh from time to time.  
-steamcommunity will show just a single game running, although multiple games will be running (if you selected them in ID)  
  
-In Idle Daddy, in 'games' page in ID, pull down to refresh (after deselecting games in Idle Daddy)  
-If you want see how much your in game time increased, AFTER AT LEAST two minutes, deselect the games in ID, to see time difference, in the app and on the site.   
-steam app will not show games current running, but will time increase (after deselecting them in ID)  
-Running steam app does not make the difference, unless you are running 32 games in id, and wa  
  
if you still get logged out: disable app battery optimization (set 'Battery optimization' to not optimized). If it does not help, disable phone 'battery save' mode.  
  
I do not think start farming works, cause it does not recognize games that have card drops. If you turn screen off and on, it will say 0 card drops remaining, even though you have card drops remaining.  
  
-if you click on game in 'games listing' screen, it will stop 'card farming' mode, and start 'playing game(s)' mode  
-if you click on stop service, ID will log you out.  
