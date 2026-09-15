# Instagram-Bilder

Zwischenablage für Kacheln, die auf Instagram veröffentlicht werden.

Instagram lädt Bilder nicht hoch, sondern **holt** sie von einer öffentlichen URL —
und zwar genau einmal, im Moment des Postens. Danach liegt das Bild auf Instagrams
Servern. Dieses Repo ist deshalb nur eine kurze Durchreiche, kein Archiv:
`posten.py` räumt die Bilder nach dem Veröffentlichen wieder weg.

Bewusst getrennt vom Website-Repo `online-Finanzspezialist`, damit ein
Instagram-Bild nie einen Deploy der Live-Website auslöst.

Befüllt wird das hier von `instagram/werkzeuge/hochladen.py` im Projekt
„Eigene Baufi-Seite". Von Hand ist hier nichts zu pflegen.
