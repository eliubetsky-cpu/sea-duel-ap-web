# Sea Duel — candidate A playtest v0.11

Experimental browser playtest. Play in landscape.

Each ship starts with 20 fighters. The number below the hull shows surviving crew.
One integer damage roll per attack, from the fighter's inclusive interval, multiplied by living crew.
Wounds persist; zero crew sinks the ship. One hit, no retaliation, double hits or defence bonuses.

Draw a route to sail. Pull backwards from the active ship to fire. Return the pull to cancel.
BOARD is manual in contact; point-blank shooting is allowed.
One attack per turn: FIRE or BOARD. Movement can come before or after the attack.
A miss uses the attack; cancellation does not. End turn skips the remaining action.

| Ship | Fighter HP | Ranged damage per fighter | Melee damage per fighter | Range | Movement |
|---|---:|---:|---:|---:|---:|
| Galleon | 24 | 9–13 | 10–16 | 750 | 400 |
| Brig | 28 | 6–10 | 16–24 | 400 | 700 |
| Swift | 22 | 10–14 | 12–18 | 450 | 1100 |

Candidate A (profile 4495) from a search of 6656 tuning profiles and 287640 main simulated games.
With the unchanged production bot, 99/100 fresh mirrored fleet matches ended naturally,
averaging 14.90 individual ship activations; one reached the 120-activation cap.
The first ship sank at mean activation 3.36; the starting side won 85/99 natural matches.
These heuristic results do not establish optimal play or a complete rock-paper-scissors balance.
Initiative and fleet composition remain unresolved. This build is for live testing.

Controls, camera, bot and combat rules are unchanged from v0.10.
Fixed slot order, no AP, flagships, collision damage or stationary ship pushing.
All three ships have 360-degree firing sectors. Crew size does not affect movement or range.

This public repository contains generated player files only.
