# Bachelorarbeit – Politikwissenschaften B.A.

**Titel:** Der Einfluss von ICT-Investitionen auf die Arbeitslosigkeit in verschiedenen Bildungsgruppen in OECD-Ländern\
**Autor:** Tobias A. Rau\
**Universität:** Goethe-Universität Frankfurt\
**Fachbereich:** Fachbereich 03 – Geisteswissenschaften\
**Studiengang:** Politikwissenschaften B.A. mit Nebenfach Soziologie B.A.\
**Abgabedatum:** TODO\
**Projektarchivierung:** [GitHub Repository](https://github.com/TAR-IT/bachelorthesis)

---

## Projektbeschreibung
Diese Bachelorarbeit untersucht den Zusammenhang zwischen **Investitionen in Informations- und Kommunikationstechnologie (ICT)** und der **Arbeitslosigkeit in verschiedenen Bildungsgruppen** in OECD-Ländern. Die Analyse basiert auf **Paneldaten (2005–2022)** und verwendet **Fixed Effects-Modelle** zur empirischen Untersuchung der Hypothesen.

### Forschungsfrage
> *Wie beeinflussen nationale Investitionen in Informations- und Kommunikationstechnologien die Arbeitslosenquoten verschiedener Bildungsniveaus in Wohlfahrtsstaaten?*

### Hypothesen
- **H1:** Länder, in denen verstärkt in Informations- und Kommunikationstechnologien investiert wird, weisen eine geringere Arbeitslosenquote unter hochqualifizierten Arbeitskräften auf.
- **H2:** In Ländern mit hohen ICT-Investitionen verlagert sich die Arbeitslosigkeit auf niedrigqualifizierte Arbeitskräfte.
- **H3:** Der Typ des Wohlfahrtsstaates hat Einfluss auf die Polarisierung des Arbeitsmarktes. Länder mit stark entwickelten wohlfahrtsstaatlichen Systemen und flexiblen Arbeitsmarktstrukturen zeigen eine geringere Polarisierung auf.

### Daten & Methodik
#### **Datenquellen**
- **OECD-Paneldaten** zu 18 OECD-Ländern von 2005–2022 (Arbeitslosenquoten, ICT-Investitionen, BIP, Gewerkschaftsdichte)

## Projektstruktur
### **R-Codebook** (`R/codebook.R`)
- Enthält alle relevanten Datenverarbeitungsschritte
- Definition der Variablen und Transformationen
- Beschreibung der Datenquellen
- Speichern und Laden der bereinigten Daten
- Durchführung der statistischen Analysen

### **Datensätze** (`R/data`)
- Enthält alle in der Analyse genutzen Datensätze
- Die Datensätze enthalten ungefilterte Rohdaten
- Die Filterung überfolgt durch den Code im R-Codebook

## Anforderungen
### Genutzte Technologien
- [R programing language](https://www.r-project.org/)
    - Für die Paneldatenanalyse wurde die Programmiersprache "R" genutzt.
    - **Erforderliche R-Pakete:** `ggplot2`, `plm`, `dplyr`, `modelsummary`, `knitr`, `kableExtra`
- [RStudio](https://posit.co/download/rstudio-desktop/)
    - RStudio wurde als interaktive Entwicklerumgebung für R genutzt.
### Installation/Reproduzierung
1. Repository klonen/herunterladen und entpacken.
2. Die Datei `R/Data.Rproj` ausführen um das Projekt in RStudio zu öffnen.
3. `R/codebook.R` in RStudio ausführen.