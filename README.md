# Girls' Frontline Discord Search
Search a doll from Girls' Frontline within Discord. [Click to invite to your server](https://discordapp.com/oauth2/authorize?client_id=351447700064960522&scope=bot&permissions=0)

Features:
- Type, Base Stats, Max Stats, How To Obtain, Production Requirement, Ability, Ability Cooldown, Tile Bonus, Tile Bonus information.
- placebo recipies and estimated drop rates for rare dolls.
- Embed color matches star color
- Links to the corresponding doll page on https://en.gfwiki.com
- Flavor text, or adjudant quotes if there is no flavor text.
- Images for almost every doll... Assuming you ripped the images from the game files.
- Aliases. Ex. HKM4 -> HK416
- Fuzzy search that will return the closest result and suggest other results.

Coming eventually:
- $gfimage costume support
- $gffilter for finding the best doll in a type.
- $gfsearch flags for only showing the relevant part of an embed.

## Commands
Assuming that that the default prefix $gf is still being used:
- $gfsearch: Search a doll
- $gfimage: Display only the image for that doll.
- $gfhelp: List commands, version, how to contact me, etc.
- $gfquote: Show quotes from the dolls if you have CharacterVoice.json from the game files
- $gfstatus: Number of servers this bot is in.

## Prerequesites
Python3 and pip. Game files need to be extracted if you want images and quotes.

To extract files: https://github.com/36base/girlsfrontline-resources-extract

## Setup
**This bot was written for a very old version of Discord.py, it probably will not work out of the box**
1. `git clone https://github.com/RhythmLunatic/Girls-Frontline-Discord-Search.git`
2. edit main.py, insert your discord bot token in DISCORD_TOKEN
3. Change COMMAND_PREFIX to whatever you want, the default is $gf
4. If you have your own server containing the dumped girls frontline images, change PIC_DOMAIN, otherwise you can keep using mine.
5. `pip3 install discord` (Windows users, the command might be 'pip' instead of pip3)
6. `chmod +x run_forever.sh` (Windows users, you're on your own)
7. `./run_forever.sh` if linux, otherwise `python3 main.py`.


## Screenshot
![GFSearch Command](https://i.imgur.com/QAkHNF5.png)

## Legal stuff
main.py is GPL, read LICENCE for more information.

THIS PROGRAM IS NOT ENDORSED BY https://en.gfwiki.com. ALL DATA CONTAINED WITHIN girlsfrontline.json IS Ⓒ https://en.gfwiki.com AND LICENCED UNDER CC BY-SA 3.0. For more information, please read gf_json_LICENCE.
