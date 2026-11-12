# Cleso Host Dashboard

Kunden-Dashboard für **Cleso Host** – verbunden mit Pterodactyl.

## Features

- Login / Register / Logout
- Rollen: Inhaber · Admin · Technical · Developer · Kunde
- Server-Übersicht (Pterodactyl API vorbereitet)
- **Internes Guthaben** (kein Echtgeld – nur Discord-Giveaways)
- Tickets
- Live-Nachrichten (Chat)
- Team-Verwaltung & Credits vergeben

## Demo-Login

| E-Mail | Passwort | Rolle |
|--------|----------|-------|
| `justin@cleso-host.com` | `admin123` | Inhaber |

## Dateien

- `index.html` – Oberfläche
- `styles.css` – Design (dunkles Schwarz + Hellblau)
- `app.js` – Logik (Tickets, Chat, Credits, Auth)

Falls `app.js` noch fehlt oder unvollständig ist: die komplette Datei aus dem lokalen Build nach `/app.js` hochladen (GitHub → Add file → Upload).

## Lokal / Vercel

```bash
npx serve .
```

Oder den Ordner auf Vercel als Static Site deployen.

## Wichtig

Credits = **kein Echtgeld**. Nur internes Guthaben über Discord-Giveaways.
