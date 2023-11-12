# EasyRPG Compatibility List
Compatibility list of games when using the EasyRPG Player.  
In case a game does not work as you may want, consider using the executable given with your game, since not every RPG_RT patch or custom EasyRPG build will be able to be supported.  
Completable means that the game can be completed or that the entirety of the game can be seen if there is no ending (or if the game has a critical bug blocking a part of the content even in the RPG_RT).  
Playable means that the game was tested but was not completed by said user, or that it is blocking at some point if mentioned in the details.



Completable
========
.flow  
A Vacation In Nebula (En)  
A Vacation In Nebula (Es)  
Amillusion  
Answered Prayers  
Astral Guard Table Talk  
box (En)  
BRAINGIRL  
colorful. (En)  
CONFINIUM Act 1  
dream book  
Dream Genie  
Eret Link  
Face Maker  
Floppa Cube Vs. Bingus Cube  
Grimm's Hollow (En Steam) 
Grimm's Hollow (En itch.io)  
Grimm's Hollow (Es_Es)  
Grimm's Hollow (Es_Us)  
Grimm's Hollow (Pt_Br)  
Grimm's Hollow (Ru)  
Ipomoea  
KILLER BEAR (En)  
KILLER BEAR (Fr)  
Metallic Metronome  
Mikan Muzou (Ja)  
Moshimo Smash Brothers Dattara  
nighttime beats to chill and study to  
Someday  
Super Mario Death Row 2 - Shroomshank Redemption  
Super Mario Death Row!  
The Gray Garden  
Toilet in Wonderland  
Yume Nikki  
Yume no Kirby  
Zelda The Oak Quest  


Playable (details)
========
Detectivus Scitus - Ineluki keyboard not supported on every platform (could be more than that)


