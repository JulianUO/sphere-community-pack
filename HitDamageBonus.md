# Usage #
```
[events e_attunement]
on=@hitdamagebonus
if <argo> == <findid(i_attunement).tag0.weap> && <src> == <findid(i_attunement).link>
var0.<uid>_damagebonus += 50
endif
```

DEFAULT: Hitter<br>
SRC: Hit<br>
ARGO: Weapon used to hit<br>
ARGN1: Damage<br>

var0.UIDofCharacter_damagebonus +=: Used to add additional damage, in percentage.