**_AC-less_**: Creatures do not have an Armor Class anymore. A combination of Hit DC and Damage Reduction takes its place.
### Hit DC
**_Missing attacks_**: An attack automatically misses its target if the attack roll isn’t at least as high as the Hit DC.

**_Base Hit DC_**: The base Hit DC of a target depends on its size, as shown in the table below. To determine the size of something that has no given size, you can use the Hit Area and height or length measures as guidelines.

| Size       | Hit DC | Hit Area | Height or Length |
| ---------- | ------ | -------- | ---------------- |
| Minuscule  | 20     | <25cm²   | <8cm             |
| Fine       | 18     | <100cm²  | <15cm            |
| Diminutive | 16     | <400cm²  | <30cm            |
| Tiny       | 14     | <0.15m²  | <60cm            |
| Small      | 12     | <0.6m²   | <120cm           |
| Medium     | 10     | <2.5m²   | <240cm           |
| Large      | 8      | <10m²    | <5m              |
| Huge       | 6      | <40m²    | <10m             |
| Gargantuan | 4      | >40m²    | >10m             |

The Hit Area refers to the area of a target that is facing the attacker. For example, a piece of paper is easier to hit from the front than from the side, because the papers thinness leads to a smaller Hit Area when looking at it sideways.

For the purposes of very small targets, a new set of sizes has been introduced. These will, for example, be used for [[Aimed Strikes]].

**_Even smaller sizes_**: If a target is significantly smaller than the sizes listed above, you can either find an extended table in the [[Extended Size Table|tables chapter]], or extrapolate the Hit DC from the measures in the table. Start with the measures and Hit DC for minuscule targets. Then add 2 to the Hit DC, quarter the Hit Area and halve the height or length. Repeat this until the measures fit the target you have in mind to get the appropriate Hit DC.
### Cover
**_Cover_**: Instead of increasing the Armor Class of the target that is behind cover, the Hit DC for attacks against the target increases in correlation with the now reduced Hit Area. Thus, Half Cover and Three-Quarters Cover can now be disregarded for attack rolls.

For example, if the Hit Area of an otherwise Medium size target matches the Tiny size due to Cover, the targets Hit DC is that of a Tiny target for attacks that are affected by that Cover.

**_Cover size_**: Sometimes, the creatures or objects that are used for Cover have an associated size category. If the Cover is of a larger size category than the target, it gives Total Cover. If it has the same category, it only leaves a few openings at best, which usually manifests as an increase in Hit DC of +4. If it is one category smaller, it leaves a decent area open to attack, giving no more than a +2 to the Hit DC. Even smaller Cover is too small to effectively reduce the Hit Area. It can, however, still be used to give Cover to specific body parts and other smaller targets.

**_Cover Cone_**: In some cases, it is not clear against which attacks a target benefits from Cover. The Dungeon Masters Guide describes a method to determine Cover through occupied and blocked spaces on a battle map, but some cover is not represented by this because it is too small and thus too finicky to place and manage on a battle map. For example, this is usually the case with [[Shields]].

In such cases where the cover is sufficiently small and close to the target, attacks originating from within a type of Cone, the Cover Cone, are affected by that cover. The Cover Cone originates from the target and is directed towards the cover, has no range limit and can't be interrupted.

To continue the Shield example, if you are holding a Shield directly towards an enemy, that enemy is within the Cover Cone originating from you and directed through the Shield, as they are directly on the opposite side of the Shield. Therefor, you benefit from the Cover your Shield provides you with, increasing your Hit DC against attacks by that enemy, usually by 2 or 4.

**_Crouching behind cover_**: Creatures may crouch, perch, sit down, or fall prone behind cover at will to increase the degree of cover they can obtain. When doing so, the following effects apply to the crouched creature:
- They decrease their effective size by one category for the purposes of determining the degree of cover they gain through the cover they crouch behind.
- They have the Prone condition.

For example, a Medium Humanoid receives three quarters cover from a Tower Shield when crouching behind it instead of the usual half cover, while a Small Humanoid can receive full cover from a Tower Shield when crouching behind it.
### Damage Reduction
**_Damage Reduction_**: Targets now have a Damage Reduction value. When the target takes damage through an attack, that value is subtracted from this damage.

**_Resistances & Vulnerabilities_**: Damage Reduction happens before resistances and vulnerabilities modify the damage.

**_Multiple Damage Types_**: When one attack deals damage of multiple different damage types, the Damage Reduction still only applies once to the attack, not to every type of damage it deals.

Damage of different types is reduced in order, with leftover reduction being carried to the next type. Bludgeoning, Piercing and Slashing damage are reduced first, Force damage and Psychic damage are reduced last, and all other damage types are reduced in-between. Within each category, the order of reduction is chosen by the target for each attack, so you may choose to reduce Bludgeoning damage before Slashing damage and vice versa whenever relevant.

For example, if an attack deals 2 Piercing damage, 2 Cold damage and 2 Force damage against a Damage Reduction of 3, the Piercing damage is reduced to 0, the Cold damage to 1 and the Force damage stays at 2, reducing the total damage dealt by 3. If it dealt Fire damage instead of Force damage, the target could have chosen to reduce the Fire damage by 1 instead of the Cold damage.

**_Damage Reduction for Specific Damage Types_**: Some features may give Damage Reduction against a specific damage type only. This Damage Reduction only reduces the Damage of its specified type, and its reduction takes place before general Damage Reduction is applied as described above.

**_Converting Armor Class to Damage Reduction_**: Every bonus to Armor Class that is not the Dexterity bonus can be converted 1:1 into a bonus for Damage Reduction, unless otherwise noted. An armour that sets the Armor Class of the wearer to 13 + Dexterity modifier will, for example, be converted to 3 Damage Reduction, because it is an Armor Class bonus of +3 compared to the base Armor Class of 10, while the Dexterity modifier is discarded. The conversion for armours can also be seen in [[Armour|their chapter]].

**_Stacking Damage Reduction_**: Damage Reduction from multiple sources stacks. However, the prerequisites for each source must still be met. For example, the Damage Reduction now gained from the Barbarians Unarmoured Defence and a heavy armour will not stack, because the heavy armour still disables the Barbarians Unarmoured Defence.
### Other changes
**_Reactive Defence_**: There are now options to reactively defend against incoming attacks and other effects. These include [[Dodging]], [[Blocking]] and [[Parrying]], as detailed within the Rules Glossary. For spellcasters, some of the [[Spells#New Spells|new]] and [[Spells#Reworked Spells - Defence|reworked spells]] provide options for reactive defence.

**_Defence and Dodge Action_**: The [[Actions#]]

**_Misses?_** Any rule or feature that requires a missed attack to work also works if the attack does not deal damage because of Damage Reduction, Blocking, or Parrying. Those attacks count as both a hit and a miss in that regard. Note that Dodging explicitly causes dodged attacks to miss.