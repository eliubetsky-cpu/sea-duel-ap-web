# Sea Duel — Tactical Duel v0.4

Isolated 1v1 experiment. Two identical Brigs:100 HP,20 damage,320 movement,1100 range.
Five successful volleys sink a ship. No crew, boarding, retaliation, AP or damage scaling.
One shot per turn; movement can come before and after firing.
Rocks stop ships and cannonballs. The selected landing must hit the hull.

Draw your route with the fleet's original curved white ribbon. Pull back from your ship to aim automatically.
Natasha's original start-of-shot camera opens during the pull, with room below the ship for your finger.
Once the camera settles, the yellow arrow swings in a45-degree sector with a4.8-second cycle.
The dotted ballistic centre aim stays still while the timing arrow moves.
Pull strength changes range, including close shots. The bot uses the same landing calculation. The original fleet iron broadside flies along ShotArc; a volley damages once.
Aim opposite your finger in the displayed camera. Release to fire along the shown arrow; return to the ship to cancel.
Releasing before the camera settles cancels the shot.
There are no SAIL/AIM/FIRE buttons. END TURN, MENU and FULL SCREEN are available.
Movement starts on release and does not discard elapsed frame time.
The player has no additional random spread. The bot has seeded error up to5.5 degrees.
The bot seeks firing positions and cover after shooting.

Water material, seabed mesh/texture and reflection cubemap imported from main eb7cece561b72fdbb7d879230c0a679ca034e130 (Water Tweak2).

This experiment lives at /duel/. The fleet v0.12 root player is preserved.
Source branch:experiment/tactical-duel. Generated public player files only.
