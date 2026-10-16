# Sea Duel — damage ranges and class ranges v0.9

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
| Galleon | 25 | 9–11 | 1–2 | 800 | 450 |
| Brig | 40 | 1–2 | 32–38 | 500 | 350 |
| Swift | 25 | 1–2 | 20–25 | 250 | 1100 |

Galleon keeps distance against Brig; Swift closes against Galleon; Brig wins contact against Swift.
AI duels on islands: Galleon > Brig60/60, Swift > Galleon60/60, Brig > Swift52/60.
These are heuristic simulations, not proof of optimal play.50 mirrored fleet matches averaged24.4 activations;
first side won46/50. The15-turn target and initiative balance remain unresolved. Published at the owner's request for playtesting.

Crew labels are slightly smaller and the floating pull-control hint is hidden.
Fixed slot order, stationary camera, no AP, flagships, collision damage or stationary ship pushing.

This public repository contains generated player files only.
