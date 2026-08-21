# Chasing Toblerone

Roadbook, Hotel & Zimmerplan-App für die "Chasing Toblerone" Radtour (Barcelona ↔ Andorra, Chasing Project × MDNSS, 4ª edición).

Single-page App (`index.html`), kein Build-Schritt nötig. Persistenz läuft über Supabase (Projekt "MDNSS 24h", Tabelle `toblerone_kv`) mit öffentlichem anon-Key im Client — die "Modo Organización" ist nur clientseitig per Passwort geschützt, keine echte Auth.

## Deploy

Statisches Hosting (z. B. Netlify): Publish-Verzeichnis ist das Repo-Root (`index.html` + `_headers`).
