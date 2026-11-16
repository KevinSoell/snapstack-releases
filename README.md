# Screenshot App (macOS)

Screenshots, Scrolling-Screenshots und ein Editor zum Markieren – für Macs mit
Apple-Chip (M1 oder neuer) und macOS 14 oder neuer. Intel-Macs werden nicht unterstützt.

**Download:** [Screenshot-App.dmg](https://github.com/KevinSoell/snapstack-releases/releases/latest/download/Screenshot-App.dmg)

1. DMG öffnen, **Screenshot App** auf **Applications** ziehen.
2. Screenshot App starten. Beim ersten Start meldet macOS, dass die App nicht überprüft
   werden kann (sie ist privat signiert): **Fertig** → Systemeinstellungen →
   Datenschutz & Sicherheit → bei „Screenshot App“ **Dennoch öffnen** (je nach macOS
   „Trotzdem öffnen“). Nur einmal nötig.
3. Beim ersten Screenshot **Bildschirmaufnahme** erlauben (Systemeinstellungen →
   Datenschutz & Sicherheit → Bildschirm- & Systemaudioaufnahme), für
   Scrolling-Screenshots auch **Bedienungshilfen**. Danach die App einmal neu öffnen.

Die App sitzt oben rechts in der Menüleiste. Neue Versionen meldet sie selbst
(einmal am Tag; installiert wird erst, wenn du zustimmst).

## Datenschutz (kurz)

- Screenshots, Verlauf und Einstellungen bleiben auf deinem Mac
  (`~/Library/Application Support/com.kevinsoell.snapstack`); es gibt kein Konto, keine
  Telemetrie und keinen Upload in dieser Version.
- Netzwerk nutzt die App nur für die tägliche Update-Prüfung bei GitHub. Dabei sieht
  GitHub – wie bei jedem Download – deine IP-Adresse und die App-Version, nichts von
  deinen Screenshots.
- Sicherheitsprobleme bitte über [SECURITY.md](SECURITY.md) melden.

Dieses Repository enthält nur fertige, signierte Downloads und den Update-Feed –
keinen Quellcode. Drittanbieter-Lizenzen liegen in der App unter
`Contents/Resources/Licenses` (libwebp, BSD; Sparkle, MIT).
