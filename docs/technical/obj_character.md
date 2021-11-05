---
title: obj_Character
---

Dieses Objekt implementiert Bewegung, Kollision und Animation für Charaktere im Spiel. Sowohl die Spielfigur, NPC's, als auch Gegner sind Subtypen dieses Objekts.

*sprite*
:   `sprite_index` des Sprite Sheets. Das Animationssystem ist in der Lage die jeweiligen Einzelanimationen des Sheets über ihre Position zu referenzieren.

*animationIndex*
:   Position des erster Frames der aktuellen Animation

*frame*
:   Position des Frames der im nächsten Draw Event gerendert wird