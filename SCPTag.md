# Item Tags #
In the item section, we will separate the tags by type. Most of the tags (if not all) are applied and work if you define the tevents in the item. If you forgot to do this, the tag will have no effect at all over the item. Unless there's no typedef specified on the header.<br>

<h3>Magical Properties (TYPE: t_iprop)</h3>
<table><thead><th> <b>Name</b> </th><th> <b>Description</b> </th></thead><tbody>
<tr><td> TAG.BestWeaponSkill </td><td> Substitutes the character's trained weapon skill for that normally required for the weapon type </td></tr>
<tr><td> TAG.DamageIncrease </td><td> Increases the base damage you inflict with your weapon </td></tr>
<tr><td> TAG.DefenseChanceIncrease </td><td> Increases your chance to dodge blows </td></tr>
<tr><td> TAG.DexterityBonus </td><td> Increases your Dexterity Stat by the number of points on the item </td></tr>
<tr><td> TAG.EnhancePotion </td><td>                    </td></tr>
<tr><td> TAG.FasterCastRecovery </td><td> Shortens waiting time between casting spells by 0.25 second per point </td></tr>
<tr><td> TAG.FasterCasting </td><td> Decreases the time required to cast Magery and Chivalry spells by 0.25 seconds per point </td></tr>
<tr><td> TAG.HitChanceIncrease </td><td> Increases your chance to hit your opponents. </td></tr>
<tr><td> TAG.HitColdArea </td><td>                    </td></tr>
<tr><td> TAG.HitDispel </td><td> Has a percentage chance on each hit to cast the magery spell dispel on any summoned creature </td></tr>
<tr><td> TAG.HitEnergyArea </td><td>                    </td></tr>
<tr><td> TAG.HitFireArea </td><td>                    </td></tr>
<tr><td> TAG.HitFireball </td><td>                    </td></tr>
<tr><td> TAG.HitHarm </td><td>                    </td></tr>
<tr><td> TAG.HitLifeLeech </td><td> On every successful hit, converts a percentage of the damage inflicted by the attack into hit points for the wielder </td></tr>
<tr><td> TAG.HitLightning </td><td>                    </td></tr>
<tr><td> TAG.HitLowerAttack </td><td> Has a percentage chance on each hit to lower the hit chance of the target (HCI -25). Duration: 8 seconds, not cumulative </td></tr>
<tr><td> TAG.HitLowerDefense </td><td> Has a percentage chance on each hit to lower the defensive capabilities of the target(DCI -25). Duration: 8 seconds, not cumulative </td></tr>
<tr><td> TAG.HitMagicArrow </td><td>                    </td></tr>
<tr><td> TAG.HitManaLeech </td><td> On every successful hit, converts a percentage of the damage inflicted by the attack into mana points for the wielder </td></tr>
<tr><td> TAG.HitPhysicalArea </td><td>                    </td></tr>
<tr><td> TAG.HitPoisonArea </td><td>                    </td></tr>
<tr><td> TAG.HitStaminaLeech </td><td> Has a percentage chance on each hit to convert 100% of the damage inflicted on the target into stamina for the wielder </td></tr>
<tr><td> TAG.HitPointIncrease </td><td> Increases your maximum hit points by the number of points on the item </td></tr>
<tr><td> TAG.IntelligenceBonus </td><td> Increases your Intelligence Stat by the number of points on the item </td></tr>
<tr><td> TAG.LowerManaCost </td><td> Lowers the amount of mana needed to cast a spell or use a special move </td></tr>
<tr><td> TAG.LowerReagentCost </td><td> Lowers the amount of reagents needed to cast spells, both magery and necromancy. 100% negates the need to carry reagents at all. Tithing points, though unused, are required to be available to cast Chivalry spells </td></tr>
<tr><td> TAG.Luck    </td><td> Potentially increases monster loot in 3 ways: number of items, number of properties, intensty of properties </td></tr>
<tr><td> TAG.MageArmor </td><td> Negates impediments to both active and passive meditation from armor types that would normally block it </td></tr>
<tr><td> TAG.MageWeapon </td><td> Allows magery skill to substute for the normal combat skill of the weapon. Special moves cannot be used via this substitution </td></tr>
<tr><td> TAG.ManaIncrease </td><td> Increases your maximum mana by the number of points on the item </td></tr>
<tr><td> TAG.ManaRegeneration </td><td> Increases the rate at which you regain mana. (0.1 point per second per point of MR) </td></tr>
<tr><td> TAG.NightSight </td><td> Negates dark nights </td></tr>
<tr><td> TAG.ReflectPhysicalDamage </td><td> Reflect Physical Damage will reflect a percentage of any physical damage that is inflicted on you back onto the one who inflicted it </td></tr>
<tr><td> TAG.StaminaRegeneration </td><td> Increases the rate at which you regain stamina. (0.1 point per second per point of SR.) </td></tr>
<tr><td> TAG.HitPointRegeneracion </td><td> Increases the rate at which you regain hit points. (0.1 hit point per second per hpr point) </td></tr>
<tr><td> TAG.SelfRepair </td><td> Has a chance of regaining durability each time it takes damage in the amount of the self repair </td></tr>
<tr><td> TAG.SkillBonus </td><td>                    </td></tr>
<tr><td> <a href='Slayer.md'>TAG.Slayer</a> </td><td> Weapons will do double damage against all creatures within a certain group </td></tr>
<tr><td> TAG.SpellChanneling </td><td> Allows the casting of magery spells while a weapon or shield is equipped </td></tr>
<tr><td> TAG.SpellDamageIncrease </td><td> Increases the amount of damage spells inflict </td></tr>
<tr><td> TAG.StaminaIncrease </td><td> Increases your maximum stamina by the number of points on the item </td></tr>
<tr><td> TAG.StrengthBonus </td><td> Increases your Strength Stat by the number of points on the item </td></tr>
<tr><td> TAG.SwingSpeedIncrease </td><td> Increases the base speed at which you swing your weapon </td></tr>
<tr><td> TAG.CraftingBonus </td><td>                    </td></tr>
<tr><td> TAG.CraftingExceptionalBonus </td><td>                    </td></tr>
<tr><td> TAG.UsesRemaining </td><td>                    </td></tr></tbody></table>

