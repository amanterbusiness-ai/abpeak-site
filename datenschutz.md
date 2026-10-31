---
layout: default
title: Datenschutz
lang: de
---
# Datenschutzerklärung

Entwurf – wird vor dem Launch durch die geprüfte Fassung ersetzt.

## Verantwortlicher

- Name: Giuseppe Tringale
- Anschrift: Sperberweg 2c, 31224 Peine
- E-Mail: support@abpeak.app

## Was auf deinem Gerät bleibt

Dein Profil, deine Scans mit Fotos und Ergebnissen und deine Workouts speichert die App auf deinem Gerät, geschützt durch die Datei-Verschlüsselung von iOS (File Protection). Sie sind Teil deines Geräte-Backups, zum Beispiel in deiner eigenen iCloud. Dazu gehören deine Trainingsangaben (Ziel, Erfahrung, Geräte, Zeitwahl) und die Ergebnisse deiner Tests (Plank-Zeit, Dead-Bug-Antwort); sie werden nur auf deinem Gerät gespeichert (und sind Teil deines Backups) und nicht an unsere Server übertragen. Wenn du Apple Health verbindest, liest die App dort dein Gewicht und speichert deine Workouts; das ist freiwillig.

## Kamera-Coach (optional)

Der Kamera-Coach ist standardmäßig aus und startet nur, wenn du ihn selbst einschaltest und der Kamera-Zugriff erlaubt ist. Apple Vision erkennt dabei live auf deinem Gerät Körperpunkte, um Wiederholungen zu zählen und Hinweise zur Haltung zu geben. Die Kamerabilder liegen nur im Arbeitsspeicher, um das Raster zu berechnen. Nichts davon wird gespeichert oder hochgeladen, auch nicht an unsere Server.

## Scan-Analyse

Für die Auswertung schneidet die App dein Gesicht auf dem Gerät ab und sendet nur den Ausschnitt deines Oberkörpers an eine Supabase-Funktion in Frankfurt. Von dort geht er an Google Gemini über Vertex AI in der EU; das Foto wird dabei nicht gespeichert. Das Analyse-Ergebnis eines eigenen Scans hält der Server bis zu 24 Stunden vor, um bei einem erneuten Hochladen desselben Fotos dieselbe Antwort zu liefern, ohne den Scan erneut zu berechnen (Schutz vor Doppelabrechnung). Nach Ablauf der 24 Stunden löscht der Server es automatisch. Rechtsgrundlage ist deine ausdrückliche Einwilligung nach Art. 9 Abs. 2 lit. a DSGVO, die du jederzeit in den Einstellungen widerrufen kannst.

## Anonyme Anmeldung und Scan-Kontingent

Beim ersten Start meldet dich die App ohne Namen und ohne E-Mail mit einer zufälligen Nutzer-ID an. Zu dieser ID zählt der Server deine Scans, damit das Scan-Kontingent eingehalten wird (Art. 6 Abs. 1 lit. b DSGVO, Vertragserfüllung). Ohne Abo ist 1 Scan insgesamt enthalten, mit Pro 1 Scan pro Tag (nach UTC-Kalendertag).

## Gäste-Scan

Mit Pro und Gäste-Scan-Guthaben (gekauft oder durch Freundescode geschenkt) kannst du einen Scan für eine andere Person durchführen. Dabei werden Foto und Angaben dieser anderen Person verarbeitet. Die Person bestätigt auf deinem Gerät selbst, dass sie mindestens 16 Jahre alt ist, und erteilt selbst die ausdrückliche Einwilligung nach Art. 9 Abs. 2 lit. a DSGVO. Die Auswertung läuft wie bei deinem eigenen Scan (Supabase-Funktion in Frankfurt, Google Gemini über Vertex AI in der EU). Weder dein Gerät noch der Server speichern Foto, Angaben oder Ergebnis der Gast-Person, und Gast-Ergebnisse werden nie zum erneuten Abruf aufbewahrt. Der Server speichert nur pro verbrauchtem Gäste-Scan eine Zähler-Zeile mit deiner Nutzer-ID und einem Zeitstempel (Art. 6 Abs. 1 lit. b DSGVO, Vertragserfüllung gegenüber dir). Jeder Gäste-Versuch zählt außerdem zu deinen eigenen Versuchen pro Tag. Für die Daten der Gast-Person ist der oben genannte Verantwortliche ebenfalls verantwortlich. Die Gast-Person kann vor dem Senden des Fotos ablehnen oder abbrechen und sich an support@abpeak.app wenden.

## Freundescode

