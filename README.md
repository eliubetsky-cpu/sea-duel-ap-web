# Sea Duel — lower-damage playtest v0.10

Experimental browser playtest. Play in landscape.

Each ship starts with 20 fighters. A number below the hull shows surviving crew.
One integer damage roll per attack, from the fighter's inclusive interval, multiplied by living crew.
Wounds persist; zero crew sinks the ship. One hit, no retaliation, double hits or defence bonuses.

Draw a route to sail. Pull backwards from the active ship to fire. Return the pull to cancel.
BOARD is manual in contact; point-blank shooting is allowed.
One attack per turn: FIRE or BOARD. Movement can come before or after the attack.
A miss uses the attack; cancellation does not. End turn skips the remaining action.

| Ship | Fighter HP | Ranged damage | Melee damage | Range | Movement |
|---|---:|---:|---:|---:|---:|
| Galleon | 25 | 8–9 | 1–2 | 800 | 450 |
| Brig | 40 | 1–2 | 18–22 | 500 | 350 |
| Swift | 25 | 1–2 | 14–17 | 250 | 1100 |

Galleon keeps distance against Brig; Swift closes against Galleon; Brig wins contact against Swift.
AI duels on islands: Galleon > Brig 30/30, Swift > Galleon 30/30, Brig > Swift 30/30.
These are heuristic simulations, not proof of optimal play. In 100 fresh-seed mirrored fleet matches,
98 finished by sinking a fleet (mean 32.53 activations); 2 reached the 120-turn limit.
The first ship sank at mean turn 6.67. The 15-turn target and initiative balance remain unresolved.
Published at the owner's request to test longer exchanges. Retaliation is not included in this build.

Crew labels are slightly smaller and the floating pull-control hint is hidden.
Fixed slot order, stationary camera, no AP, flagships, collision damage or stationary ship pushing.

This public repository contains generated player files only.
