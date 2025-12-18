## Idle Daddy

#2025-12-17-1

fork of https://github.com/steevp/UpdogFarmer

Steam Trading Card farmer for Android

work in progress...

buildable in android studio, you have to enter you steam api instead of dymmy variable in gradle.properties


<hr>

2025-12-18-1 notes, for all versions of the app:

**Running Idle Daddy:**  

Settings that work for me on Android 10:  
- Idle Daddy App properties/battery:   
  - Background restriction: App can use battery in the background  
  - Battery optimization: Optimizing battery use  
- Open Idle Daddy/settings/keep device awake = on  
- Login to Idle Daddy  
- Go to games, select games to run, up to 32  

- DO NOT click on 'start farming' on the main page, it will switch app to 'card farming' mode  
- If you go back to main screen in Idle Daddy, it should say 'Logged in'  
- if you still get logged out out of Idle Daddy: disable App battery optimization (set 'Battery optimization' to not optimized). If it does not help, disable phone 'battery save' mode.  

**Inspecting time played increase:**

- you will not see game time increase until: **at least two minutes have passed**, AND, you have **deselected game(s) in Idle Daddy**.  
- if you don't check times, **it will still be increasing**, of course.  
- you can see game(s) you are currently playing in https://steamcommunity.com/id/your_steam_name/, 'Currently In-Game'. Press f5 to refresh from time to time.  Steamcommunity will show just a single game running, although multiple games will be running (if you selected them in Idle Daddy)  
- in 'games' page in Idle Daddy, pull down to refresh (after deselecting games in Idle Daddy)  
- steam app will not mark games current running as 'running', but their game play time will increase (after deselecting them in Idle Daddy)  
- running steam app does not make the difference, unless you are running 32 games in Idle Daddy, and want to play another one. Steam can track up to 32 games running at once.  
  

  
I do not think 'start farming works', cause it does not recognize games that have card drops. If you turn screen off and on, it will say 0 card drops remaining, even though you have card drops remaining.  
  
-if you click on game in 'games listing' screen, it will stop 'card farming' mode, and start 'playing game(s)' mode  

-if you click on stop service, Idle Daddy will log you out.  
