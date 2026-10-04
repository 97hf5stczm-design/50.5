RSVP-E-Mail-Anbindung
======================

Die RSVP-Antworten werden per FormSubmit AJAX an folgende Adresse übermittelt:
Rasiemon@icloud.com

WICHTIG: FormSubmit muss die Formularadresse einmalig aktivieren.
1. Die Website über HTTPS/HTTP hosten (nicht direkt als file:// öffnen).
2. Eine Test-RSVP absenden.
3. Die Aktivierungs-E-Mail von FormSubmit im Postfach Rasiemon@icloud.com öffnen und den Aktivierungslink bestätigen.
4. Danach werden weitere RSVP-Antworten an diese Adresse weitergeleitet.

Die Website zeigt nach erfolgreicher Übermittlung weiterhin die eigene Bestätigungsseite an. Bei einem Fehler bleibt der Gast im Formular und erhält eine Fehlermeldung.

Technik:
- AJAX-Endpunkt: https://formsubmit.co/ajax/Rasiemon@icloud.com
- E-Mail-Betreff: RSVP · 50.5 Jahre · 19.06.2027 · Thusis · [Name]
- E-Mail-Template: table
- Honeypot gegen einfache Spam-Einsendungen

Hinweis zum Datenschutz:
Die im RSVP eingegebenen Daten werden an FormSubmit übertragen, damit der Dienst die E-Mail-Zustellung übernehmen kann. Vor dem öffentlichen Einsatz sollte die Einladung um einen kurzen Datenschutzhinweis ergänzt werden.
