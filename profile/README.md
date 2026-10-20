<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dunkel.svg">
    <img alt="Logo von Gesetze für KI: eine Waage, deren Säule das MCP-Zeichen bildet" src="logo.svg" width="120">
  </picture>
</p>

<h1 align="center"><a href="https://gesetze-fuer-ki.de">Gesetze für KI</a></h1>

<p align="center">
  <a href="https://liberapay.com/GesetzeFuerKI"><img alt="Über Liberapay unterstützen" src="https://img.shields.io/badge/Liberapay-unterst%C3%BCtzen-F6C915?logo=liberapay&logoColor=black"></a>
</p>

<p align="center"><b>Das aktuelle Bundesrecht für KI-Assistenten: kostenlos, ohne Anmeldung, ohne Werbung.</b></p>

Gesetze für KI ist ein öffentlicher [MCP-Server](https://modelcontextprotocol.io) mit rund 6.100 Gesetzen und Verordnungen des Bundes, jede Nacht abgeglichen mit den amtlichen Texten auf [gesetze-im-internet.de](https://www.gesetze-im-internet.de). Claude, ChatGPT und andere Assistenten schlagen damit den Wortlaut nach, statt aus dem Gedächtnis zu zitieren, und antworten mit Paragraf, Stand und Link zur Quelle.

```text
https://gesetze-fuer-ki.de/mcp
```

Wie man den eigenen Assistenten verbindet, steht auf **[gesetze-fuer-ki.de](https://gesetze-fuer-ki.de/verbinden/)**.

## Repositories

- **[gesetze-fuer-ki](https://github.com/Gesetze-fuer-KI/gesetze-fuer-ki)**: der MCP-Server, die Aufbereitung der Gesetze und die Webseite.
- **[gesetze](https://github.com/Gesetze-fuer-KI/gesetze)**: das gesamte Bundesrecht als Markdown, eine Datei je Gesetz. Jede Nacht abgeglichen; jede Änderung ist ein Commit, den man Zeile für Zeile nachlesen kann.

## So hängt es zusammen

```mermaid
flowchart TB
    A(["Amtliche Texte&nbsp;&nbsp;<br/>gesetze-im-internet.de&nbsp;&nbsp;&nbsp;"])
    B["Repository gesetze&nbsp;&nbsp;<br/>Markdown mit Historie&nbsp;&nbsp;"]
    C["Server gesetze-fuer-ki&nbsp;&nbsp;<br/>Suchindex und MCP&nbsp;&nbsp;"]
    D(["Ihr KI-Assistent&nbsp;&nbsp;"])
    A -->|jede Nacht| B -->|stündlich| C -->|MCP| D
```

## Unterstützen

Der Dienst wird privat betrieben. Wer die Kosten für Server und Domain mittragen möchte, findet alles auf [gesetze-fuer-ki.de/unterstuetzen](https://gesetze-fuer-ki.de/unterstuetzen/) oder direkt auf [Liberapay](https://liberapay.com/GesetzeFuerKI). Ein Beitrag ist eine freiwillige Unterstützung, keine steuerlich absetzbare Spende.

Fehler in einem Gesetz oder eine Suche, die nichts findet? Bitte als [Issue](https://github.com/Gesetze-fuer-KI/gesetze-fuer-ki/issues) melden.

---

<sub>Keine Rechtsberatung: Der Dienst liefert Gesetzestexte; maßgeblich ist die amtliche Fassung. · [Impressum](https://gesetze-fuer-ki.de/impressum/) · [Datenschutz](https://gesetze-fuer-ki.de/datenschutz/)</sub>
