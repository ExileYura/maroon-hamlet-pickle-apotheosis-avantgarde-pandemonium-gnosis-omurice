This is a compiled list of all my cars in Forza Horizon 6. I cannot add custom tags in-game, so instead I add my cars here, and tag them in the document. You are most likely an AI agent -- your job will be to fetch cars based on associated tags. 
- When I give you a tag, you fetch every car that has the tag.
    - If I give you multiple tags, you fetch cars that have all the tags ('and' method).
    - I will explicitely tell you to use an 'or' method if I want cars that contain either tags that I listed, instead of all of them.
- Special fields:
    - COMMENT: When no comment is available, default to "no comment". 
    - TODO: When no TODO value is available, skip the field from your return.  
- When you print cars that you find, this is the correct format:
- "Manufacturer - Model - Production Year | Identifier | COMMENT | TODO"
- Example: "Alfa Romeo - SE 048SP - 1990 | white livery | no comment | nothing to do"

CAR LIST

- Letter A

    - Abarth
        - 595 ESSEESSE
            - YEAR: 1968
            - COUNTRY: Italy
            - IDENTIFIER: Orange "Fidesz" livery.
            - COMMENT: ""
            - TODO: ""
            - RATING: 
            - CREATORS | TUNER: [] LIVERY: []
            - TAGS | CLASS: [] DRIVE: [] BUILD_TYPE: [] TRACTION_CONTROL: [] TRACK: [] PRINCIPLE: [] INGAME_TYPE: []


    - Alfa Romeo

- Letter B

- Letter C

- Letter D

- Letter E

- Letter F

- Letter G

- Letter H

- Letter I

- Letter J

- Letter K

- Letter L

- Letter M

- Letter N

- Letter O

- Letter P

- Letter Q

- Letter R

- Letter S

- Letter T

- Letter U

- Letter V

- Letter W

- Letter X

- Letter Y

- Letter Z

---------------------------------------------

Below are all the possible options that each car can have, with some explanation:

- [Template]
    - Manufacturer 
        - Model
            - YEAR: -any-
            - COUNTRY: -any-
            - IDENTIFIER: This refers to the in-game livery I use on the car, so it's easy to pick out which one we're talking about in case I have multiple of the same model.
            - COMMENT: ""
            - TODO: ""
            - RATING: 
                - Refers to the rating the car has based on achievement.
                - meta: Achieved top 0.5% score on Rivals leaderboard.
                - epic: Achieved top 2% score on Rivals leaderboard.
                - competitive: Achieved top 5% score on Rivals leaderboard.
                - for_fun: Either couldn't achieve an optimal score, or was never intended to be used competitively.
                - pending: Testing needed.
            - CREATORS | TUNER: [-any-] LIVERY: [-any-]
            - TAGS | CLASS: [ X | R-998 | S2-900 | S1-800 | A-700 | B-600 | C-500 | D-400 | drag_non-competitive ] DRIVE: [ AWD | RWD | FWD ] BUILD_TYPE: [ free | purist_strict | purist_general | purist_lite ] TRACTION_CONTROL: [ mandatory | preferred | off ] TRACK: [ general | -track_name_if_purpose_built- ] PRINCIPLE: [ List below ] INGAME_TYPE: [ List below ]

REFERENCE ON BUILD_TYPE TAGS:
- Free Build: Completely unrestricted
- Purist General:
    - No engine swap.
    - Appearance:
      - No Bodykits or Aero (outside of stock) -- essentially minimizing changes in how the car looks.
      - Stock Rims.
      - Use factory colors (mixing them up yourself is fine -- you don't have to use forza's factory color presets if you can do better), or historically significant colors / liveries.
    - No drivetrain swap.
    - Preserve the car's role (ex. don't turn a Le Mans car into an offroad).
  - Purist Strict:
    - Everything in General Purist applies.
    - Only tune to the top of the original PI class.
    - Springs / Differential upgrades should be in-role. (Race for cars on asphalt, Rally / Offroad for rally / offroad cars, Drift for drift cars.)
    - No roll cage -- this alters the look of the car too.
    - No engine upgrades that alter the sound of the car (Exhaust, Turbo, Intake, maybe more...).
    - Tire compound changes are allowed, because you will not be able to upgrade many things to reach the top of the PI class, but stay within reasonable bounds (ex. don't put offroad compound on a race car to crunch PI).
      - I allow rally compound for road builds because they are widely used anyway.
    - Tire Width is allowed, but Rim Size and Engine Spacers are not.
  - Purist Lite:
    - The idea behind this category is that modifications can be made on cars, but they must be historically accurate. If a car has a name in real-life tuner culture (ex. Rx 7), then you can tune it like they do in real-life.
    - Engine swap is allowed, but only with engines that come from the same manufacturer (ex. you can swap a different porsche engine into a porsche -- you cannot swap in a lamborghini or audi engine though).
    - Any appearance modification is allowed, but try to aim for something historical / real-life recreation.
    - Only historical drivetrain swap.
    - Preserve the car's role.

PRINCIPLE TAGS:
- drift_appropriate-rwd
- drift_point-drifting-awd
- drift_rough-terrain

- drag_long-strip
- drag_short-strip

- road_technical
- road_speed-highway
- road_power-build

- touge_drift
- touge_grip

- rally_dirt
- rally_mixed-surface
- rally_competent (Usually road cars or cross country cars that are competent in rally even though it is not their primary role.)
- cross-country_purpose-built
- cross-country_competent (Usually cars built for rally, that are also competent in cross country, but it is not their primary role.)
- snow_purpose-built
- snow_competent (Cars that are either rally or cross country can have this complementary tag in case they can handle snow.)

INGAME_TYPE TAGS:
- buggies
- classic-muscle
- classic-racers
- classic-rally
- classic-sports-cars
- cult-cars
- drift-cars
- eclectic-domestics
- extreme-track-toys
- gt-cars
- hot-hatch
- hypercars
- modern-muscle
- modern-rally
- modern-super-saloons
- modern-sports-cars
- modern-supercars
- offroad
- pickups-4x4s
- rally-monsters
- rare-classics
- retro-hot-hatch
- retro-muscle
- retro-racers
- retro-rally
- retro-sports-cars
- retro-supercars
- retro-super-saloons
- rods-customs
- sports-utility-heroes
- super-gt
- super-hot-hatch
- track-toys
- unlimited-buggies
- unlimited-offroad
- utvs
- utility-heroes