# Gesprächsnotiz – Ingenieurbüro Tassenbacher GmbH

Einzeldatei-Webapp für Telefonnotizen, Besprechungsprotokolle und Aktenvermerke.
Erfassen am iPhone/iPad/Mac, Ausgabe als A4-PDF im Büro-Layout.

## Einrichten auf GitHub Pages

1. Neues Repository anlegen, z. B. `gespraechsnotiz`.
2. `index.html` und `README.md` hochladen (Add file → Upload files → Commit).
3. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, Ordner: `/ (root)`.
4. Nach ca. 1 Minute erreichbar unter:
   `https://scherto.github.io/gespraechsnotiz/`
5. Am iPhone/iPad im Safari öffnen → Teilen → **Zum Home-Bildschirm**. Danach startet die
   App wie ein normales Programm im Vollbild.

Updates: einfach die `index.html` im Repo ersetzen.

## Bedienung

| Schaltfläche | Wirkung |
|---|---|
| Als PDF drucken | Druckdialog; am Mac „In PDF sichern“. Dateiname wird automatisch aus Datum, Art und Name vorgeschlagen. |
| Zu den Akten legen | Speichert die Notiz in der Ablage dieses Geräts (Liste unten, mit Suche). |
| Text kopieren | Reine Textfassung für E-Mail, Stackfield oder orgaMAX. |
| Neue Notiz | Leeres Formular mit aktuellem Datum und Uhrzeit. |
| Sichern (JSON) | Alle abgelegten Notizen als Datei – für Backup oder Gerätewechsel. |
| Einlesen | Sicherungsdatei wieder einspielen; vorhandene Notizen bleiben erhalten. |

Kurzbefehle am Mac: `⌘S` legt ab, `⌘P` druckt.

Diktieren funktioniert in Chrome und Safari über die Schaltfläche neben dem Textfeld;
am iPad alternativ das Mikrofon der Bildschirmtastatur.

## Speicherort der Daten

Alle Notizen liegen ausschließlich lokal im Browser des jeweiligen Geräts
(localStorage). Nichts wird übertragen. Ein Gerätewechsel oder das Löschen der
Safari-Daten entfernt die Ablage – deshalb regelmäßig „Sichern (JSON)“ verwenden.

## Layout

Arial, Orange `#E8632A`, Dunkelblau `#1A2B3C`, Titelbalken weiß auf dunkelblau,
Logo rechts oben, Fußzeile mit oranger Linie und den drei grauen Firmenzeilen (7 pt).
Das Logo wird direkt aus dem Repo `Fotodokumentation_Tassenbacher` geladen.
