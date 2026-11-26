# mothership-web

Frontend-dashboard för **Mothership Dashboard**-plattformen.

## Översikt
`mothership-web` är byggt med **React + TypeScript + Vite**. Den ansvarar för att visa:
- **Översikt:** Serverhälsa, CPU, RAM, disk, snabbstatus för tjänster och säkerhet.
- **Tjänstekatalog:** Uptime-procent, svarstider, statusgrafer.
- **Incidenter:** Visa, skapa och hantera driftstörningar.
- **Docker & Säkerhet:** Containrar, portar, UFW-brandvägg och Fail2ban.
- **Hermes:** Status och hantering för AI-agenten.

Paketeras i en lättviktig container med `nginxinc/nginx-unprivileged` för hög säkerhet (non-root).
