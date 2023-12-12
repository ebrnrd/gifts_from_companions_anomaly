# Gifts From Companions - S.T.A.L.K.E.R. Anomaly Addon

Go to [releases](https://github.com/ebrnrd/gifts_from_companions_anomaly/releases) to download

<h1>Description</h1>
A simple addon that gives your companions the ability to give you gifts from time to time. The gifts are chosen randomically from different tables based on your squad "friendship".

<h2>Friendship system</h2>
You and your companions will develop friendship by killing enemies and surviving the Zone. The friendship level is increased passively every X seconds. When your squad kills an enemy stalker or mutant the friendship increases. If one or more of your companions die, your friendship decreases. When you don't have any more companions your friendship is reset to 0. I still don't know if "friendship" is the right word to use but I'll figure it out later.

The gifts_tables include handpicked game items, the categories are: FOOD, DRINK, MEDICAL, DEVICE (PDAs), TOOL, REPAIR(Repair tools for weapons and outfits), MISC (Junk) and AMMO. I'm still working on the list, it is a tedious job and if you have suggestions about which items to add just let me know.
You can change these list if you want in the file gfcmod_tables.script inside the scripts folder.

Your companions will also say a random sentence while giving you the gift, I will add more in the future.

The mod is in english and partially translated to russian.

<h1>MCM settings:</h1>
min_timer: the minimum time that needs to pass before receiving another gift (seconds) (default = 300
max_timer: the maximum time that can pass before receiving another gift (seconds) (default = 600)
friendship_timer: the time between each passive friendship increment (seconds) (default = 900)
gift_chance: the chance of receiving said gift when the time comes (default = 0.2)

This is my first ever mod so it's bound to have some errors but I hope nothing game breaking. If you find some bugs or have some requests feel free to let me know in the comments.

<h1>How to install</h1>

Simply extract and copy the gamedata folder in your Anomaly installation (where the game's "gamedata" folder is located).
For MO2 simply install the mod using the 7z file provided.

<h1>Credits</h1>

Thanks to Darkasleif and their Chatty Companions Addon that I used to figure out what I was even doing.
I love to see some love for our not-so-smart-but-kind companions.

<h1>Changelog</h1>
<h2>v0.0.4</h2>

Added a friendship system, now gifts are based on the friendship level and note your stalker reputation

Added a notification system for the friendship level changes

Decreased the mod intervals to have more reactive notifications

Now the code is a bit more complicated so crashes could happen more easily, I didn't encounter any.

<h2>v0.0.3</h2>
Added russian translations thanks to forsiid

Added a debug option that shows at regular intervals the time passed and the time to reach to receive the gift (i need it for debugging don't worry about it)

<h1>Future plans</h1>
Interactions with your squad companions to improve your friendship level
