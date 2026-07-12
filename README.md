# brainz-docs — Mintlify-Doku der Brainz-Features

Vollständiges [Mintlify](https://mintlify.com)-Projekt (`docs.json` + MDX-Seiten).
Sprache: Deutsch. Interne Links folgen dem Site-Schema `/features/<slug>` —
die Seiten liegen deshalb unter `features/`.

> **Hinweis Repo-Layout:** Auf der Entwickler-Maschine ist `brainz-docs/` ein
> **geschachteltes eigenes Git-Repository** (die Mintlify-Site). Im
> PostgresBackend-Repo liegt dieser Ordner als Quell-Spiegel, damit
> Cloud-Sessions die Doku aktualisieren können — Änderungen von hier ins
> Docs-Repo übernehmen (Dateien 1:1 kopieren, Struktur ist identisch).

Lokale Vorschau: `npx mint dev` in diesem Ordner.

| Seite | Thema |
| --- | --- |
| `index.mdx` | Überblick + Einstieg |
| `features/drop.mdx` | Universelle Inhaltserfassung (`POST /api/drop`) inkl. Medien-Promotion |
| `features/omnibar.mdx` | Intent-Engine, Direkt-Antworten, Medien-Erkennung, Tenant-Vokabular |
| `features/enrichment.mdx` | Globales Weltwissen, Medien-/Feld-Enrichment, Knowledge Entities |
| `features/mediathek.mdx` | Medien-Pipeline: ein `document`-Zweig, Enrichment, Status, Karten |
| `features/nexus.mdx` | Connection Intelligence + Nexus-Pfad (Mobile) |
| `features/meetings.mdx` | Meeting Companion |
| `features/skills.mdx` | Deklarative KI-Wizards + SKILL.md/MCP-Prompt-Import |
| `features/render-ui.mdx` | Karten-Engine, alle Surfaces, Bundle-Auslieferung (brainz-detail-host) |
| `features/desktop.mdx` | Desktop-Frontend: Karten-Ansicht, Plugin-Aktionen, Plugin-Store |
| `features/chrome-extension.mdx` | Brainz Clipper: natives Detail, Plugin-Aktionen, MV3 |
| `features/plugins.mdx` | Konsolidiertes Plugin-System (deklarativ) + Mobile-Capabilities |

Historie: bis Juli 2026 lagen die ersten drei Seiten unter `docs/doc-site-drafts/`;
seit Juli 2026 ist der Ordner ein vollständiges Mintlify-Projekt.
