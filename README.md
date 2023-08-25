# TS3Fixes

+ Fixes for The Sims 3
+ For modifications that are not numeric / changeable in NRaas Returner

## Installation

1. See below for changes
2. Go to the [Packages](https://github.com/VMPYRC/TS3Fixes/tree/main/Packages) folder
3. Download the packages you want
4. Move to your Mods folder
5. Play. Enjoy. Report issues [here](https://github.com/VMPYRC/TS3Fixes/issues)

# Changes

## AcademicDegrees_Expanded

+ SkillsThatGrantXP = 0.01
+ Business
  + AssociatedOccupationNameEnum -- Added SportsAgent
  + Beneficial Traits -- Added BornSalesman
  + SkillsThatGrantXP -- Added Bartending, Logic, Writing
+ Communications
  + AssociatedOccupationNameEnum -- Added Education
  + Beneficial Traits -- Added Charismatic, Diva, Flirty, Friendly, GoodSenseOfHumor, Irresistible, Perceptive, PhotographersEye
  + SkillsThatGrantXP -- Added Charisma, SocialNetworking
+ Fine Arts
  + AssociatedOccupationNameEnum -- Added ArtAppraiser
  + Beneficial Traits -- Added Bookworm, Dramatic, PhotographersEye, Rebellious, Rocker, Virtuoso
  + SkillsThatGrantXP -- Added Bartending, Dancing, LaserHarp, Photography, Writing
+ PhysEd
  + AssociatedOccupationNameEnum -- Added Criminal, SportsAgent
  + Beneficial Traits -- Added Burglar, Evil, Kleptomaniac, LovesTheOutdoors, LovesToSwim, Sailor
  + SkillsThatGrantXP -- Added Diving, ScubaDiving, Skating, Snowboarding, Waterskiing, Windsurfing
+ Science
  + AssociatedOccupationNameEnum -- Added Astronomer
  + Beneficial Traits -- Added Bookworm, Perceptive, Perfectionist, SociallyAwkward
  + SkillsThatGrantXP -- Added Alchemy, Future, Logic
+ Technology
  + AssociatedOccupationNameEnum -- Added BotArena, GameDeveloper
  + Beneficial Traits -- Added BotFan, Brave, ComputerWhiz, Daredevil, Eccentric, Good, Handy, NoSenseOfHumor, Workaholic
  + SkillsThatGrantXP -- Added BotBuilding, Hacking, VideoGame

## AutoVenuePlacement_Disabled

+ Disabled the Auto Venue Placement that occurs when starting a new save game with specific worlds / expansions

## Books_AddedEP11

+ Added CodeVersion = EP11

## CASCameras_Expanded

1. Go to this [commit](https://github.com/VMPYRC/TS3Fixes/commit/4f57d42f38897ad548ce2b233fc442d56cdc1564)
2. Click "Load Diff" for the .ini files
3. View changes
4. TLDR: Better CASCamera

## Careers_Fast

+ DayLength = 0.5
+ DowntownDayLength = 0.5

## Fishing_Easy

+ AvgLength = 1
+ CanBuyFromStore = True
+ GlobalSpawner
  + Probability = 100, None = 1
+ Spawner
  + ActiveProbability = 100, None = 1
  + InactiveProbability = 100, None = 1

## Inventing_Fast

+ MinTime = 1
+ MaxTime = 2

## Opportunities_Easy_NonRepeatable

+ Career Requirements = 1,MaxNumber
+ ChanceToGetOnPhone = 5
+ Removed all RepeatLevel = Always
  + Except for OncePerHousehold (Unchanged)
+ Replaced Celebrity Requirements to 0,5
+ Skill Requirements = 0,MaxNumber
  + EXCEPT THESE, WHICH ARE -1,0
    + EP1_CareerAthletic_LearnMartialArts
    + EP1_CareerCriminal_LearnMartialArts
    + EP1_CareerJournalism_LearnPhotography
    + EP1_CareerMilitary_LearnMartialArts
    + EP1_CareerPolice_LearnMartialArts
    + EP1_CareerPolice_LearnPhotography
+ Skill Challenge -- Laser Harp Star
  + Added monetary values of 1,000 or 500 Simoleons
  + TargetInteractionLength = 1

## Photography_Fixed

+ BadPhotoChance = 0
+ Dropa Stones fix
+ Theatre fix

## RecipeMasterList_Expanded

+ All Meals are available for Breakfast, Brunch, Lunch, and Dinner
+ Ambrosia can be a Group Serving
+ These are Desserts:
  + BakedAngelFoodCake
  + BellagianWaffles
  + BrownieCaramel
  + BrownieChocolate
  + Cake
  + Cake Slice
  + CakeChocolate
  + CakeVanilla
  + CheesePlate
  + ChocolateMiniGnome
  + Cobbler
  + CookieChocolate
  + Cookies
  + CookieSugar
  + Crepe
  + CupcakeChocolate
  + CupcakeVanilla
  + FrenchToast
  + FriedPeanutButterBanana
  + FruitParfait
  + KeyLimePie
  + Muffin
  + MuffinBlueberry
  + MuffinVanilla
  + Pancakes
  + PeanutButterAndJelly
  + Pie
  + PumpkinPie
  + SphereOfDestiny
  + Wedding Cake
  + Wedding Cake Slice
