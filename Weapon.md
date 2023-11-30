---  
tags:  
  - Rule  
---  
# Overview  
  
Weapons modify the effects of [Attacking](./Attack.md) when equipped.  
  
|Weapon Attribute|Data Type|Description|  
|---|---|---|  
|Weight|Number|The DC of attacks and saves regarding this weapon.|  
|Damage|Number|The amount of damage that will be applied on a hit.|  
|Damage Type|[Damage Type](./Damage%20Type.md)|The type of damage that will be applied on a hit.|  
|Attack Attribute|[Attribute](./Attribute.md)|The attribute used for skill checks when attacking with this weapon.|  
|Damage Scaling|[Attribute](./Attribute.md)|The attribute used for [Damage Scaling](./Damage%20Scaling.md) when attacking with this weapon.|  
|Brace Attribute|[Attribute](./Attribute.md)|The attribute used when blocking attacks made by this weapon.|  
|Avoid Attribute|[Attribute](./Attribute.md)|The attribute used when dodging attacks made by this weapon.|  
  
When a weapon is [Shredded](./Shred.md), the damage amount is reduced by the shred value.  
  
Weapons can be affected by [Intrinsic Enchantment](./Intrinsic%20Enchantment.md). Modify the attack roll and damage amount by the intrinsic enchantment value.  
  
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
| File                        | Category   | Rarity   | [Attack Attribute](Attack%20Attribute.md)        | [Damage Scaling](Damage%20Scaling.md)          | [Brace Attribute](Brace%20Attribute.md)         | [Avoid Attribute](Avoid%20Attribute.md)         |  
| --------------------------- | ---------- | -------- | --------------------------- | --------------------------- | --------------------------- | --------------------------- |  
| [Precision](./Precision.md) | \-         | \-       | \-                          | \-                          | \-                          | \-                          |  
| [Psychic](./Psychic.md)     | Biological | Rare     | [Talent](./Talent.md)       | [Awareness](./Awareness.md) | [Wisdom](./Wisdom.md)       | [Intellect](./Intellect.md) |  
| [Acid](./Acid.md)           | Elemental  | Uncommon | [Talent](./Talent.md)       | [Strength](./Strength.md)   | [Strength](./Strength.md)   | [Finesse](./Finesse.md)     |  
| [Cold](./Cold.md)           | Elemental  | Uncommon | [Intellect](./Intellect.md) | [Vitality](./Vitality.md)   | [Vitality](./Vitality.md)   | [Finesse](./Finesse.md)     |  
| [Fire](./Fire.md)           | Elemental  | Uncommon | \*\*                        | [Finesse](./Finesse.md)     | [Vitality](./Vitality.md)   | [Agility](./Agility.md)     |  
| [Lightning](./Lightning.md) | Elemental  | Uncommon | [Intellect](./Intellect.md) | [Awareness](./Awareness.md) | [Intellect](./Intellect.md) | [Awareness](./Awareness.md) |  
| [Poison](./Poison.md)       | Elemental  | Uncommon | [Intellect](./Intellect.md) | [Wisdom](./Wisdom.md)       | [Vitality](./Vitality.md)   | [Talent](./Talent.md)       |  
| [Sonic](./Sonic.md)         | Elemental  | Rare     | [Talent](./Talent.md)       | [Vitality](./Vitality.md)   | [Vitality](./Vitality.md)   | [Awareness](./Awareness.md) |  
| [Force](./Force.md)         | Magical    | Rare     | \*\*                        | [Charisma](./Charisma.md)   | [Charisma](./Charisma.md)   | [Talent](./Talent.md)       |  
| [Radiant](./Radiant.md)     | Magical    | Rare     | [Wisdom](./Wisdom.md)       | [Charisma](./Charisma.md)   | [Wisdom](./Wisdom.md)       | [Charisma](./Charisma.md)   |  
| [Void](./Void.md)           | Magical    | Rare     | [Wisdom](./Wisdom.md)       | [Intellect](./Intellect.md) | [Wisdom](./Wisdom.md)       | [Intellect](./Intellect.md) |  
| [Blunt](./Blunt.md)         | Mundane    | Common   | [Strength](./Strength.md)   | [Strength](./Strength.md)   | [Strength](./Strength.md)   | [Agility](./Agility.md)     |  
| [Pierce](./Pierce.md)       | Mundane    | Common   | [Finesse](./Finesse.md)     | [Strength](./Strength.md)   | [Vitality](./Vitality.md)   | [Finesse](./Finesse.md)     |  
| [Sharp](./Sharp.md)         | Mundane    | Common   | [Agility](./Agility.md)     | [Strength](./Strength.md)   | [Vitality](./Vitality.md)   | [Agility](./Agility.md)     |  
  
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
  
