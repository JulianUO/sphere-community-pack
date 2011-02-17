To activate the champions (in the exact places like on OSI) type:

  .GENERATECHAMPS

Notice that the Ilhenir Spawn and other new ML champions won't be
auto-created since some people might not want ML activated...

Make sure that the Star Chamber is empty (it's the place for the Harrower
altar).  After that, just enjoy =)

Notes & Instructions: The system will work with any ini setting, but I
suggest (just to make it more beautifull) to activate tooltips and the
new triggers (with the new triggers you'll activate the champion special
abilities).

You'll probably have to increase MaxComplexety in sphere.ini to allow more
npcs on a sector.  And also, remember to activate at least Felucca and
Ilshenar, or you might have some errors.

Check the defs in the script for customization.

You can acess a customization menu by double clicking the idol with .gm on,
and you can create blank champ altars by typing:

  .CREATEALTAR

v2.0
-Added transcendence scrolls
-After the time limit the champion won't fully restart, it'll restart the
current level or go back 1 if the players haven't killed enough in time.
-Power scrolls now use the new TAG.OVERRIDE tags
-Better engine, with new sphere syntaxes
-Lots of stuff added with time which I don't remember!

v2.1
-Using new LIST.xxx feature to give Power Scrolls (thus fixing a possible
crash with the old method)

Note that the artifacts won't give anything special unless you make a
separate system for them. Unfortunatly mine is so distributed throughout
other scripts and use so many custom, not default by sphere, calculations
and scripts that it's not easily releasable. Also, this system does not
have the Valor Virtue, since it's not available by default on Sphere,
so I removed that part of the code. It also doesn't have the Justice
Virtue for the same reasons, although you can make your own  script
using 3 triggers I added:
@ReceivePowerScroll
@ReceiveTranscendenceScroll
@ReceiveStatPowerScroll

v3.0
-Monsters spawning method remade to fully match OSI's. You can configure the amount of monsters spawned in the defs.
 *Note: You will have to reset all champion spawns for this to work. To do that just D-click the idol
	and inactivate the champion spawn, then reactivate it. =]
-Power Scrolls and Stat Scrolls now with OSI's accept skillcap increase gump.
-Added +15 Stat Scroll (why wasn't that there already o.O?)
-Altar colors change according to status (inactive, idle, champion summoned, active)
-Added sound and other effects when a white skull appears.
-Added basic champion & harrower title support for this distributable script
 *How players will see the titles are up to you. Check the end of the script file and the @Death trigger on the
 Champions for more details.
-Fixed white skulls not appearing correctly some times.

v3.1
-Added a check on the power scroll dialogs to check if they are in the bag.
-Added dialogs for Transcendence scrolls too.

v3.2
-Removed some functions that belonged to my server and might throw some errors.
-Added SPHERECHAMPIONS_STATSUMINCREASE_x defs to change STATSUM override more easily.
-Removed some items that belonged to my server and might throw errors (my bad)
-Tweaked spawning method a bit to make it more accurate.
-Changed Champion Skull id (more beautiful now =]).
-Added commented out defs with correct monsters ids (Note that a lot do not come with sphere by default, that's why
they are commented out).

v3.3
-Fixed double definitions of chance to get a champion artifact.
-Added light effects according to the level the champion spawn is currently at.
-Increased champion spawn multi area, so the light is properly changed and that also auto disables
house building inside the spawn area.
-Spawn region will have flags to prevent recalling out, gating and recalling in/marking. Note that recalling out will be possible after the champion
is killed and the spawns is idle.
-Added OSI's chance of actually spawning the Champion when 16 red candles are present. The champion will appear
or not after completing the 16th level. Each time it doesn't appear the required number of monsters to be killed
is lowered (10, 8, 6, 4, 2 [can't go further]). Default chance of appearence is 70%.
-Made champion skulls with correct names (Skull of Power, Greed, Enlightment, Death, Venom and Pain).
Note that only the original 6 champions and on MAP 0 (Felucca) will give such skulls.
-Remade Harrower summoning method to fully match OSI's. This will require some tweaking for those who already used
this script. To automatically fix your harrower spawn use .FIXHARROWER (this comes in a separate script and only
needs to be used IF you already used this script prior to this change). If that's your first time, just use
.GENERATECHAMPS as you would normally + no need for Champions_FixHarrower.scp script.
-Separated the script a bit into more then 1, to facilitate tweaks.

v3.4
-Champion Skulls will now stay on the altar to show which ones have been sacrificed, like on OSI.

v3.5
-Fixed 'Idol of the Champion' without ATTR_MOVE_NEVER upon creation.
-Re-added MAXSPAWNS setting on the customization menu. This will allow for spawns on low space areas
like Bedlam for example, or Twisted Weald.

v4.0 (Final)
-Remade Minion Spawning to use the new LIST feature, it's faster and more organized.

by ClouD_BR