Mit einem Freundescode verknüpfen wir pseudonym zwei anonyme App-Konten (Nutzer-ID der werbenden und der geworbenen Person, Zeitstempel, gewährte Gäste-Scans), um die Belohnung zu vergeben (Art. 6 Abs. 1 lit. b DSGVO, Vertragserfüllung). Dazu gehören dein Freundescode (6 Zeichen), den wir mit deiner Nutzer-ID speichern, auch wenn ihn niemand einlöst, und der Zeitpunkt der Belohnung. Diese Daten werden gelöscht, wenn das anonyme Konto gelöscht wird. „Alle Daten löschen“ in der App entfernt die Daten auf deinem Gerät und löscht die vom Server vorgehaltenen Scan-Ergebnisse sofort. Scan-Zähler, Gäste-Scan- und Freundescode-Daten und das anonyme Server-Konto bleiben dabei bestehen. Die Löschung der Server-Daten kannst du per E-Mail an support@abpeak.app verlangen.

## Käufe

Abos kaufst und bezahlst du über Apple. RevenueCat verwaltet deinen Abo-Status und erhält dafür deine zufällige Nutzer-ID. Es gelten die Standard-Nutzungsbedingungen von Apple (EULA). Gekaufte Gäste-Scans verfallen nicht und sind nicht übertragbar. Erstattungen laufen über das Verfahren von Apple.

## Nutzungsstatistik

Mit TelemetryDeck zählen wir, wie die App genutzt wird, ohne personenbezogene Daten und ohne Tracking.

## Speicherdauer

Die Daten auf deinem Gerät bleiben, bis du sie mit „Alle Daten löschen“ entfernst oder die App löschst. Das Foto eines Scans speichert der Server nicht; das Ergebnis eines eigenen Scans hält er bis zu 24 Stunden vor und löscht es danach automatisch (siehe Scan-Analyse). Mit „Alle Daten löschen“ wird es auf dem Server sofort gelöscht, sofern das Gerät dabei online ist. Nutzer-ID und Scan-Zähler bleiben gespeichert, solange du AbPeak nutzt; auf Anfrage über support@abpeak.app löschen wir sie. Zähler-Zeilen für Gäste-Scans, gewährtes Guthaben und Daten zum Freundescode bleiben, bis das anonyme Konto gelöscht wird (Löschung auf Anfrage über support@abpeak.app).

## Diese Website

Die Website abpeak.app wird über GitHub Pages bereitgestellt (GitHub, Inc., 88 Colin P. Kelly Jr. Street, San Francisco, CA 94107, USA). Beim Aufruf verarbeitet GitHub technisch notwendige Daten, insbesondere deine IP-Adresse, Datum und Uhrzeit sowie Browser-Angaben, um die Seite auszuliefern und vor Missbrauch zu schützen. Rechtsgrundlage ist unser berechtigtes Interesse an einer sicheren und stabilen Bereitstellung (Art. 6 Abs. 1 lit. f DSGVO). Dabei können Daten in die USA übermittelt werden. Details: [GitHub-Datenschutzerklärung](https://docs.github.com/de/site-policy/privacy-policies/github-general-privacy-statement). Die Website setzt keine Cookies, nutzt kein Tracking und lädt keine Inhalte von Dritten.

## Deine Rechte

Nach der DSGVO hast du diese Rechte:

- Auskunft über deine Daten (Art. 15 DSGVO)
- Berichtigung falscher Daten (Art. 16 DSGVO)
- Löschung (Art. 17 DSGVO)
- Einschränkung der Verarbeitung (Art. 18 DSGVO)
- Datenübertragbarkeit (Art. 20 DSGVO)
- Widerspruch gegen die Verarbeitung (Art. 21 DSGVO)
- Widerruf einer Einwilligung mit Wirkung für die Zukunft (Art. 7 Abs. 3 DSGVO), auch der ausdrücklichen Einwilligung in die Verarbeitung von Gesundheitsdaten nach Art. 9 Abs. 2 lit. a DSGVO. Du widerrufst sie in den Einstellungen; die bis dahin erfolgte Verarbeitung bleibt rechtmäßig.
- Beschwerde bei einer Datenschutz-Aufsichtsbehörde (Art. 77 DSGVO)

Die Daten auf deinem Gerät und die auf dem Server vorgehaltenen Scan-Ergebnisse löschst du selbst mit „Alle Daten löschen“ in den Einstellungen. Ist das Gerät dabei offline, löscht die App trotzdem alles auf dem Gerät und weist dich darauf hin, dass die Löschung auf dem Server nicht geklappt hat; dann löscht der Server das Ergebnis spätestens nach 24 Stunden von selbst, oder du schreibst an support@abpeak.app. Für alle anderen Rechte schreib an support@abpeak.app.
