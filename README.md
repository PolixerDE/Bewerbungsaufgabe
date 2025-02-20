# Bewerbungsaufgabe
Aufgabe: Custom Land-Claim Plugin

Schreibe ein Minecraft-Bukkit/Spigot/Paper-Plugin, das es Spielern erlaubt, ein eigenes Grundstück (Land) zu claimen, um es vor anderen Spielern zu schützen.

Funktionen:
✅ Spieler können mit /claim ein 16x16-Chunks großes Gebiet beanspruchen.
✅ Spieler können mit /unclaim ihr Land wieder freigeben.
✅ Spieler können mit /trust <Spieler> einen anderen Spieler berechtigen, ihr Land zu betreten und zu bauen.
✅ Spieler können mit /untrust <Spieler> einem Spieler die Berechtigung wieder entziehen.
✅ Landbesitzer können mit /listclaims ihre beanspruchten Gebiete auflisten.
✅ Das Plugin soll verhindern, dass fremde Spieler auf einem geclaimten Gebiet Blöcke abbauen oder platzieren.

Technische Anforderungen:
Nutze Java oder alternativ Kotlin
Projekt mit Maven oder Gradle
Speichere die Daten (geclaimte Gebiete & Trust-Liste) in einer YAML-Datei oder SQLite-Datenbank
Nutze Events (BlockBreakEvent, BlockPlaceEvent) für den Schutzmechanismus
(Optional) ActionBar-Nachricht, wenn ein Spieler ein fremdes Gebiet betritt
Extra (Optional, für Bonuspunkte 😁)
⭐ Visualisierung des geclaimten Gebiets mit Partikeln, wenn ein Spieler /claim eingibt
⭐ Admin-Befehl /adminclaims, um alle geclaimten Gebiete zu sehen

Wenn du das erledigt hast sende uns einfach den Code via deinem Discord-Ticket zu! 😊







