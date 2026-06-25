<!--
Datei: README.md
Zweck: Gibt einen schnellen Ueberblick ueber die Inhalte dieses Repositories.
Grenze: Keine vollstaendige ICAROS-Dokumentation, sondern Einstiegspunkt.
-->

# Erstellen eines Clients 🚀

Dieses Repository enthaelt die kleinste brauchbare Systematik, um einen eigenen
Client mit dem ICAROS Host zu verbinden.

## Was ist drin? 📦

- 🤝 `student-handshake-example.ts` - Beispielskript fuer Anmeldung beim Host und Heartbeats.
- 🎮 `student-control-stream-example.ts` - Beispielskript fuer Controller-Daten per WebSocket.
- 📘 `client-connection.md` - Anleitung zu Endpunkten, Nachrichten und typischen Fehlern.
- 🧠 `LM_PROMPT.md` - Prompt fuer LLMs, um die Systematik in ein bestehendes Projekt zu integrieren.

## Was ist nicht drin? ✂️

Keine VR-Logik, kein Rendering, keine Szenen, keine Physik und keine Framework-Vorgabe.
Der Host-Teil soll klein bleiben: Handshake, Heartbeat, Controller-Stream.

## Startpunkt 🧭

Lies zuerst `client-connection.md`. Danach kannst du die zwei TypeScript-Dateien
in dein Projekt uebernehmen oder als Vorlage fuer deine eigene Struktur nutzen.
