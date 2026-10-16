# Sea Duel — crew combat v0.7

Experimental browser playtest. Play in landscape.

Each ship carries 20 fighters. Their surviving number determines its ranged and melee damage.
Wounds persist. Zero fighters sinks the ship. There is no separate hull HP pool.

Draw a route from the active ship to sail. Pull backwards away from an enemy in range and release to fire.
Return the pull to the ship to cancel. BOARD is a manual button in contact.
Point-blank shooting remains available.
Choose ONE action: fire OR board OR defend. Movement can be split before and after an attack.
End without attacking to DEFEND: 35% less damage until that ship next activates.

Galleon / Gunners: 12 HP per fighter; ranged 6 x2; melee 2; movement 450.
Brig / Marines: 15 HP per fighter; ranged 2; melee 6 x2; movement 675.
Swift / Raiders: 12 HP per fighter; ranged 6; melee 8; movement 900. Boarding provokes no reply.

A surviving target in contact replies once before its next activation:
50% of one melee hit, or 100% while defending. Replies never trigger replies.
The reply lands between double hits; the second hit uses the surviving attackers.

Pre-battle slots determine activation order. There are no flagships or AP.
Stationary ships are not pushed. Collision damage is disabled in this crew experiment.
The balance targets about 15 individual ship activations in the separate open-map model.
Actual play, aiming, obstacles and bot decisions can differ. First-player advantage remains under study.

This public repository contains generated player files only.

