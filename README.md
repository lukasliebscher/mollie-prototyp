# helloCash × Mollie – Onboarding-Prototyp

Ein klickbarer, interaktiver Prototyp für das **Kartenzahlung-Onboarding mit Mollie** in helloCash.
Komplett im Browser bedienbar, keine Anmeldung nötig.

**▶︎ Live ansehen:** https://lukasliebscher.github.io/mollie-prototyp/

## Was der Prototyp zeigt

Der gesamte Weg vom Erstkontakt bis zur ersten Kartenzahlung – als zusammenhängender Flow:

1. **Landing / Registrierung** – Einstiegsseite mit E-Mail-Anmeldung.
2. **helloCash Backoffice** – die interne „Kartenzahlung"-Seite; die Onboarding-Umfrage startet automatisch als Dialog darüber.
3. **Geführte Umfrage** – kleine Schritt-für-Schritt-Fragen zu Unternehmen und Eigentümer:in (statt einer dichten Formularmaske).
4. **Tarifauswahl** – Mollie Flat vs. Pay-per-Use, der passende Tarif ist anhand der Antworten **vorausgewählt** (mit Preis & Transaktionsgebühr, monatlich/jährlich).
5. **Gerät koppeln** – je nach Setup entweder **QR-Code** (separates Terminal/Smartphone) oder **Pairing-Code + „Jetzt konfigurieren"** (Tap to Pay auf demselben Gerät).
6. **Mollie-Tap-App (simuliert)** – Token einfügen, „Terminal koppeln".
7. **Bestätigung** – Terminal erfolgreich gekoppelt, Aufforderung zur ersten Zahlung.
8. **Zahlungsmaske & „Karte vorhalten"-Animation** – Betrag eintippen, bezahlen, Erfolg.

## Hinweise

- **Demodaten:** Die Formularfelder sind zum schnellen Durchklicken vorausgefüllt (im Code über `PREFILL` abschaltbar).
- **Platzhalter:** QR-Code und Pairing-Code sind realistische Attrappen – nicht echt scanbar; es findet keine echte Mollie-Verbindung statt.
- **Zweck:** reiner UX-/Ablauf-Prototyp zur Abstimmung, kein Produktivcode.

## Technik

Eine einzige, eigenständige HTML-Datei (`index.html`) – kein Build, keine externen Abhängigkeiten.
Lokal einfach die Datei im Browser öffnen.
