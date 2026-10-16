# Sea Duel — simple crew combat v0.8

Experimental browser playtest. Play in landscape.

Each ship starts with 20 fighters. A large number below the ship shows its surviving crew.
Damage = surviving fighters x their ranged or melee damage. Wounds persist; zero crew sinks the ship.
Every attack is one hit. There are no counterattacks, double hits, class exceptions or defence bonuses.

Draw a route to sail. Pull backwards from the active ship to fire. Return the pull to cancel.
BOARD is a manual button in contact. Point-blank shooting is allowed.
Choose one attack per turn: FIRE or BOARD. Movement is independent and can come before or after it.
End turn passes without a defence bonus. A miss uses the attack; cancellation does not.

| Ship | Fighter HP | Ranged | Melee | Movement |
|---|---:|---:|---:|---:|
| Galleon | 18 | 11 | 4 | 450 |
| Brig | 15 | 5 | 11 | 675 |
| Swift | 12 | 7 | 8 | 900 |

Pre-battle slots determine activation order. No flagships or AP. Ships do not push stationary ships.
Collision damage is disabled. Camera stays still. The previous 15.3-turn simulator result belongs to v0.7.
This simpler balance needs a fresh playtest; no counter-class triangle is claimed.

This public repository contains generated player files only.
