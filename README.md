# 📡 Themenreport

> **Alle News Deutschlands auf einen Blick!**

Dauerbeobachtung der Pressestellen aller 16 Bundesländer. Je Bundesland eine tagesaktuelle Presseschau, strukturiert nach Monat und Pressequelle.

## 🇩🇪 Bundesländerübersicht

👉 [**Deutschlandweite Bundesländerübersicht**](Uebersicht.md) — alle Länder mit Quellen und aktuellstem Stand auf einer Seite.

## 🗺️ Bundesländer

- [Baden-Württemberg](baden-wuerttemberg/)
- [Bayern](bayern/)
- [Berlin](berlin/)
- [Brandenburg](brandenburg/)
- [Bremen](bremen/)
- [Hamburg](hamburg/)
- [Hessen](hessen/)
- [Mecklenburg-Vorpommern](mecklenburg-vorpommern/)
- [Niedersachsen](niedersachsen/)
- [Nordrhein-Westfalen](nordrhein-westfalen/)
- [Rheinland-Pfalz](rheinland-pfalz/)
- [Saarland](saarland/)
- [Sachsen](sachsen/)
- [Sachsen-Anhalt](sachsen-anhalt/)
- [Schleswig-Holstein](schleswig-holstein/)
- [Thüringen](thueringen/)
- [**Bund (Bundesebene)**](bund/)

---

### 📂 Struktur

Jedes Bundesland sowie der Bund enthalten Reports nach Monat und Quelle verschachtelt:

```
<bundesland>/  (bzw. bund/)
└── YYYY-MM/
    ├── Presseschau/
    │   └── YYYY-MM-DD-report.md
    └── Themen-Cluster/
        └── YYYY-MM-DD-cluster-update.md

<bundesland>/README.md   = Startseite (neuester Cluster-Report als Volltext)
```

**Täglich aktualisiert:** 16 Bundesland-Cluster-Reports + 1 Bund-Cluster-Report (Batch-Job), plus Presseschau aller Länder.