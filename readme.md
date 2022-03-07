# Welcome to larsj.info
Here you will find information about the apps that we are publishing in the Apple and Google app stores.
At the moment the following apps are in development or have been tested:
- Target for Today Assistant
and you can finfd out more information about these applications below.

# Target for Today Assistant
This app was created to make it much easier to play the Target for Today solo boardgame from Legion Wargames.
The goal of the app is to remove the need to keep any manual records while playing and to do as much of the dice rolling and table lookups for you.

As a new player I found it very hard to get used to the detailed sequence of play and would forget to do things or do them in the wrong order and the app guides you through the detailed sequence of play so that you can't forget anything or do things out of order. Using the app you should find that you don’t need any paper forms to play as it tracks everything you would mark on a form, and you can see that data any time on the left-hand scroll panel on the screen or by using some of the main menu items.

To make things easier for you, and thanks to the nice people in the TFT forums at Boardgamegeek.com, the app can generate bomber names and crew names for you and keep track of bomber damage on missions (using Peckham points). It also handles hospitalisation and recovery for wounded crew members, promotion boards and gunnery stats (including Ace status). You are also able to choose between using the default damage tables that come with the game or an alternative set provided by the techincal advisor for the game (Joe Osentoski).

The app also allows you to play multiple campaigns at the same time so you can fly a mission on, say, campaign 2 and then when that mission is over you could then decide to fly a mission on, say, campaign 4. When you swap to a campaign that you have played missions for previously the app will carry on from where you left off.

The app keeps a Composite Mission Log for you so that you can see what happened on each mission and you can export those details from the app to a file that you can import to any spreadsheet. **NB** if your pilot is killed on a mission and you want to keep the composite mission log for the game you will need to export it **after** the Gunnery Review board has taken place.

One thing to be aware of is that to allow Bomber Group games to be played it is necessary for you to choose your Army Air Force and Unit when starting a new campaign and your chosen Bomber Wing will determine the type of plane that you can fly.
To support those players that are not interested in the rest of the group and who still want the freedom to fly the bomber of their choice for the campaign they want to play (rather than being constrained by their Bomber Wing) there are now made-up bomber wings for both 8th and 15th AAFs that allow both types of bomber choices for all the relevant campaigns and city missions (based on mission dates). These made-up wings are the last entry in the bomber wing list (for 1st Air Division in 8AAF).

## Headline Limitations:
- No YB40 bomber option.
- B-24J crew assignment option defaults to Radio Operator as Left Waist Gunner, Left Waist Gunner as Nose Turret Gunner and Navigator at Radio Operator seat (later release will allow you to choose from the two options).
- Only the following optional rules are implemented: Gunnery Review Board, rule 10.5.3 for B17G Radio Room gun and Bomber Group as per rule 10.4.
- Escort effect randomly removes the attackers rather than you choose which one(s) to remove
- If available “Lady Luck Smiles” is automatically used by the app to try and avoid catastrophic events.
- No penalty crew moving
- No Tables 5-7B or 5-17C
- The app needs to be used in Landscape mode.

Anything shown inside the blue-bordered rectangles is potentially scrollable so if the text you see goes close to the bottom of the rectangle, make sure that you scroll down to see everything (this can include guns that can fire at the enemy).

## Main Menu
There is a main menu in the top left corner of the screen from which you can choose at any time. It now has the following options:

### Settings
This will display all the options available on a new settings screen. There you can choose from the following options:
- **Preferred Random Number Strategy**
Which one of 3 different random number strategies to use for the dice rolling.
- **Show more game details**
If you want to see the results of the table lookups and what the die roll modifications are then you can toggle the detail pages on (but this will mean a lot more button pressing ;-)
This will also let you see a lot more information about damage to fighters from defensive fire.
- **Show Bomber Group information**
Disable this option if you don’t want to see the various bomber group game details as described in section 10.4 of the rules.
- **Always show campaign choice before next mission**
This will allow you to swap to another campaign at the end of the current mission.
If you choose "City" then make sure you set the mission date first on the next screen as that will then determine what bomber choices you have (if a new bomber is needed) and that date will also determine which campaign number is used for the various combat tables.
- **Use your own crew names**
If you don’t want to type in your crew names the app defaults to the random crew names as posted by worst2first on BGG Files for TFT. Turn this on if you want to enter your own crew names.
- **Use your own plane name**
If you don’t want to make up your plane name the app defaults to the random plane names as posted by worst2first on BGG Files for TFT. Turn this on if you want to enter your own plane names.
- **Campaign over if pilot KIA/MIA/POW or sent home**
Your current campaign will only last as long as the pilot. If you want to continue the campaign with other surviving crew members if the pilot is lost, then you should unset this option
- **Pilot gets new crew after more than 6 weeks absence**
If the pilot needs 6+ weeks to recover from any injuries then he will get a new crew for the next mission date on his recovery date. If you want to continue with the same crew then unset this option.

### Show more details
This option will immediately show you the detailed information behind whatever has just been displayed. This is the same information that would be displayed before the current screen if you have the “Show more game details” option on except that now you can do it on demand rather than having it happen for every screen update.

### Show crew details
This option will immediately show you the information for all crew members.
Currently that information will be reset after you press “Submit” on the next mission screen so you can see any wound/frostbite details up to that point.

### Composite Mission Log
This option will immediately show you the Composite Mission Log (CML) Summary screen. A mission gets added to the Composite Mission Log when the “Next Mission” button is shown on the right-hand side of the screen.
For each summary entry, the mission number is a button that will take you to a mission detail screen for that mission where you can see the full target info and who the crew were on that mission.
The “share” button at the top right of this screen will let you export the CML details to a CSV file so that you can import it into apps like Excel. It has (only) been tested for Google Drive on Android and for iCloud on iOS/iPadOS.

### Bomber Group Status
This will show the current state of the whole bomber group with damage in amber or red and your plane shown in blue text.
At end of mission, it will show which bombers landed OK, were destroyed (KIA) or failed to make it back to base (MIA).
You can only see these details if the Show Bomber Group information option is on (this is the default).
