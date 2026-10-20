<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dunkel.svg">
    <img alt="Logo von Gesetze für KI: eine Waage, deren Säule das MCP-Zeichen bildet" src="logo.svg" width="135">
  </picture>
</p>

<h1 align="center"><a href="https://gesetze-fuer-ki.de">Gesetze für KI</a></h1>

<p align="center"><b>Ihr KI-Assistent schlägt aktuelles Bundes- und Landesrecht nach. Kostenlos.</b></p>

<p align="center">
  Alles zum Einrichten und Benutzen steht auf <b><a href="https://gesetze-fuer-ki.de">gesetze-fuer-ki.de</a></b>:<br>
  <a href="https://gesetze-fuer-ki.de/verbinden/"><b>So verbinden Sie Ihren Assistenten</b></a>
</p>

<p align="center">
  <a href="https://liberapay.com/GesetzeFuerKI"><img alt="Über Liberapay unterstützen" src="https://img.shields.io/badge/Liberapay-unterst%C3%BCtzen-F6C915?logo=liberapay&logoColor=black"></a>
</p>

```text
https://gesetze-fuer-ki.de/mcp
```

## So hängt es zusammen

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="ablauf-dunkel.svg">
  <img alt="Ablauf: Die amtlichen Texte von gesetze-im-internet.de werden jede Nacht in das Repository bundesrecht übernommen, eine Markdown-Datei je Gesetz mit jeder Änderung als Commit. Der Server gesetze-fuer-ki holt sie stündlich, baut den Suchindex und stellt sie über MCP bereit. Ihr KI-Assistent schlägt darüber den Wortlaut nach." src="ablauf.svg" width="100%">
</picture>

- **[gesetze-fuer-ki](https://github.com/Gesetze-fuer-KI/gesetze-fuer-ki)**: der Server und die Webseite. Funktionsweise, selbst betreiben und mitmachen stehen dort.
- **[bundesrecht](https://github.com/Gesetze-fuer-KI/bundesrecht)**: alle Gesetze und Verordnungen des Bundes als Textdateien, jede Nacht aktualisiert, jede Änderung ein Commit.
- **landesrecht-…**: dasselbe für die Länder, ein Repository je Land, direkt vom amtlichen Landesportal (siehe unten).

## Landesrecht

Übernommen wird nur, was das Portal eines Landes erlaubt.

✅ **Enthalten:** [Bayern](https://github.com/Gesetze-fuer-KI/landesrecht-by) · [Nordrhein-Westfalen](https://github.com/Gesetze-fuer-KI/landesrecht-nw) · [Sachsen](https://github.com/Gesetze-fuer-KI/landesrecht-sn)

⏳ **Im Aufbau:** [Brandenburg](https://github.com/Gesetze-fuer-KI/landesrecht-bb): erlaubt, aber nur ein Abruf alle 20 Sekunden; der erste Abgleich dauert zwei Nächte.

❌ **Nicht erlaubt:**

- Das Portal sperrt automatische Abrufe in seiner robots.txt: [Baden-Württemberg](https://github.com/Gesetze-fuer-KI/landesrecht-bw) · [Berlin](https://github.com/Gesetze-fuer-KI/landesrecht-be) · [Hamburg](https://github.com/Gesetze-fuer-KI/landesrecht-hh) · [Hessen](https://github.com/Gesetze-fuer-KI/landesrecht-he) · [Mecklenburg-Vorpommern](https://github.com/Gesetze-fuer-KI/landesrecht-mv) · [Rheinland-Pfalz](https://github.com/Gesetze-fuer-KI/landesrecht-rp) · [Saarland](https://github.com/Gesetze-fuer-KI/landesrecht-sl) · [Sachsen-Anhalt](https://github.com/Gesetze-fuer-KI/landesrecht-st) · [Schleswig-Holstein](https://github.com/Gesetze-fuer-KI/landesrecht-sh) · [Thüringen](https://github.com/Gesetze-fuer-KI/landesrecht-th)
- Der Betreiber behält sich die Nutzung der Texte vor: [Niedersachsen](https://github.com/Gesetze-fuer-KI/landesrecht-ni)
- Das Portal sperrt Abrufe aus Rechenzentren: [Bremen](https://github.com/Gesetze-fuer-KI/landesrecht-hb)

Im Repository jedes fehlenden Landes steht, woran es genau scheitert, mit einer Vorlage, um sich beim Land für freien Zugang einzusetzen. Mehr unter [Daten und Grenzen](https://gesetze-fuer-ki.de/daten/#landesrecht).

---

<sub>Keine Rechtsberatung: Der Dienst liefert Gesetzestexte; maßgeblich ist die amtliche Fassung. · [Unterstützen](https://gesetze-fuer-ki.de/unterstuetzen/) · [Impressum](https://gesetze-fuer-ki.de/impressum/) · [Datenschutz](https://gesetze-fuer-ki.de/datenschutz/)</sub>