Completable with minor issues
========
1899 London Gothic Demo - Sound with .link files (zug-nachts-entfernt, zzz-ripper, demon-fly-by-1) are not supported  
Deep Dreams - uses a custom RPG_RT with a custom font that is not loaded  
Don's Adventures - Russian language for the encoding not detected (English/Russian game)  
Helen's Mysterious Castle - Boss defeat animation not correctly displayed (use of out of range transparency values, see section Transparency overflow on a picture on issue [#1486](https://github.com/EasyRPG/Player/issues/1486))  
Gray Garden The - midi struggles sometimes for the Blancblack Castle  
Grimm's Hollow (Ja) - ExFont not loaded since the real executable is not the RPG_RT.exe present; Display issue when attacking (see issue [#2972](https://github.com/EasyRPG/Player/issues/2972))  
Grimm's Hollow (Zh_Cn) - ExFont not loaded since the real executable is not the RPG_RT.exe present  
Muma Rope (v4) - The title picture is incorrectly displayed due to being interlaced (see issue [#2984](https://github.com/EasyRPG/Player/issues/2984))   
Muma Rope (v32.1 and +) - The R-Maze map is not randomized due to the lack of generate dungeon (see issue [#2474](https://github.com/EasyRPG/Player/issues/2474)); the Black Water sounds are crispy (see issue [#3045](https://github.com/EasyRPG/Player/issues/3045))  
[Mikan Muzou (En) (v0.2)](http://www.mediafire.com/file/40ua4esu1l79get/) - Japanese language for the encoding not detected (English translation of a Japanese game)  
Kodomo-tachi no kuni Magic Children (子供たちの国-Magic Children-) - character ㌧ not displayed with the internal font  
[Baty's flower story (こうもりさんの花物語)](https://w.atwiki.jp/viprpg23s/pages/21.html) - Japanese language for the encoding not detected (the game seems to only use Japanese for the title of the window, no filenames or nothing in-game)
Octillery Social Test DX - uses Languages folder and not Language, no longer compatible since version 0.8.1 (EasyRPG game)  
Outotsu Yume (v0.01) - Invalid skill on title screen displayed (see issue [#2977](https://github.com/EasyRPG/Player/issues/2977))  
Project Rose - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Steamed Hams, but it's RPGMAKER2003! - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036));  
[Rumia in the darkness (Ja)](https://store.steampowered.com/app/1060240/Rumia_in_the_darkness/) - Simplified Chinese for the encoding not detected (Even if it's a Japanese language game, the encoding should be Simplified Chinese)  
[Tetris](https://www.rpg-maker.fr/index.php?page=jeux&id=206) - Music 8 Gerudo Song can struggle to play  
The Adventures of Meatball Dog - Invalid party member when starting a new game (see issue [#3008](https://github.com/EasyRPG/Player/issues/3008))  
[Ultra Violet (Ja)](https://twitter.com/Switch_foot2312/status/1177564993375522822) - \\ character incorrectly displayed as a \\ instead of a yen in the Shrine (see issue [#3066](https://github.com/EasyRPG/Player/issues/3066))  
Uneven Dream - Incorrect tile ID incorrectly handled in a specific map (see issue [#3070](https://github.com/EasyRPG/Player/issues/3070))  
Yume 2kki - The autoplay feature of the Sound Room does not work correctly due to an issue with MIDI play ticks (see issue [#3047](https://github.com/EasyRPG/Player/issues/3047)); some audio bitrates cause issues to the RPG_RT making the Player have different results (see issue [#3044](https://github.com/EasyRPG/Player/issues/3044)); more colors than 256 leading to unintended display issues (see issue [#3043](https://github.com/EasyRPG/Player/issues/3043)); Some System have their $ window transparency incorrect (see issue [#3012](https://github.com/EasyRPG/Player/issues/3012)); visual issues when moving pictures at the same time on the edges (see issue [#2928](https://github.com/EasyRPG/Player/issues/2928)); some transitions cause crashes on mobile (see issue [#2593](https://github.com/EasyRPG/Player/issues/2593))  
[Yume Nikki 16_9](https://poyouli.itch.io/yumenikki169) - loop command lags a lot the player on the title screen, use of Rewrite Map (Maniac command) as an easter egg somewhere  


Playable with minor issues
========
3 AM Cathrath - specific fonts used for string pictures  
8 Bit Quest - title screen not skipped (could be more)  
Alive - patch to skip the title screen not supported  
Barkley, Shut Up And Jam Gaiden - Incorrect timing for the actions while in battle (see issue [#2991](https://github.com/EasyRPG/Player/issues/2991))  
Corpse Casino - uses unsupported commands of the Maniac Patch  
Dragon Ball Z: Legend of Z RPG - uses DynRPG and has stats higher than the usual  
Dollmaker and the 100 Alices - specific fonts used for string pictures  
Ex.Emi - more colors than 256 leading to unintended display issues (see issue [#3043](https://github.com/EasyRPG/Player/issues/3043))  
Farethere City (En) - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Fifth Era - title screen not skipped, custom title screen with load function not working, commands.ini file present  
Final Fantasy Blackmoon Prophecy Plus - may use dynrpg (not checked where) and some stats are above the usual maximum  
Final Fantasy Dog - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Final Fantasy Time and Again - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Houkago Meikyuubu After School Dungeon Club - uses unsupported commands of the Maniac Patch  
Ib - a Movie is played mid-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Ib (Fr) - French language for the encoding not detected (French translation of a Japanese game); a Movie is played mid-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Ian El Benjamin Arrugado (Ian, El Benjamín Arrugado) - uses Game.ini in addition to RPG_RT.ini; Game need to be extracted from its zip due to an encoding issue not letting you go to its folder  
Lament Incarnation of the Goddess - specific fonts used for string pictures  
LanVodis - Invalid skill on title screen displayed (see issue [#2977](https://github.com/EasyRPG/Player/issues/2977))  
Lavender (Ko) - ExFont not loaded  
Legend of Heroen - Ineluki commands  
LOTUS EATER PRINCESS Book 1 ½ - specific fonts used for string pictures  
LOTUS EATER PRINCESS Book I - specific fonts used for string pictures  
Mega Dream (v0.2) - Japanese language for the encoding not detected (English/Japanese game)  
Neo Jado Episode One Complete - Invalid IDAT image (see issue [#856](https://github.com/EasyRPG/Player/issues/856))  
Nepheshel (Ja) - Invalid IDAT image for the System graphic making it use the default one instead (see issue [#856](https://github.com/EasyRPG/Player/issues/856))  
Ocean OI - healing mp skill does not work correctly (see issue [#2848](https://github.com/EasyRPG/Player/issues/2848))  
Ollimio - uses dynrpg (custom title screen with load, save that don't work, different battle system (?))  
Phantasia 5 - dynrpg listed (game_clock, faster_atb, noautobattle and more in the default folder), issues can be expected  
Project Rose - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
Re In - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
[Rumia in the darkness (Ja)](https://store.steampowered.com/app/1060240/Rumia_in_the_darkness/) - Simplified Chinese for the encoding not detected (Even if it's a Japanese language game, the encoding should be Simplified Chinese)  
Witch's Heart - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  
[Yume 2kki (Es) (v0.107 patch 1)](https://www.dropbox.com/s/f5oi69g7qjxvwoi/Yume2kki%20-%20Spanish%20Translation.zip?dl=0) - this version is a mess: uses an encoding for Spanish text since accents are used, but there is still a lot of lines in Japanese so they can't properly be displayed, and the files called are also in Japanese so they can't be properly called (EasyRPG game)  
[Yume 2kki (Zh_Cn)](https://tmp.link/f/62da409de54e8) - Simplified Chinese keyboard not accurate  
Zelda Link's Awakening - a Movie is played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036))  


Playable with major issues
========
A New HOME - display issue during a fall transition making the player not visible (see issue [#2969](https://github.com/EasyRPG/Player/issues/2969)); uses a patch to skip the title not handled and load on said title does not work  
Aedemphia (Aëdemphia) - Movies are played in-game (see issue [#1036](https://github.com/EasyRPG/Player/issues/1036)), the game has performance issues due to an heavy huge of pictures and tints (see issue [#2842](https://github.com/EasyRPG/Player/issues/2842))  
[Beloved Rapture (Demo)](https://store.steampowered.com/app/2017620/Beloved_Rapture/) - uses unsupported commands of the Maniac Patch (Set Game Option; String Picture bad text argument; Expression contains unsupported operation 34); custom resolution not being a multiple of 16  
Buried Barry (Zh_Cn) - requires a password in-game that cannot be typed due to the keyboard not being supported (see issues [#2522](https://github.com/EasyRPG/Player/issues/2522) and [#2656](https://github.com/EasyRPG/Player/issues/2522))  
Buried Barry (Zh_Tw) - requires a password in-game that cannot be typed due to the keyboard not being supported (see issues [#2522](https://github.com/EasyRPG/Player/issues/2522) and [#2656](https://github.com/EasyRPG/Player/issues/2522))  
[Ib (Thai)](https://wez.in.th/game/ib) - uses a custom Player to be able to display the characters (was done before official support), so may need a font to display them  
Ib (Zh_Cn) - requires a password in-game that cannot be typed due to the keyboard not being supported (see issues [#2522](https://github.com/EasyRPG/Player/issues/2522) and [#2656](https://github.com/EasyRPG/Player/issues/2656))  
Labyrinth of Poverty (Zh_Cn) - requires a password in-game that cannot be typed due to the keyboard not being supported (see issues [#2522](https://github.com/EasyRPG/Player/issues/2522) and [#2656](https://github.com/EasyRPG/Player/issues/2656))  
[Medievil 2D](https://mackvalentine.itch.io/medievil-2d) - uses unsupported commands of the Maniac Patch  
Muma Rope (v32.0 and -) - The R-Maze map crashes the game on visit due to the lack of generate dungeon (see issue [#2474](https://github.com/EasyRPG/Player/issues/2474)); the Black Water sounds are crispy (see issue [#3045](https://github.com/EasyRPG/Player/issues/3045))  
Nehan II Darkness Fantasy - Invalid IDAT image for the ChipSet making your character not being able to be seen (see issue [#856](https://github.com/EasyRPG/Player/issues/856))  
Nightmare Game Secret Memory (Zh_Cn) - requires a password in-game that cannot be typed due to the keyboard not being supported (see issues [#2522](https://github.com/EasyRPG/Player/issues/2522) and [#2656](https://github.com/EasyRPG/Player/issues/2656))  
[The Gray Garden (Vi)](https://gametungtrai.blogspot.com/2023/10/blog-post_21.html) - Text not properly displayed due to the use of a different font for some characters  
[THUNDER WINDY](https://viprpg2020kohaku.xxxxxxxx.jp/entry16.html) - Maniac patch game, Set Game Option used to make the game be faster (so extremely slow on the Player), Change Picture IDs used  


Unplayable
========
[Frozen Triggers (風呂鳥)](https://w.atwiki.jp/vipkohaku2021/pages/122.html) - Maniac: Expression contains unsupported operation 34 & 67; Font no found; Conditional Branch 16 unsupported; Key Input Process EX; Global Save; the game is stuck on startup  
Oneshot - Uses a custom RPG_RT made specifically for the game; the continuous build does not support it but a [fork is available](https://github.com/20kdc/EasyRPG-Player-OneShot-Legacy)  
[Rogue](https://mackvalentine.itch.io/rm-rogue) - uses a custom build of the Player with new commands making it not compatible  
[Suika's drunk runaway](https://poyouli.itch.io/suikas-drunk-runaway) - uses unsupported commands of the Maniac Patch to generate maps (Rewrite Map and Set Game Option); request the Arial font  
[Super Mario Portal](https://www.rpg-maker.fr/index.php?page=jeux&id=877) - patch to skip title screen unsupported; game made with PowerMode 2003 using unsupported commands making it impossible to go after the titlescreen and play  
[Super Pokemon Eevee Edition](http://dreammodule.com/?spee) - uses unsupported commands and content of DynRPG making fights having incorrect options disallowing you to flee, and the intro does not work correctly  


Cannot be launched (protection)
========
[DEEP 8](https://store.steampowered.com/app/1037460/DEEP_8/)  
[OFF (Ru)](https://www.zhupel.com/p/offrus.html) - Bundled with Enigma  
[Saint Seiya -The Myth]( https://saint-seiya-team.itch.io/ilmito)  
[Skolio (En)](https://skoliosthegame.wordpress.com) - Bundled with Enigma  
[Skolio (De)](https://skoliosthegame.wordpress.com) - Bundled with Enigma  
[The Sacred Tears TRUE](https://store.steampowered.com/app/316840/The_Sacred_Tears_TRUE/) (uses a custom RPG_RT.lmt considered as corrupted by a normal RPG_RT, but uses a custom launcher to bypass this)  
[Victorian Fear - First Chapter](https://pixelgaiden.itch.io/victorian-fear-download)