<h3>Traps (TYPE: t_trapped)</h3>
<table><thead><th> <b>Name</b> </th><th> <b>Description</b> </th></thead><tbody>
<tr><td> TAG.Trap.Type </td><td> Spell used on the traps. Trap spells start at 1001 </td></tr>
<tr><td> TAG.Trap.Level </td><td> Intensity of the spell, from 0 to 1000 </td></tr></tbody></table>

<h3>Damage and Resistances</h3>
<table><thead><th> <b>Name</b> </th><th> <b>Description</b> </th></thead><tbody>
<tr><td> TAG.ResPhysical </td><td> Amount of Physical Resistance. If uses UO:R damage, it replaces ARMOR property </td></tr>
<tr><td> TAG.ResFire </td><td> Amount of Fire Resistance </td></tr>
<tr><td> TAG.ResCold </td><td> Amount of Cold Resistance </td></tr>
<tr><td> TAG.ResPoison </td><td> Amount of Poison Resistance </td></tr>
<tr><td> TAG.ResEnergy </td><td> Amount of Energy Resistance </td></tr>
<tr><td> TAG.DamPhysical </td><td> Amount of Physical Damage in %. This doesn't replace DAMAGE property! </td></tr>
<tr><td> TAG.DamFire </td><td> Amount of Fire Damage in % </td></tr>
<tr><td> TAG.DamCold </td><td> Amount of Cold Damage in % </td></tr>
<tr><td> TAG.DamPoison </td><td> Amount of Poison Damage in % </td></tr>
<tr><td> TAG.DamEnergy </td><td> Amount of Energy Damage in % </td></tr></tbody></table>


<h1>NPC Tags</h1>
<table><thead><th> <b>Name</b> </th><th> <b>Description</b> </th></thead><tbody>
<tr><td> TAG.Control.Slots </td><td> Followers slots required to control this creature. Default is 1 unless this is set to something different. Setting negatives values will lead to undesired behavior </td></tr>