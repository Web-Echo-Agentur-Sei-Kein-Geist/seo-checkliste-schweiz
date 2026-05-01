# SEO-Checkliste für Schweizer KMU-Websites 🇨🇭

**Vollständige, praxiserprobte SEO-Checkliste für KMU-Websites in der Schweiz**

Zusammengestellt von [web-echo.ch](https://web-echo.ch) auf Basis von Audits Schweizer Unternehmenswebsites.  
Stand: 2025/2026 · Getestet für WordPress, aber plattformunabhängig anwendbar.

---

## Warum diese Checkliste?

Standard-SEO-Checklisten ignorieren Schweiz-spezifische Faktoren: lokale Verzeichnisse wie local.ch, mehrsprachige Anforderungen, das Fehlen einer Google Business Profile-Pflicht bei nationalen Anbietern, und das besondere Wettbewerbsumfeld im DACH-Raum.

Diese Liste deckt beides ab: universelle Best Practices **und** Schweizer Besonderheiten.

---

## Checklisten-Übersicht

- [1. Technisches SEO](#1-technisches-seo)
- [2. On-Page SEO](#2-on-page-seo)
- [3. Content-Qualität](#3-content-qualität)
- [4. Local SEO Schweiz](#4-local-seo-schweiz)
- [5. Core Web Vitals & Performance](#5-core-web-vitals--performance)
- [6. Schema Markup](#6-schema-markup)
- [7. Linkprofil](#7-linkprofil)
- [8. Monitoring & Reporting](#8-monitoring--reporting)

---

## 1. Technisches SEO

### Crawling & Indexierung
- [ ] `robots.txt` vorhanden und korrekt (kein Blockieren wichtiger Ressourcen)
- [ ] XML-Sitemap vorhanden, in Google Search Console eingereicht
- [ ] Keine wichtigen Seiten auf `noindex` gesetzt (z.B. versehentlich über WordPress-Einstellung)
- [ ] Keine Duplicate-Content-Probleme durch trailing slash / www vs. non-www
- [ ] Kanonische URLs (`rel="canonical"`) auf allen Seiten korrekt gesetzt
- [ ] Paginierte Seiten korrekt behandelt (canonical oder rel prev/next)
- [ ] Hreflang-Tags bei mehrsprachigen Sites korrekt implementiert (DE/FR/IT bei CH relevant)

### HTTPS & Sicherheit
- [ ] HTTPS auf der gesamten Domain aktiv
- [ ] Alle HTTP-URLs werden auf HTTPS weitergeleitet (301, nicht 302)
- [ ] Kein Mixed Content (HTTP-Ressourcen auf HTTPS-Seite)
- [ ] HSTS-Header gesetzt

### URL-Struktur
- [ ] URLs sind kurz, beschreibend, kleingeschrieben
- [ ] Keine Sonderzeichen, keine Umlaute in URLs (ä→ae, ü→ue, ö→oe oder englische Variante)
- [ ] Logische Verzeichnisstruktur (z.B. `/leistungen/seo/` statt `/page-id=47`)
- [ ] Keine Redirect-Ketten (A→B→C — immer direkt auf das Ziel)
- [ ] 404-Seite vorhanden und hilfreich gestaltet

### Interne Verlinkung
- [ ] Alle wichtigen Seiten sind von mindestens einer anderen Seite verlinkt
- [ ] Keine verwaisten Seiten ("Orphan Pages")
- [ ] Ankertext ist beschreibend (nicht "hier klicken")
- [ ] Keine kaputten internen Links (Screaming Frog oder Ahrefs prüfen)

---

## 2. On-Page SEO

### Title Tags
- [ ] Jede Seite hat einen einzigartigen Title Tag
- [ ] Länge: 50–60 Zeichen (nicht zu lang für SERP-Abschneidung)
- [ ] Primäres Keyword steht am Anfang
- [ ] Brand-Name am Ende (Format: `Keyword – Unterseiten-Thema | Marke`)
- [ ] Keine Keyword-Stuffing

### Meta Descriptions
- [ ] Jede Seite hat eine einzigartige Meta Description
- [ ] Länge: 120–155 Zeichen
- [ ] Enthält eine Handlungsaufforderung
- [ ] Kein direktes Ranking-Signal, aber beeinflusst CTR

### Überschriften (H1–H6)
- [ ] Genau ein `H1` pro Seite
- [ ] H1 enthält das Haupt-Keyword natürlich
- [ ] Logische Hierarchie (H2 → H3 → H4, nicht überspringen)
- [ ] Keine Überschriften nur aus Styling-Gründen (Absatz statt H2 nutzen)

### Bilder
- [ ] Alle Bilder haben beschreibende `alt`-Attribute
- [ ] Dateinamen beschreibend (nicht `IMG_1234.jpg`, sondern `seo-agentur-bern.jpg`)
- [ ] Bilder komprimiert (WebP bevorzugt, unter 200 KB pro Bild anstreben)
- [ ] Keine Copyright-Verletzungen bei Stockfotos

### Inhalte
- [ ] Primäres Keyword im ersten Absatz (erste 100 Wörter)
- [ ] Synonyme und semantisch verwandte Begriffe verwendet (LSI)
- [ ] Inhalte beantworten die Suchintention der Zielgruppe vollständig
- [ ] Keine "Thin Content"-Seiten unter 300 Wörter (ausser Kontakt/Impressum)

---

## 3. Content-Qualität

### E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness)
- [ ] Autorenprofile mit echtem Namen und Foto vorhanden
- [ ] Quellenangaben bei Fakten und Statistiken
- [ ] "Über uns"-Seite mit echten Personen und Qualifikationen
- [ ] Kontaktdaten prominent sichtbar (Telefon / E-Mail / Kontaktformular)
- [ ] Impressum vorhanden (in der Schweiz gesetzlich vorgeschrieben für kommerzielle Websites)
- [ ] Datenschutzerklärung vorhanden (nDSG-konform, Stand September 2023)

### Aktualität
- [ ] Keine veralteten Inhalte (Daten, Angebote, Preise von vor 2+ Jahren)
- [ ] Letztes Bearbeitungsdatum bei Artikeln sichtbar
- [ ] Blog/Neuigkeiten-Bereich regelmässig aktualisiert (mind. 1×/Monat)

### Mehrsprachigkeit (Schweiz-spezifisch)
- [ ] Bei mehrsprachigen Sites: jede Sprache hat eigene URLs (nicht nur übersetzter Content auf gleicher URL)
- [ ] Hreflang korrekt für `de-CH`, `fr-CH`, `it-CH` (nicht nur `de`, `fr`, `it`)
- [ ] Übersetzungen sind echte Übersetzungen, kein Machine-Translation ohne Überarbeitung

---

## 4. Local SEO Schweiz

### Google Business Profile
- [ ] Google Business Profile (GBP) erstellt und verifiziert (sofern Standort-Relevanz vorhanden)
- [ ] Kategorie korrekt gewählt (primäre Kategorie entscheidend)
- [ ] Öffnungszeiten aktuell
- [ ] Mindestens 5 Fotos hochgeladen
- [ ] Auf Bewertungen reagiert (alle, positiv und negativ)

### Schweizer Verzeichnisse (ohne NAP-Pflicht wo möglich)
- [ ] [local.ch](https://www.local.ch) — Eintrag vorhanden und aktuell
- [ ] [search.ch](https://www.search.ch) — Eintrag vorhanden (läuft über localsearch zusammen)
- [ ] [moneyhouse.ch](https://www.moneyhouse.ch) — Firmeneintrag mit Website-Link
- [ ] [swissfirms.ch](https://www.swissfirms.ch) — Handelskammer-Eintrag
- [ ] [firma-finden.ch](https://firma-finden.ch) — Eintrag vorhanden
- [ ] [waisch.ch](https://www.waisch.ch) — Eintrag vorhanden
- [ ] [Wikidata](https://www.wikidata.org) — Firmeneintrag mit P856 (offizielle Website)

### NAP-Konsistenz (Name, Adresse, Telefon)
- [ ] Name, Adresse und Telefonnummer **überall identisch** geschrieben
- [ ] Schweizer Telefonnummern im Format `+41 XX XXX XX XX` oder `0XX XXX XX XX` (konsistent wählen)
- [ ] Kein Mischmasch zwischen GmbH / AG / ohne Rechtsform in verschiedenen Verzeichnissen

### Lokale Keywords
- [ ] Ortsname in Title Tags der relevanten Seiten
- [ ] Ortsbezogene Landingpages bei mehreren Standorten (separate Seite pro Standort)
- [ ] "Schweiz"-Keywords genutzt (z.B. "SEO Agentur Schweiz" statt nur "SEO Agentur")

---

## 5. Core Web Vitals & Performance

### Messung
- [ ] Google PageSpeed Insights geprüft (pagespeed.web.dev)
- [ ] Lighthouse-Score Mobile ≥ 70 (Performance)
- [ ] LCP (Largest Contentful Paint) ≤ 2,5 Sek.
- [ ] FID/INP (Interaction to Next Paint) ≤ 200 ms
- [ ] CLS (Cumulative Layout Shift) ≤ 0,1

### Typische Probleme bei WordPress-Sites
- [ ] Caching-Plugin aktiv (WP Rocket, W3 Total Cache oder Hosting-seitiges Caching)
- [ ] Bilder werden lazy-geladen (ausser above-the-fold Hauptbild)
- [ ] Render-blocking CSS/JS minimiert
- [ ] Google Fonts lokal geladen (kein externer Request zu Google-Servern — auch DSGVO-relevant)
- [ ] Hosting in der Schweiz oder DACH (Latenz für CH-Nutzer)

---

## 6. Schema Markup

### Basis
- [ ] `Organization` oder `LocalBusiness` auf der Startseite
- [ ] `WebSite` mit `SearchAction` (für Sitelinks-Suchfeld)
- [ ] `BreadcrumbList` auf allen Unterseiten
- [ ] `FAQPage` bei Seiten mit FAQ-Abschnitt

### Schweiz-spezifisch
- [ ] `addressCountry: "CH"` in LocalBusiness-Schema
- [ ] `areaServed` korrekt gesetzt (Land oder Kanton)
- [ ] `sameAs`-Array mit Wikidata-URL, LinkedIn, relevante Verzeichnisse

### Prüfung
- [ ] Schema mit [schema.org Validator](https://validator.schema.org) geprüft
- [ ] Google Rich Results Test ([search.google.com/test/rich-results](https://search.google.com/test/rich-results)) ohne Fehler

---

## 7. Linkprofil

### Analyse
- [ ] Linkprofil in Ahrefs oder SEMrush geprüft
- [ ] Keine toxischen Links aus Linkfarmen / PBNs
- [ ] Anchor-Text-Verteilung natürlich (kein Over-Optimization auf ein Keyword)
- [ ] Verhältnis verweisende Domains zu Backlinks prüfen (zu hohe Konzentration = Risiko)

### Aufbau (Mindeststandard für CH-KMU)
- [ ] Einträge in den wichtigsten CH-Verzeichnissen (siehe Local SEO oben)
- [ ] Branchenrelevante Verzeichnisse (z.B. swissmadesoftware.org für Tech)
- [ ] Mindestens 1 Editorial-Mention auf relevanter DE/AT/CH-Publikation

---

## 8. Monitoring & Reporting

### Setup (einmalig)
- [ ] Google Search Console verifiziert
- [ ] Google Analytics 4 (GA4) konfiguriert und DSGVO-konform (kein Google-Server-IP-Übertragung ohne Consent)
- [ ] Matomo als Alternative zu GA4 bei strengen Datenschutzanforderungen geprüft
- [ ] Ahrefs / SEMrush / SISTRIX für Ranking-Tracking eingerichtet

### Laufend (monatlich)
- [ ] Ranking-Entwicklung für Top-Keywords prüfen
- [ ] GSC: neue Crawling-Fehler, Coverage-Probleme?
- [ ] GSC: Core Web Vitals Report — neue Probleme?
- [ ] Neue Backlinks: relevant oder toxisch?
- [ ] Organischen Traffic-Trend analysieren (Basis: GA4 oder Matomo)

---

## Verwendung dieser Checkliste

**Als Markdown-Datei:** Direkt in Notion, Obsidian oder als GitHub-Issue verwenden.  
**Als Projektvorlage:** Fork dieses Repos und passe die Checkliste für dein Projekt an.  
**Mit Kunden:** Leere Checkboxen als Basis für Audit-Gespräche nutzen.

---

## Verwandte Ressourcen

- [wordpress-snippets-de](https://github.com/Web-Echo-Agentur-Sei-Kein-Geist/wordpress-snippets-de) — PHP-Snippets zur technischen Umsetzung
- [web-echo.ch/blog](https://web-echo.ch/blog) — Vertiefende Artikel zu einzelnen Themen

---

## Lizenz

MIT — frei nutzbar, auch kommerziell. Kein Attributionszwang, aber ein ⭐ ist immer willkommen.

---

## Maintainer

[web-echo.ch](https://web-echo.ch) — SEO- & WordPress-Agentur, Schweiz  
Verbesserungsvorschläge? [Issue öffnen](https://github.com/Web-Echo-Agentur-Sei-Kein-Geist/seo-checkliste-schweiz/issues) oder Pull Request einreichen.
