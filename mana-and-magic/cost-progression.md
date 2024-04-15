# Cost progression

!!! info "Machine Translated Content"

    This entry was machine translated from german to english with the deepl api.
    If you find any errors, please report them

The mana costs of all spells increase in the same way: The next spell costs 1.25 times the previous one _and the resulting number is always rounded up._ So the first Cursed Arrows costs 20 mana, the second `1.25 x 20 = 25 mana`, the third `1.25 x 25 = 31.25 ≈ 32 mana`, etc.&#x20;

In total, there are only ten unique initial mana costs and _the following table lists the development of the sum of the costs_. For example, five times Stone to Iron (initially 25 mana) costs a total of 210 mana.

=== "Spells 60 - 25"
    | Barbarian Conversion | Map Reveal | Strengthen Soldiers, Stone to Iron | Vanishing Resources, Banish Enemies, Forest Fire, Horus' Heat, Ch'ih-Yu's Shield, Cursed Arrows | The Midas Touch, Festering Fear, Archer to Bordermen, Siphon Swamp, The Samurai Sword, Freeze Enemy, Send Goods | Stone Curse | Celestial Gifts etc, Fish to Flesh, Fish Tide, Melting Snow, Gold to Stone, Forest Favor | Magnificent Growth | Grasslands in Hell and Fullness | The Magic Eye, Call Goods |
    | ---------------------- | --------------- | -------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------------------------- | ------------------- | --------------------------- | ------------------------------ |
    | 60 | 30 | 25 | 20 | 15 | 12 | 10 | 8 | 4 | 2 |
    | 135 | 68 | 57 | 45 | 34 | 27 | 23 | 18 | 9 | 5 |
    | 229 | 116 | 97 | 77 | 58 | 46 | 40 | 31 | 16 | 9 |
    | 347 | 176 | 147 | 117 | 88 | 70 | 62 | 48 | 25 | 14 |
    | 495 | 251 | 210 | 167 | 126 | 100 | 90 | 70 | 37 | 21 |
    | 680 | 345 | 289 | 230 | 174 | 138 | 125 | 98 | 52 | 30 |
    | 912 | 463 | 388 | 309 | 234 | 186 | 169 | 133 | 71 | 42 |

=== "Spells 20 - 10"
    | Vanishing Resources, Banish Enemies, Forest Fire, Horus' Heat, Ch'ih-Yu's Shield, Cursed Arrows | The Midas Touch, Festering Fear, Archer to Bordermen, Siphon Swamp, The Samurai Sword, Freeze Enemy, Send Goods | Stone Curse | Celestial Gifts etc, Fish to Flesh, Fish Flood, Melting Snow, Gold to Stone, Forest Favor | Barbarian Conversion | Reveal Map | Strengthen Soldiers, Stone to Iron | Magnificent Growth | Grassland in Envelope and Filling | The Magic Eye, Summon Goods |
    | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------------------------- | ---------------------- | --------------- | -------------------------------- | ------------------- | --------------------------- | ------------------------------ |
    | 20 | 15 | 12 | 10 | 60 | 30 | 25 | 8 | 4 | 2 |
    | 45 | 34 | 27 | 23 | 135 | 68 | 57 | 18 | 9 | 5 |
    | 77 | 58 | 46 | 40 | 229 | 116 | 97 | 31 | 16 | 9 |
    | 117 | 88 | 70 | 62 | 347 | 176 | 147 | 48 | 25 | 14 |
    | 167 | 126 | 100 | 90 | 495 | 251 | 210 | 70 | 37 | 21 |
    | 230 | 174 | 138 | 125 | 680 | 345 | 289 | 98 | 52 | 30 |
    | 309 | 234 | 186 | 169 | 912 | 463 | 388 | 133 | 71 | 42 |

=== "Spell 8 - 2"
    | Magnificent Growth | Grassland to Hell and Filling | The Magic Eye, Summon Goods | Barbarian Conversion | Map Reveal | Strengthen Soldiers, Stone to Iron | Vanishing Resources, Banish Enemies, Forest Fire, Horus' Heat, Ch'ih-Yu's Shield, Cursed Arrows | The Midas Touch, Festering Fear, Archer to Bordermen, Siphon Swamp, The Samurai Sword, Freeze Enemy, Send Goods | Stone Curse | Celestial Gifts etc, Fish to Flesh, Fish Flood, Melting Snow, Gold to Stone, Forest Favor |
    | ------------------- | --------------------------- | ------------------------------ | ---------------------- | --------------- | -------------------------------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------------------------------------------------------------------------------------------- |
    | 8 | 4 | 2 | 60 | 30 | 25 | 20 | 15 | 12 | 10 |
    | 18 | 9 | 5 | 135 | 68 | 57 | 45 | 34 | 27 | 23 |
    | 31 | 16 | 9 | 229 | 116 | 97 | 77 | 58 | 46 | 40 |
    | 48 | 25 | 14 | 347 | 176 | 147 | 117 | 88 | 70 | 62 |
    | 70 | 37 | 21 | 495 | 251 | 210 | 167 | 126 | 100 | 90 |
    | 98 | 52 | 30 | 680 | 345 | 289 | 230 | 174 | 138 | 125 |
    | 133 | 71 | 42 | 912 | 463 | 388 | 309 | 234 | 186 | 169 |

Note that rounding up in the manner described above leads to a rapid increase in cost for cheap spells such as "Eye" (initially two mana), but loses significance for expensive spells and becomes negligible for larger numbers.

This helps to approximate the long-term course of a hypothetical game under the assumption that the players only cast the same spell or group of spells.

It turns out that the number of spells or spell splits a player has in front of them at any given time converges approximately to **δ = log 1,25 × Δ** for each mana production ratio δ".

For example, let's look at a 1v1 Romans game and it turns out that you have five small temples while your opponent has four small temples, so **δ = log 1,25 × (5/4) = 1**, which means you are always one convert ahead.

But if you have four temples and your opponent has three temples, so that **δ = log 1,25 × (4/3) ≈ 1,3**, you are always one convert and sometimes two converts ahead.