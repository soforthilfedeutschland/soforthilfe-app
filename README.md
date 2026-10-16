# Soforthilfe Zentrale (Handy-Fassung)

Passwortgeschützte Web-App der Soforthilfe-Firmenzentrale. Die App ist in `index.html`
mit AES-256-GCM verschlüsselt (Schlüssel aus dem Passwort per PBKDF2-SHA-256, 600.000 Runden).
Ohne Passwort ist nur die Anmeldeseite sichtbar. Alle App-Daten bleiben auf dem eigenen Gerät.

Erzeugt mit `npm run phone && npm run phone:locked` im Hauptprojekt.

`zentrale.html`: neue Zentrale (Stand 16.10.2026 abends) mit Zahnrad „Clara & KI-Einstellungen“, ohne Passwort
(Freigabe Yasin 16.10.2026). Enthält keine Schlüssel und keine Daten; der OpenAI-Schlüssel bleibt nur im Arbeitsspeicher
des Geräts. Erzeugt mit `npm run phone` im Hauptprojekt.
