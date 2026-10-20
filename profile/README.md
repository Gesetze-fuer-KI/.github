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
- **landesrecht-…**: dasselbe für die Länder, direkt von den amtlichen Landesportalen, ein Repository je Land. Nur vier Länder lassen den automatischen Abruf zu; bei den anderen steht im Repository, woran es scheitert, mit einer Vorlage, um sich beim Land dafür einzusetzen. Mehr unter [Daten und Grenzen](https://gesetze-fuer-ki.de/daten/#landesrecht).

| Land | | Abruf | Repository |
|---|---|---|---|
| Baden-Württemberg | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-bw](https://github.com/Gesetze-fuer-KI/landesrecht-bw) |
| Bayern | ✅ | Nutzungshinweise erlauben die Weiterverwendung | [landesrecht-by](https://github.com/Gesetze-fuer-KI/landesrecht-by) |
| Berlin | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-be](https://github.com/Gesetze-fuer-KI/landesrecht-be) |
| Brandenburg | ⏳ | erlaubt, erster Abgleich läuft (alle 20 Sekunden ein Abruf) | [landesrecht-bb](https://github.com/Gesetze-fuer-KI/landesrecht-bb) |
| Bremen | ❌ | Portal sperrt Abrufe aus Rechenzentren | [landesrecht-hb](https://github.com/Gesetze-fuer-KI/landesrecht-hb) |
| Hamburg | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-hh](https://github.com/Gesetze-fuer-KI/landesrecht-hh) |
| Hessen | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-he](https://github.com/Gesetze-fuer-KI/landesrecht-he) |
| Mecklenburg-Vorpommern | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-mv](https://github.com/Gesetze-fuer-KI/landesrecht-mv) |
| Niedersachsen | ❌ | Betreiber behält sich die Nutzung der Texte vor | [landesrecht-ni](https://github.com/Gesetze-fuer-KI/landesrecht-ni) |
| Nordrhein-Westfalen | ✅ | kein Verbot | [landesrecht-nw](https://github.com/Gesetze-fuer-KI/landesrecht-nw) |
| Rheinland-Pfalz | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-rp](https://github.com/Gesetze-fuer-KI/landesrecht-rp) |
| Saarland | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-sl](https://github.com/Gesetze-fuer-KI/landesrecht-sl) |
| Sachsen | ✅ | kein Verbot | [landesrecht-sn](https://github.com/Gesetze-fuer-KI/landesrecht-sn) |
| Sachsen-Anhalt | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-st](https://github.com/Gesetze-fuer-KI/landesrecht-st) |
| Schleswig-Holstein | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-sh](https://github.com/Gesetze-fuer-KI/landesrecht-sh) |
| Thüringen | ❌ | Portal sperrt automatische Abrufe (robots.txt) | [landesrecht-th](https://github.com/Gesetze-fuer-KI/landesrecht-th) |

✅ enthalten · ⏳ im Aufbau · ❌ nicht erlaubt

---

<sub>Keine Rechtsberatung: Der Dienst liefert Gesetzestexte; maßgeblich ist die amtliche Fassung. · [Unterstützen](https://gesetze-fuer-ki.de/unterstuetzen/) · [Impressum](https://gesetze-fuer-ki.de/impressum/) · [Datenschutz](https://gesetze-fuer-ki.de/datenschutz/)</sub>
