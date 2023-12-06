#  Reponse [ate]

## Commande passee

```bash

<span>$</span>  grep -i "star wars" sets.csv | sed -e 's/"\(.*\),\(.*\),\(.*\),\(.*\)"/\1\2\3\4/' -e 's/"\(.*\),\(.*\),\(.*\)"/\1\2\3/' -e 's/"\(.*\),\(.*\)"/\1\2/' | awk -F, '{print "| " $3 " | " $2 " |"}' | sort -t "|" -k2,2r | uniq  >>reponse-ate.md

```
# Resultat

| Annee | Nom de la boite |
| ----- | --------------- |
| 2024 | Star Wars: 800 Stickers |
| 2024 | Star Wars: Visual Dictionary: Updated Edition |
| 2023 | Hallmark Keepsake Christmas Tree Ornament - Star Wars The Mandalorian and Grogu |
| 2023 | Star Wars Advent Calendar 2023 |
| 2023 | Star Wars: Book of the Force |
| 2023 | Star Wars Collectible: Clone Wars E |
| 2023 | Star Wars: Galaxy Mission |
| 2023 | Star Wars: Kolorowanka z Naklejkami |
| 2023 | Star Wars Mech 3-Pack |
| 2023 | Star Wars. Największy Mistrz Jedi |
| 2023 | Star Wars: Official Annual 2024 |
| 2023 | Star Wars: Scouting Time |
| 2023 | Star Wars: Wanted: Bounty Hunter |
| 2023 | Star Wars: Where's Yoda |
| 2023 | Star Wars: Yoda's Galaxy Tour |
| 2023 | Star Wars: Zostań Bohaterem Galaktyki |
| 2022 | Build Your Own Star Wars Comic |
| 2022 | Exclusive Star Wars Landspeeder Print |
| 2022 | Limited Edition Star Wars UCS Print |
| 2022 | Star Wars Advent Calendar 2022 |
| 2022 | Star Wars: Awesome Vehicles |
| 2022 | Star Wars: Fun Time |
| 2022 | Star Wars: Fun To Colour |
| 2022 | Star Wars: Galactic Adventures |
| 2022 | Star Wars: Galactic Face-Offs |
| 2022 | Star Wars: Official Annual 2023 |
| 2022 | Star Wars: Smuggler Rebel Hero |
| 2022 | Star Wars: Stormtrooper Adventures |
| 2022 | Star Wars: The Skywalker Saga Deluxe Edition – Nintendo Switch |
| 2022 | Star Wars: The Skywalker Saga Deluxe Edition – PlayStation 4 |
| 2022 | Star Wars: The Skywalker Saga Deluxe Edition – PlayStation 5 |
| 2022 | Star Wars: The Skywalker Saga Deluxe Edition – Xbox Series X/S Xbox One |
| 2022 | Star Wars: The Skywalker Saga - PS4 |
| 2022 | Star Wars: The Skywalker Saga - PS5 |
| 2022 | Star Wars: The Skywalker Saga - Xbox Series X/S Xbox One |
| 2022 | Star Wars: Time to play! |
| 2021 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Darth Vader |
| 2021 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Stormtrooper |
| 2021 | Star Wars Advent Calendar 2021 |
| 2021 | Star Wars: Galactic Riddles |
| 2021 | Star Wars: Yoda's Galaxy Atlas |
| 2020 | DK Readers Level 2: Star Wars: The Rise of Skywalker |
| 2020 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Chewbacca |
| 2020 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Han Solo |
| 2020 | Star Wars Advent Calendar 2020 |
| 2020 | Star Wars: Amazing Starships |
| 2020 | Star Wars: Character Encyclopedia: New Edition |
| 2020 | Star Wars Collectible Cards |
| 2020 | Star Wars: Galaktyczne Zagadki |
| 2020 | Star Wars: Holiday Sticker Book |
| 2019 | Hallmark Keepsake Christmas Tree Ornament - Star Wars C-3PO |
| 2019 | Hallmark Keepsake Christmas Tree Ornament - Star Wars R2-D2 |
| 2019 | Star Wars 20th Anniversary Art Print |
| 2019 | Star Wars 20th Anniversary Lightsaber Poster (Blue) |
| 2019 | Star Wars 20th Anniversary Lightsaber Poster (Red) |
| 2019 | Star Wars Advent Calendar 2019 |
| 2019 | Star Wars: Brick Adventures: Awesome Jedi Tales |
| 2019 | Star Wars: Build Your Own Adventure: Galactic Missions |
| 2019 | Star Wars: C-3PO |
| 2019 | Star Wars: Darth Vader on the Rebel Hunt |
| 2019 | Star Wars Deluxe Drawing Gift Set |
| 2019 | Star Wars: From Planet to Planet: Sticker Activity Challenges |
| 2019 | Star Wars Naboo Starfighter Stationery Set |
| 2019 | Star Wars: Official Annual 2020 |
| 2019 | Star Wars Podracer Stationery Set |
| 2019 | Star Wars: Starship Pilots |
| 2019 | Star Wars: The Visual Dictionary: Anniversary Edition |
| 2019 | Star Wars: Visual Dictionary New Edition |
| 2018 | DK Readers Level 2 Star Wars - The Last Jedi |
| 2018 | Official LEGO Star Wars Annual 2019 |
| 2018 | Star Wars: 1001 Stickers - The Light Side Strikes Back |
| 2018 | Star Wars Advent Calendar 2018 |
| 2018 | Star Wars: Choose Your Path Be The Hero Discover The Galaxy! |
| 2018 | Star Wars: Giant Galactic Activity Book |
| 2018 | Star Wars: Great Galactic Battles |
| 2018 | Star Wars: Ideas Book |
| 2018 | Star Wars: Rätselspaß für kosmische Abenteurer |
| 2018 | Star Wars: Stories from the Galaxy |
| 2018 | Star Wars Stormtrooper Backpack |
| 2018 | Star Wars Storm Trooper School Bag Trolley |
| 2018 | Star Wars Surprise Box |
| 2018 | Star Wars: The Amazing Book of LEGO Star Wars |
| 2018 | Star Wars: The Best Friends in the Galaxy |
| 2018 | Star Wars: The Freemaker Adventures: Season Two [DVD] |
| 2018 | Star Wars: The Official Force Training Manual |
| 2018 | Star Wars: The Official Stormtrooper Training Manual |
| 2017 | DK Readers Level 1: Star Wars: Secrets of the Dark Side |
| 2017 | Star Wars Advent Calendar 2017 |
| 2017 | Star Wars: A New Galactic Hero |
| 2017 | Star Wars: Book of Mazes: With Stickers |
| 2017 | Star Wars: Galactic Freedom Fighters |
| 2017 | Star Wars: Han Solo's Adventures |
| 2017 | Star Wars: Legendes Van De Bouwmeesters |
| 2017 | Star Wars Mini Millennium Falcon |
| 2017 | Star Wars: Official Annual 2018 |
| 2017 | Star Wars: R2-D2 The Brave |
| 2017 | Star Wars: R2-D2 The Brave/Han Solo's Adventures: 2-in-1 Flip Over Reader |
| 2017 | Star Wars: Rebel Princess |
| 2017 | Star Wars: Rebels Forever |
| 2017 | Star Wars: Rise of the Rebellion |
| 2017 | Star Wars Super Pack 2 in 1 |
| 2017 | Star Wars: The Classic Collection Episodes I-VI |
| 2017 | Star Wars: Ultimate |
| 2016 | DK Readers Level 2: Star Wars: The Force Awakens |
| 2016 | Star Wars: 500 Reusable Stickers |
| 2016 | Star Wars Advent Calendar 2016 |
| 2016 | Star Wars: Build Your Own Adventure |
| 2016 | Star Wars: Choose Your Side: Doodle Activity Book |
| 2016 | Star Wars: Chronicles of the Force |
| 2016 | Star Wars Collection |
| 2016 | Star Wars: Droid Tales (DVD) |
| 2016 | Star Wars: Epic Space Adventures |
| 2016 | Star Wars Episode VII Poster |
| 2016 | Star Wars Microfighters Super Pack 3 in 1 |
| 2016 | Star Wars: Official Annual 2017 |
| 2016 | Star Wars: Phonics: Pack 1 |
| 2016 | Star Wars: Quest for the Kyber Saber |
| 2016 | Star Wars: R2-D2 and C-3PO's Guide to the Galaxy |
| 2016 | Star Wars: Read Build Play - Battle for the Stolen Crystals |
| 2016 | Star Wars: Ready Steady Stick: Cosmic Activity Book |
| 2016 | Star Wars: Ready Steady Stick: Intergalactic Activity Book |
| 2016 | Star Wars: Rebel Stories |
| 2016 | Star Wars: Spot The Galactic Heroes |
| 2016 | Star Wars: Strong with the Force |
| 2016 | Star Wars: The Force Awakens - 3DS |
| 2016 | Star Wars: The Force Awakens Deluxe Edition - PS3 |
| 2016 | Star Wars: The Force Awakens Deluxe Edition - PS4 |
| 2016 | Star Wars: The Force Awakens Deluxe Edition - Xbox One |
| 2016 | Star Wars: The Force Awakens: Prima's Official Guide |
| 2016 | Star Wars: The Force Awakens - PS3 |
| 2016 | Star Wars: The Force Awakens - PS4 |
| 2016 | Star Wars: The Force Awakens - PS Vita |
| 2016 | Star Wars: The Force Awakens - Wii U |
| 2016 | Star Wars: The Force Awakens - Xbox 360 |
| 2016 | Star Wars: The Force Awakens - Xbox One |
| 2016 | Star Wars: The Freemaker Adventures - Complete Season One |
| 2016 | Star Wars: The Freemaker Adventures - Complete Season One [with Magnets] |
| 2016 | Star Wars: Ultimate Factivity Collection |
| 2016 | Star Wars: Use The Force! |
| 2015 | DK Readers Level 2: Star Wars: Free the Galaxy |
| 2015 | DK Readers Level 3: Star Wars: Into Battle |
| 2015 | Star Wars Advent Calendar 2015 |
| 2015 | Star Wars Character Encyclopedia: Updated and Expanded |
| 2015 | Star Wars : Combats l'empire !- l'album des autocollants |
| 2015 | Star Wars Episode III Poster |
| 2015 | Star Wars Episode II Poster |
| 2015 | Star Wars Episode I Poster |
| 2015 | Star Wars Episode IV Poster |
| 2015 | Star Wars Episode VI Poster |
| 2015 | Star Wars Episode V Poster |
| 2015 | Star Wars in 100 Scenes |
| 2015 | Star Wars: Official LEGO Star Wars Annual 2016 |
| 2015 | Star Wars: Small Scenes from a Big Galaxy |
| 2015 | Star Wars Super Pack 3 in 1 |
| 2015 | Star Wars: The New Yoda Chronicles (DVD) |
| 2015 | Star Wars: The Power of the Jedi |
| 2015 | Star Wars: The Power Of The Sith Activity Book |
| 2015 | Star Wars: Ultimate Sticker Collection: Mighty Minifigures |
| 2015 | Star Wars: Vader's Secret Missions |
| 2015 | Star Wars Wall Stickers |
| 2015 | Star Wars X-wing Fighter |
| 2015 | Tatooine Mini-Build (Star Wars Celebration Version) |
| 2014 | DK Readers Level 1: Star Wars A New Hope |
| 2014 | DK Readers Level 2: Star Wars The Empire Strikes Back |
| 2014 | DK Readers Level 3: Star Wars Return of the Jedi |
| 2014 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Boba Fett |
| 2014 | Star Wars 2015 Pocket Calendar |
| 2014 | Star Wars Advent Calendar 2014 |
| 2014 | Star Wars Choose Your Side Key Chain |
| 2014 | Star Wars Microfighters Super Pack 3 in 1 |
| 2014 | Star Wars Poster |
| 2014 | Star Wars: Spot The Spy Droid |
| 2014 | Star Wars Super Pack 2 in 1 |
| 2014 | Star Wars Super Pack 3 in 1 |
| 2014 | Star Wars: The Dark Side |
| 2014 | Star Wars: These Aren't the Droids You're Looking For: A Search-and-Find Book |
| 2014 | Star Wars: The Visual Dictionary Updated and Expanded |
| 2014 | Star Wars: The Yoda Chronicles (DVD) |
| 2014 | Star Wars: The Yoda Chronicles Trilogy |
| 2014 | Star Wars:Ultimate Sticker Book: Darth Vader's Empire |
| 2014 | Star Wars: Ultimate Sticker Book: Yoda's Jedi Army |
| 2014 | Star Wars: Ultimate Sticker Collection: Choose Your Side! |
| 2014 | Star Wars Yoda Chronicles: The Battle Continues Poster |
| 2014 | Star Wars: Yoda's Secret Missions |
| 2013 | DK Readers Level 2: Star Wars: Attack of the Clones |
| 2013 | DK Readers Level 3: Star Wars: Revenge of the Sith |
| 2013 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Yoda |
| 2013 | Star Wars 2014 Pocket Calendar |
| 2013 | Star Wars Advent Calendar 2013 |
| 2013 | Star Wars: Brickmaster: Battle for the Stolen Crystals |
| 2013 | Star Wars Super Pack 3 in 1 |
| 2013 | Star Wars: The Empire Strikes Out |
| 2013 | Star Wars: The Empire Strikes Out - DVD |
| 2013 | Star Wars: The Yoda Chronicles |
| 2012 | DK Readers Level 2: Star Wars: The Phantom Menace |
| 2012 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Stormtrooper |
| 2012 | Star Wars Advent Calendar 2012 |
| 2012 | Star Wars Battle of Hoth |
| 2012 | Star Wars: Battle of Hoth Die Key Chain |
| 2012 | Star Wars Magnet Set |
| 2012 | Star Wars Poster |
| 2012 | Star Wars Super Pack 3 in 1 |
| 2012 | Star Wars: Ultimate Sticker Collection: Minifigures |
| 2012 | Star Wars ZipBin Toy Box & Playmat |
| 2011 | Armor Case Kit for Nintendo DSi - Star Wars III: The Clone Wars |
| 2011 | Hallmark Keepsake Christmas Tree Ornament - Star Wars Darth Vader |
| 2011 | Play and Build Kit for Nintendo DS - Star Wars - Anakin Skywalker |
| 2011 | Play and Build Kit for Nintendo DS - Star Wars - Obi Wan Kenobi |
| 2011 | Star Wars 3: The Clone Wars: Prima's Official Game Guide |
| 2011 | Star Wars Advent Calendar 2011 |
| 2011 | Star Wars Advent Calendar 2011 (San Diego Comic-Con Exclusive) |
| 2011 | Star Wars: Brickmaster |
| 2011 | Star Wars: Character Encyclopedia |
| 2011 | Star Wars III: The Clone Wars - 3DS |
| 2011 | Star Wars III: The Clone Wars - DS |
| 2011 | Star Wars III: The Clone Wars - PC DVD-ROM |
| 2011 | Star Wars III: The Clone Wars - PS3 |
| 2011 | Star Wars III: The Clone Wars - PSP |
| 2011 | Star Wars III: The Clone Wars - Wii |
| 2011 | Star Wars III: The Clone Wars - Xbox 360 |
| 2011 | Star Wars Magnet Set |
| 2011 | Star Wars Miniland Figures (Toy Fair 2011 Collector's Party) |
| 2011 | Star Wars Sith Kit |
| 2011 | Star Wars Super Pack 3 in 1 |
| 2011 | Star Wars: The Padawan Menace |
| 2011 | Star Wars: Ultimate Sticker Book: Heroes |
| 2011 | Star Wars: Ultimate Sticker Book: Villains |
| 2011 | Star Wars: Ultimate Sticker Collection |
| 2010 | Magnet Set Star Wars - Kit Fisto Barriss Offee Captain Jag |
| 2010 | Star Wars Magnet Set |
| 2010 | Star Wars Super Pack 3 in 1 |
| 2009 | Armor Case Kit for Nintendo DS - Star Wars |
| 2009 | LEGO Star Wars Holo-Brick Archives |
| 2009 | Magnet Set Star Wars |
| 2009 | Star Wars 10th Anniversary Stormtrooper Magnet |
| 2009 | Star Wars 10th Anniversary T-Shirt |
| 2009 | Star Wars Magnet Set |
| 2009 | Star Wars Stormtrooper T-Shirt |
| 2009 | Star Wars Super Pack 3 in 1 |
| 2009 | Star Wars: The Complete Saga - MAC DVD-ROM |
| 2009 | Star Wars: The Complete Saga - PC DVD-ROM |
| 2009 | Star Wars: The Visual Dictionary |
| 2008 | Star Wars Clock |
| 2008 | Star Wars Magnet Set |
| 2007 | Star Wars II: The Original Trilogy - MAC-DVD |
| 2007 | Star Wars Magnet Set |
| 2007 | Star Wars Magnet Set: Darth Maul Anakin and Naboo Fighter Pilot |
| 2007 | Star Wars: The Complete Saga - DS |
| 2007 | Star Wars: The Complete Saga: Prima's Official Game Guide |
| 2007 | Star Wars: The Complete Saga - PS3 |
| 2007 | Star Wars: The Complete Saga - Wii |
| 2007 | Star Wars: The Complete Saga - Xbox 360 |
| 2006 | Star Wars 2: The Original Trilogy: Prima's Official Game Guide |
| 2006 | Star Wars II: The Original Trilogy - DS |
| 2006 | Star Wars II: The Original Trilogy - Game Boy Advance |
| 2006 | Star Wars II: The Original Trilogy - Gamecube |
| 2006 | Star Wars II: The Original Trilogy - PC CD-ROM |
| 2006 | Star Wars II: The Original Trilogy - PS2 |
| 2006 | Star Wars II: The Original Trilogy - PSP |
| 2006 | Star Wars II: The Original Trilogy - Xbox |
| 2006 | Star Wars II: The Original Trilogy - Xbox 360 |
| 2006 | Star Wars Magnet Set |
| 2006 | Star Wars Value Pack |
| 2005 | Lego Toy Fair 2005 Star Wars V.I.P. Gala Set |
| 2005 | Star Wars Classic Vehicles Bonus Pack |
| 2005 | Star Wars Co-Pack Classic Vehicles Bonus Pack |
| 2005 | Star Wars / M&M Mosaic - Promo Set |
| 2005 | Star Wars: Prima's Official Game Guide |
| 2005 | Star Wars: The Video Game - Game Boy Advance |
| 2005 | Star Wars: The Video Game - Gamecube |
| 2005 | Star Wars: The Video Game - MAC CD-ROM |
| 2005 | Star Wars: The Video Game - PC CD-ROM |
| 2005 | Star Wars: The Video Game - PS2 |
| 2005 | Star Wars: The Video Game - Xbox |
| 2005 | Star Wars Value Pack |
| 2004 | Star Wars Co-Pack |
| 2004 | Star Wars Miniatures Kit III |
| 2003 | Star Wars Miniatures Kit I |
| 2003 | Star Wars Miniatures Kit II |
| 2003 | Star Wars MINI Bonus Pack |
| 2003 | Star Wars Value Pack with Free LEGO Backpack |
| 2002 | Star Wars Co-Pack |
| 2002 | Star Wars Episode II Co-Pack |
| 2001 | Star Wars Co-Pack |
| 2000 | Star Wars #1 - Sith Minifig Pack |
| 2000 | Star Wars #2 - Luke/Han/Boba Minifig Pack |
| 2000 | Star Wars #3 - Troopers/Chewie Minifig Pack |
| 2000 | Star Wars #4 - Battle Droid Minifig Pack |
| 2000 | Star Wars Co-Pack |
| 2000 | Star Wars Minifig Packs 4-Pack |
| 2000 | Star Wars Podracing Bucket |
