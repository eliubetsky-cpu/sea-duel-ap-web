# Sea Duel — boarding retaliation playtest v0.12

Experimental browser playtest. Play in landscape.

Each ship starts with 20 fighters. The number below the hull shows surviving crew.
One integer damage roll per attack, from the fighter's inclusive interval, multiplied by living crew.
Wounds persist; zero crew sinks the ship. One initiating hit. Surviving defenders answer every boarding once with their remaining crew and melee damage.
The answer uses an independent integer roll, can sink the attacker, and causes no counter-chain.
A sunk defender cannot answer. Shooting, including point-blank shooting, causes no reply.
Replies do not spend the defender's own attack. No double attacks or defence bonuses.

Draw a route to sail. Pull backwards from the active ship to fire. Return the pull to cancel.
BOARD is manual in contact; point-blank shooting is allowed.
One attack per turn: FIRE or BOARD. Movement can come before or after the attack.
A miss uses the attack; cancellation does not. End turn skips the remaining action.

| Ship | Fighter HP | Ranged damage per fighter | Melee damage per fighter | Range | Movement |
|---|---:|---:|---:|---:|---:|
| Galleon | 24 | 9–13 | 10–16 | 750 | 400 |
| Brig | 28 | 6–10 | 16–24 | 400 | 700 |
| Swift | 22 | 10–14 | 12–18 | 450 | 1100 |

Candidate A (profile 4495) stats are unchanged. Boarding retaliation is the new experiment.
The bot includes immediate retaliation losses when choosing its attack.
Controls, camera, movement and the bot's existing withdrawal condition are unchanged.
Old v0.11 duration and matchup results do not describe this new ruleset.

Fixed slot order, no AP, flagships, collision damage or stationary ship pushing.
All three ships have 360-degree firing sectors. Crew size does not affect movement or range.

This public repository contains generated player files only.
