# Liebherr Hackathon 2025 – Produktionsplanung mit Data Science

**Vorhersage realistischer Fertigstellungstermine in der Fertigung**

---

## 🎯 Projektbeschreibung

Im Rahmen des **Liebherr Hackathon 2025** haben wir ein Machine-Learning-Modell entwickelt, das **Terminverzüge in der Produktion** frühzeitig erkennt und für laufende Fertigungsaufträge einen **realistischen Fertigstellungstermin** prognostiziert.

Liebherr beobachtet seit mehreren Jahren vermehrt Terminverzüge durch:
- Ungeplante Nacharbeiten und Abweichungen vom Standardarbeitsplan
- Voll ausgelastete Maschinen und maschinenabhängige Bearbeitungsdauern
- Besonders schleppenden Start in der Woche (Montagseffekt)

Ziel war es, die bestehende Planung durch moderne Data-Science-Methoden deutlich zu verbessern.

## 📊 Die Aufgabe

Entwicklung eines Modells, das auf Basis eines umfangreichen Datensatzes (ca. 1,6 Millionen Einträge) mit Produktionsparametern und zeitlichen Abläufen den voraussichtlichen Fertigstellungstermin eines Auftrags möglichst genau vorhersagt.

Wir durften frei wählen zwischen klassischen statistischen Verfahren und modernen Ansätzen aus Machine Learning oder Deep Learning.

## 🛠️ Unser Ansatz

- **Datenexploration** & Feature Engineering basierend auf den identifizierten Problembereichen (Nacharbeit, Maschinentyp, Wochentag, Auslastung etc.)
- Erstellung neuer, aussagekräftiger Features
- Training und Vergleich verschiedener Modelle
- Evaluierung mit produktionsrelevanten Metriken (z. B. Mean Absolute Error in Tagen/Stunden, Vorhersagegenauigkeit innerhalb bestimmter Toleranzfenster)

## 🚀 Wie man das Projekt startet

```bash
# 1. Repository klonen
git clone https://github.com/hakanderbarbar/Hackathon_Liebherr_DataScience2025.git

# 2. Ins Verzeichnis wechseln
cd Hackathon_Liebherr_DataScience2025/rwu_hackatron_2025

# 3. Virtuelle Umgebung erstellen & aktivieren (optional)
python -m venv venv
source venv/bin/activate    # Linux / macOS

# 4. Abhängigkeiten installieren
pip install -r requirements.txt

# 5. Notebooks starten
jupyter lab
