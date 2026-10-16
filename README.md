# Sea Duel — playtest

Browser build of the experimental naval tactics prototype.

Play in landscape. Draw from the active ship to sail. Start pulling backwards, away from an enemy in range, to aim; release to fire. Return to your ship to cancel. A close approach automatically boards if at least 30% turn budget remains after sailing. Withdrawing does not trigger boarding. There is no joystick or boarding button.

Each activation starts with one shared 100% turn bar. Sailing spends distance; FIRE and automatic boarding each spend 30%, at most once each. Cyan bars show the remaining budget. Ships stop on hull contact without pushing stationary ships. Enemy collisions damage both hulls (Swift 9.6 / Brig 14.4 / Galleon 21.6 outgoing damage); friendly contacts deal no damage. Slots determine activation order. Sink the enemy fleet; there are no flagships. Combat keeps the overview camera.

Generated from the private Sea Duel source project. This repository contains the published player only.
