## Nutburgers Mod


### How to run the Mod

1. Create a folder inside your Diablo 2 Resurrected directory called `mods`
2. Create a folder within the `mods` folder named `nutburgers`.
3. Download and place the `nutburgers.mpq` folder into the `nutburgers` directory.
4. On your Battle.net client open up the settings menu and go to the options wheel and select `Game Settings`.
5. Under Diablo 2 Resurrected check the `Additional Command Line Arguments` box.
6. Copy and Paste `-mod nutburgers -txt` into the text box. (optionally add `-enablerespec` to allow respecing whenever by `alt + left click` on any allocated stat points will reset everything)
7. Start the game :)

### Change Log

Documented Changes made to D2R

Sockets:

    Added sockets to throwing weapons, gloves, boots, and belts
        - Belts, Gloves and Boots can get up to 2 sockets

Sorceress:

    In general added synergies between all skills in a tab (i.e fire, cold, lightning)

    Inferno:
        - Added a base number of 5 projectiles to increase its AoE capabilities
        - Added a mod on Hotspurs Leather Boots to give inferno 5 additional projectiles

    Thunder Storm:
        - Modified it to fork to nearby enemies based on Chain Lightning level
        - Modified it to hit faster based on faster cast rate (1 frame per 5% capped at 150% fcr)
    
    Shatter Strike:
        - New Skill similar to Amazons Charged Strike. Melee Cold Attack that creates Ice Bolts
        - Replaces Frozen Armor

    Masteries:
        - Gave them all a smaller diminishing bonus opposite of their normal effect (either pierce or damage)

Barbarian:

    Ricochet:
        - A new throwing skill that will bounce between enemies

    Seismic Slam:
        - An improved Leap Attack that now hits a larger radius, leaps much faster but has a 3 second cooldown baseline
        - The AoE portion deals the weapon damage plus the skill damage

Assassin:

    Updated the martial arts skills so that charges only expire with duration instead of expending them on attack with the exception of Dragon Talon because it would proc the charges on every kick.

    
New Items:

    Currency:

        Alteration Orb:
            - Alteration Orbs can be transmuted with a magic item to reroll its properties

        Chaos Orb:
            - Chaos Orbs can be transmuted with a rare item to reroll its properties

        Vaal Orb:
            - Vaal Orbs can be transmuted with any magic or higher rarity item to have a chance to receive a new random modifier
            - Possible Outcomes:
                - 36% chance to receive a new modifier
                - 32% chance to do nothing
                - 32% chance to transform into a rare item
            - Possible New Modifiers (all have equal weighting)
                - Rings:
                    - Faster Run/Walk: 10%
                    - Faster Cast Rate: 10%
                    - Life: +15-20
                    - Physical Damage Taken Reduced: 5-7%
                    - All Resistance: +5-10
                    - Magic Find: 10-15%
                - Amulets:
                    - All Skills: +1
                    - Mana Regen: 15-20%
                    - Energy: +10-15
                    - Increased Exp Gain: 1-2%
                    - All Resistance: +5-10
                    - Magic Find: 10-15%
                - Shields:
                    - Increasd Block Chance: 10%
                    - Fire Damage: 10-15%
                    - Lightning Damage: 10-15%
                    - Cold Damage: 10-15%
                    - Poison Damage: 10-15%
                    - Vitality: +20
                - Body Armor:
                    - Increased Health: 5-7%
                    - Faster Cast Rate: 10-15%
                    - Increased Attack Speed: 10-15%
                    - Random Level 5 Aura when equipped
                    - Gold per Level: 2%/lvl
                    - Physical Damage Taken Reduced: 7-8%
                - Weapons:
                    - Enhanced Damage: 40-60%
                    - +# Damage: +50
                    - Increased Attack Speed: 10-15%
                    - +# to Class Skill: +1
                    - Faster Cast Rate: 15-20%
                    - Crushing Blow: 10-15%
                - Boots:
                    - All Resistance: +8-10
                    - Faster Run/Walk: 10%
                    - Pierce enemy Fire Resistance: 5-10%
                    - Pierce enemy Lightning Resistance: 5-10%
                    - Pierce enemy Cold Resistance: 5-10%
                    - Pierce enemy Poison Resistance: 5-10%
                - Gloves:
                    - Chance to cast level 12 Shiver Armor when Struck: 10%
                    - Mana: +30-40
                    - Deadly Strike: 10-15%
                    - Increased Attack Speed: 10-15%
                    - Increased Health: 3-5%
                    - Dexterity: 10-20
                - Belt:
                    - Pierce: 10-15%
                    - Increased Mana: 8-10%
                    - Fire Absorb: 5%
                    - Lightning Absorb: 5%
                    - Cold Absorb: 5%
                    - Mana gained on Hit: +3-5
                - Helm:
                    - Life gained on Hit: +10-15
                    - Strength: 10-20
                    - Life Regen: +30-40
                    - Magic Find: 15-25%
                    - Gold Find: 35-60%
                    - Life: +25-40

        Jewellers Orb:
            - Jewellers orbs can be transmuted with any socketable item to add random number of sockets to it

    Runewords:

        Thunder:
            - Requires a 4 socketed Staff
            - Runes: Lem + Ort + Ohm + Ist
            - Stats (Do not include the stats from the runes):
                - +3-4 Lightning Skills (Sorceress Only)
                - +3-4 Thunder Storm (Sorceress Only)
                - 60% Faster Cast Rate
                - 20-35% Faster Hit Recovery
                - +10-20 to All Resistance
                - +15-20 to Dexterity

        Frostbite:
            - Requires a 4 socket weapon
            - Runes: Thul + Ist + Pul + Shael
            - Stats (Do not include the stats from the runes):
                - 15-25% Increased Attack Speed
                - -15-20% Enemy Cold Resistance
                - 15% to Cast Level 10 Frost Nova on Striking
                - +20-40 to Cold Resistance
                - +2 to Cold Skills

        Fractured Mind:
            - Requires a 2 socket helm
            - Runes: Fal + Io
            - Stats (Do not include the stats from the runes):
                - +2 Additional Projectiles for skills
                - 100-150% Enhanced Defense
                - +3-5 to Light Radius
                - +2 Mana gained on Hit

        Annihilation:
            - Requires a 4 socket body armor
            - Runes: Cham + Zod + Jah + Sur
            - Stats (Do not include the stats from the runes):
                - 10% chance to cast level 35 Bone Spirit on Striking
                - 20% chance to cast level 25 Chain Lightning on Striking
                - 15% chance to cast level 20 Frozen Orb on Striking
                - 15% chance to cast level 26 Fist of the Heavens on Striking
                - 25% chance to cast level 13 Twister on Striking
                - 10% chance to cast level 27 Meteor on Striking
                - -(25-50) to All Resistance

        Added sockets to throwing items, therefore added the possibility of runewords for them. Here is a list of runewords that specifically changed to allow use with any throwing weapon.

            - Mist
            - Plague
            - Strength
            - Zephyr
            - All other runewords follow the same rules i.e. any axe runeword can be used in a throwing axe, any melee weapon runeword can be used in a combo (melee/throwing) weapon.


    Uniques:

        - Frostburn Gauntlets
            - Added +1 to Cold Skills

        - Hotspur Boots
            - Added +5 to Inferno Projectiles

        - Leap Boots
            - Reduce Cooldown of Leap attack by 33%
            

New Item Modifiers:
    - Added melee splash affix to jewels
    - Added +# to Cold/Lightning Skills

Shortened names of a few items to reduce clutter

Reduced the chance for NoDrop in most scenarios

Removed Quantity for Bow/Javelin/Throwing Skills
