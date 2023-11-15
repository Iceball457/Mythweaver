# Overview

Weapons modify the effects of [[./Attack|Attacking]] when equipped.

|Weapon Attribute|Data Type|Description|
|---|---|---|
|Weight|Number|The DC of attacks and saves regarding this weapon.|
|Damage|Number|The amount of damage that will be applied on a hit.|
|Damage Type|[[./Damage Type|Damage Type]]|The type of damage that will be applied on a hit.|
|Attack Attribute|[[./Attribute|Attribute]]|The attribute used for skill checks when attacking with this weapon.|
|Damage Scaling|[[./Attribute|Attribute]]|The attribute used for [[./Damage Scaling|Damage Scaling]] when attacking with this weapon.|
|Brace Attribute|[[./Attribute|Attribute]]|The attribute used when blocking attacks made by this weapon.|
|Avoid Attribute|[[./Attribute|Attribute]]|The attribute used when dodging attacks made by this weapon.|

When a weapon is [[./Shred|Shredded]], the damage amount is reduced by the shred value.

Weapons can be affected by [[./Intrinsic Enchantment|Intrinsic Enchantment]]. Modify the attack roll and damage amount by the intrinsic enchantment value.

# Creation

When designing a weapon, choose a weight class, a damage type, then up to two abilities.

# Weight Class

Lighter weapons hit more frequently. Heavy weapons are difficult to use, but deal more damage and critically hit more often. 24 weight and 4 damage is the most efficient weapon if you aren't going to choose any abilities and aren't worried about armor.

|Weight|Damage Flat|Damage Dice|
|:-:|:-:|:-:|
|18|2|d4|
|21|3|d6|
|24|4|d8|
|27|5|d10|
|30|6|d12|

# Damage Type
| File                        | Category   | Rarity   | [[Attack Attribute|Attack Attribute]]        | [[Damage Scaling|Damage Scaling]]          | [[Brace Attribute|Brace Attribute]]         | [[Avoid Attribute|Avoid Attribute]]         |
| --------------------------- | ---------- | -------- | --------------------------- | --------------------------- | --------------------------- | --------------------------- |
| [[./Precision\|Precision]] | \-         | \-       | \-                          | \-                          | \-                          | \-                          |
| [[./Psychic\|Psychic]]     | Biological | Rare     | [[./Wisdom\|Wisdom]]       | [[./Awareness\|Awareness]] | [[./Wisdom\|Wisdom]]       | [[./Intellect\|Intellect]] |
| [[./Acid\|Acid]]           | Elemental  | Uncommon | [[./Talent\|Talent]]       | [[./Strength\|Strength]]   | [[./Strength\|Strength]]   | [[./Finesse\|Finesse]]     |
| [[./Cold\|Cold]]           | Elemental  | Uncommon | [[./Intellect\|Intellect]] | [[./Vitality\|Vitality]]   | [[./Vitality\|Vitality]]   | [[./Finesse\|Finesse]]     |
| [[./Fire\|Fire]]           | Elemental  | Uncommon | \*\*                        | [[./Vitality\|Vitality]]   | [[./Vitality\|Vitality]]   | [[./Agility\|Agility]]     |
| [[./Lightning\|Lightning]] | Elemental  | Uncommon | [[./Intellect\|Intellect]] | [[./Intellect\|Intellect]] | [[./Intellect\|Intellect]] | [[./Awareness\|Awareness]] |
| [[./Poison\|Poison]]       | Elemental  | Uncommon | [[./Intellect\|Intellect]] | [[./Vitality\|Vitality]]   | [[./Vitality\|Vitality]]   | [[./Talent\|Talent]]       |
| [[./Sonic\|Sonic]]         | Elemental  | Rare     | [[./Talent\|Talent]]       | [[./Vitality\|Vitality]]   | [[./Vitality\|Vitality]]   | [[./Awareness\|Awareness]] |
| [[./Force\|Force]]         | Magical    | Rare     | [[./Talent\|Talent]]       | [[./Charisma\|Charisma]]   | [[./Charisma\|Charisma]]   | [[./Talent\|Talent]]       |
| [[./Radiant\|Radiant]]     | Magical    | Rare     | [[./Wisdom\|Wisdom]]       | [[./Charisma\|Charisma]]   | [[./Wisdom\|Wisdom]]       | [[./Charisma\|Charisma]]   |
| [[./Void\|Void]]           | Magical    | Rare     | [[./Wisdom\|Wisdom]]       | [[./Intellect\|Intellect]] | [[./Wisdom\|Wisdom]]       | [[./Intellect\|Intellect]] |
| [[./Blunt\|Blunt]]         | Mundane    | Common   | [[./Strength\|Strength]]   | [[./Strength\|Strength]]   | [[./Strength\|Strength]]   | [[./Agility\|Agility]]     |
| [[./Pierce\|Pierce]]       | Mundane    | Common   | [[./Finesse\|Finesse]]     | [[./Strength\|Strength]]   | [[./Vitality\|Vitality]]   | [[./Agility\|Agility]]     |
| [[./Sharp\|Sharp]]         | Mundane    | Common   | [[./Agility\|Agility]]     | [[./Strength\|Strength]]   | [[./Vitality\|Vitality]]   | [[./Agility\|Agility]]     |

*\*If a weapon is enchanted, the attack attribute is the same as the mundane type that weapon would deal if it were not enchanted. The listed attribute is for spellcasting.
\*\*Fire is in multiple traditions of magic and the attack attribute depends on which tradition.*
# Abilities

|Name|Effect|Stat Modifier|
|---|---|---|
|Lunge|Move 5' just before the attack.|+1 weight.|
|Reach|Can attack in melee from an additional 5' away.|+2 weight.|
|Wrap|Ignore shields.|+1 weight.|
|Rending|Shreds 1 armor on hit.|+1 weight.|
|Two Handed|Requires both hands to attack.|+2 damage.|
|Casting|You can cast spells as if the hands carrying this weapon were empty.|-1 damage.|
|Ranged|Requires ammo. Can target anything within your targeting range and line of sight. Can target anything up to twice as far with -2 to hit.|-1 damage.|
|Sweeping|Attack up to two targets in range.|-1 damage.|

