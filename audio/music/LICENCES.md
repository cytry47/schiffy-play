# Schiffy music files (D105)

The files in this folder, what they are and their licence. Below this table: the trial lane's download notes
(copied from Skills/schiffy-music/trial/LICENCES.md; file names there are the raw downloads, not these).

| File | Track | Licence | Credit |
|---|---|---|---|
| title.mp3 | The Charleston, Golden Gate Orchestra, 1925 (Edison 51542-R) | Public domain (US) | none required |
| overworld_hub.mp3 | Olde Timey, Kevin MacLeod | CC BY 3.0 | required (title screen) |
| overworld_island.mp3 | Sweet Georgia Brown, Ben Bernie Orchestra, 1925 | Public domain (US) | none required |
| story.mp3 | Mister Exposition, Kevin MacLeod | CC BY 3.0 | required (title screen) |
| boss_rat.mp3 | Dippermouth Blues, King Oliver, 1923 | Public domain (US) | none required |
| boss_moki1.mp3 | That Flying Rag, Arthur Pryor's Band, 1911 | Public domain (US) | none required |
| boss_moki23.mp3 | Swinging, Music-for-Videos (Pixabay) | Pixabay Content License (Content ID registered) | optional (title screen) |
| boss_cammy.mp3 | Super Circus, Kevin MacLeod | CC BY 3.0 | required (title screen) |
| boss_hanato.mp3 | Panama, New Orleans Rhythm Kings, 1922 | Public domain (US) | none required |
| boss_magpie.mp3 | Tiger Rag, Original Dixieland Jass Band, 1918 | Public domain (US) | none required |
| boss_stargazer.mp3 | Kitten on the Keys, Zez Confrey, 1921-22 | Public domain (US) | none required |
| boss_bruce.mp3 | Iron Horse, Kevin MacLeod | CC BY 3.0 | required (title screen) |
| sting_win.mp3 | end of Stars and Stripes Forever, Sousa's Band, 1909 | Public domain (US) | none required |
| sting_lose.mp3 | end of Krooked Blues, King Oliver, 1923 | Public domain (US) | none required |

Kevin MacLeod credit line: "Olde Timey", "Mister Exposition", "Super Circus", "Iron Horse" Kevin MacLeod (incompetech.com)
Licensed under Creative Commons: By Attribution 3.0 http://creativecommons.org/licenses/by/3.0/

---

# Trial files (downloaded 2026-10-25 on Ruben's yes, D105 A)

All from Wikimedia Commons. Total 18.7 MB. Not in the game.

| File | Source page | Licence | Credit line |
|---|---|---|---|
| olde_timey.mp3 (7.9 MB, 3:15, 320 kbps) | https://commons.wikimedia.org/wiki/File:Olde_Timey_(ISRC_USUAN1100126).mp3 | CC BY 3.0 | "Olde Timey" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 3.0 http://creativecommons.org/licenses/by/3.0/ |
| waltz_of_treachery.mp3 (1.5 MB, 0:41) | https://commons.wikimedia.org/wiki/File:Waltz_of_Treachery_(ISRC_USUAN1100018).mp3 | CC BY 3.0 | "Waltz of Treachery" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 3.0 http://creativecommons.org/licenses/by/3.0/ |
| bushwick_tarantella.oga (5.2 MB, 3:24) | https://commons.wikimedia.org/wiki/File:Bushwick_Tarantella_(MacLeod,_Kevin)_(ISRC_USUAN1300002).oga | CC BY 3.0 US | "Bushwick Tarantella" Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 3.0 US http://creativecommons.org/licenses/by/3.0/us/ |
| charleston_1925.mp3 (4.6 MB, 4:08; Wikimedia's MP3 transcode, the .ogg original timed out) | https://commons.wikimedia.org/wiki/File:Charleston_(1925)_-_Edison_51542-R.ogg | Public domain (US): composition 1923 (James P. Johnson), recording Edison 51542-R, 1925 | none required; courtesy: "The Charleston" (1925), Golden Gate Orchestra, Edison 51542-R |

## Round-3 picks (downloaded 2026-10-25 on Ruben's request; picks_raw/ = originals 64.9 MB, picks_clean/ = orig/light/strong MP3s)

All public domain in the US (recordings published before 1926, compositions before 1931). No credit required.

| File | Commons file | Recording |
|---|---|---|
| rat_dippermouth_blues.flac | File:Dippermouth Blues - KING OLIVER'S JAZZ BAND.flac | King Oliver's Jazz Band, 1923 |
| hanato_panama.mp3 | File:Panama - New Orleans Rhythm Kings (1922).mp3 | New Orleans Rhythm Kings, 1922, Gennett |
| moki1_that_flying_rag.ogg | File:Arthur Pryors Band-That Flying Rag.ogg | Arthur Pryor's Band, 1911, Victor 17021 |
| stargazer_kitten_on_the_keys.ogg | File:Zez Confrey - Kitten on the Keys.ogg | Zez Confrey, 1921-22 |
| magpie_tiger_rag.ogg | File:Tiger Rag ODJB.ogg | Original Dixieland Jass Band, 1918, Victor |
| lose_krooked_blues.ogg | File:King Oliver's Creole Jazz Band-- "Krooked Blues" (1923).ogg | King Oliver's Creole Jazz Band, 1923 |
| title_charleston.mp3 | (copy of files/charleston_1925.mp3) | Golden Gate Orchestra, 1925, Edison |

Cleanup (ffmpeg): light = `adeclick,highpass=60,afftdn=nr=12:nf=-40:tn=1,lowpass=7000`; strong = `adeclick x2,highpass=80,afftdn=nr=24:nf=-35:tn=1,lowpass=6000,eq 3 kHz +2 dB`.
| win_stars_and_stripes.ogg | File:Sousa's Band - Stars and Stripes Forever.ogg | Sousa's Band, 1909, Edison Amberol (final = last 4.5 s, strong cleanup) |
| moki23_swinging.mp3 | https://pixabay.com/music/acid-jazz-swinging-electro-swing-funny-catchy-151280/ (downloaded by Ruben) | Swinging, Music-for-Videos. Pixabay Content License (credit optional; no standalone redistribution; Content ID registered) |
