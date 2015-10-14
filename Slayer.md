# TAG.Slayer #
Slayer groups, used as defnames, bitmask. Pretty much easy to use, works as FLAGS. You will find some examples below of how to apply them to both weapons and npcs.<br>
<hr />

<h2>Weapons</h2>
Weapons can hold two different tags: TAG.Slayer.Super and TAG.Slayer.Less<br>
TAG.Slayer.Super is the Super Slayer tag, which when doing damage to the specified group in the tag does x2 damage.<br>
TAG.Slayer.Less is the Lesser Slayer tag, which when doing damage to the specified group in the tag does x3 damage.<br>
<br>
Example of use:<br>
<pre><code>TAG.Slayer.Super = SSLAYER_ELEMENTAL<br>
TAG.Slayer.Less = SLAYER_OGRE<br>
</code></pre>
<hr />

<h2>NPCs</h2>
NPCs just hold one tag: TAG.Slayer<br>
It holds the lesser type it comes from, trying to be more precise, a Fire Elemental will only hold SLAYER_FIREELEM his tag, but it will be affected by weapons which hold SLAYER_FIREELEM and SSLAYER_ELEMENTAL.<br>
<pre><code>TAG.Slayer = SLAYER_FIREELEM<br>
</code></pre>
<hr />

<h2>Slayer Groups</h2>
Complete list of Slayer groups:<br>
<br>
<h3>Lesser Slayers</h3>
<table><thead><th> <b>Flag</b> </th><th> <b>Description</b> </th></thead><tbody>
<tr><td> SLAYER_ORC  </td><td> Orc Slayer         </td></tr>
<tr><td> SLAYER_OGRE </td><td> Ogre Slayer        </td></tr>
<tr><td> SLAYER_TROLL </td><td> Troll Slayer       </td></tr>
<tr><td> SLAYER_UNDEAD </td><td> Undead Slayer      </td></tr>
<tr><td> SLAYER_AIRELEM </td><td> Air Elemental Slayer </td></tr>
<tr><td> SLAYER_BLOODELEM </td><td> Blood Elemental Slayer </td></tr>
<tr><td> SLAYER_EARTHELEM </td><td> Earth Elemental Slayer </td></tr>
<tr><td> SLAYER_POISONELEM </td><td> Poison Elemental Slayer </td></tr>
<tr><td> SLAYER_SNOWELEM </td><td> Snow Elemental Slayer </td></tr>
<tr><td> SLAYER_WATERELEM </td><td> Water Elemental Slayer </td></tr>
<tr><td> SLAYER_FIREELEM </td><td> Fire Elemental     </td></tr>
<tr><td> SLAYER_GARGOYLE </td><td> Gargoyle Slayer    </td></tr>
<tr><td> SLAYER_SCORPION </td><td> Scorpion Slayer    </td></tr>
<tr><td> SLAYER_SPIDER </td><td> Spider Slayer      </td></tr>
<tr><td> SLAYER_TERATHAN </td><td> Terathan Slayer    </td></tr>
<tr><td> SLAYER_FEY  </td><td> Fey Slayer         </td></tr>
<tr><td> SLAYER_DRAGON </td><td> Dragon Slayer      </td></tr>
<tr><td> SLAYER_LIZARDMAN </td><td> Lizardman Slayer   </td></tr>
<tr><td> SLAYER_OPHIDIAN </td><td> Ophidian Slayer    </td></tr>
<tr><td> SLAYER_SNAKE </td><td> Snake Slayer       </td></tr></tbody></table>

<h3>Super Slayers</h3>
<table><thead><th> <b>Flag</b> </th><th> <b>Description</b> </th></thead><tbody>
<tr><td> SSLAYER_REPOND </td><td> Repond = Orc + Ogre + Troll + Repond </td></tr>
<tr><td> SSLAYER_UNDEAD </td><td> Undead = Undead    </td></tr>
<tr><td> SSLAYER_ELEMENTAL </td><td> Elemental = Fire + Air + Blood + Earth + Poison + Snow + Water + Elemental </td></tr>
<tr><td> SSLAYER_DEMON </td><td> Demon = Demon + Gargoyle </td></tr>
<tr><td> SSLAYER_ARACHNID </td><td> Arachnid = Scorpion + Spider + Terathan </td></tr>
<tr><td> SSLAYER_FEY </td><td> Fey = Fey          </td></tr>
<tr><td> SSLAYER_REPTILE </td><td> Reptile = Dragon + Lizardman + Ophidian + Snake + Reptile </td></tr></tbody></table>

