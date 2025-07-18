# 🧠🔐 Wiki-Escape  
**Ein KI-gestütztes Escape Room Spiel basierend auf Wikipedia-Artikeln**

## ✨ Projektbeschreibung

**Wiki-Escape** ist ein interaktives Escape-Room-Spiel, das den Inhalt eines Wikipedia-Artikels in eine Reihe spannender Rätsel verwandelt. Mithilfe künstlicher Intelligenz werden aus einem Artikel Fragen generiert, die gelöst werden müssen, um aus dem virtuellen Raum zu entkommen.

Das Projekt verbindet Wissensvermittlung mit spielerischem Lernen und fördert Textverständnis, Logik und Allgemeinbildung.

---

## 📁 Projektstruktur

```
📦 Wiki-Escape/
├── main.py                   # Einstiegspunkt des Spiels
├── requirements.txt          # Abhängigkeiten
├── .env                      # Umgebungsvariablen (API Keys etc.)
├── core/                     # Zentrale Logik und KI-Handler
│   ├── ai_handler.py
│   ├── file_handler.py
│   ├── game_engine.py
│   └── wiki_handler.py
├── helper/                   # Spiel-Flow, Kategorien und Hilfsfunktionen
│   ├── ai_prompt.py
│   ├── game_categories.py
│   ├── game_flow.py
│   ├── game_settings.py
│   ├── messages.py
│   └── utility.py
├── data/                     # Assets, Datenbank und Audio
│   ├── WikiEscape.db
│   ├── Settings.json
│   ├── *.wav (Soundeffekte)
```

---

## 🚀 Installation & Ausführung

### Voraussetzungen

- Python 3.11+
- API-Zugang (z. B. OpenAI)

### Setup

```bash
# Repository klonen
git clone https://github.com/dein-nutzername/wiki-escape.git
cd wiki-escape

# Virtuelle Umgebung (optional)
python -m venv venv
source venv/bin/activate  # unter Windows: venv\Scripts\activate

# Abhängigkeiten installieren
pip install -r requirements.txt

# .env Datei mit API-Key anlegen
echo "OPENAI_API_KEY=dein-key-hier" > .env

# Spiel starten
python main.py
```

---

## 🎮 Spielablauf

1. Du gibst ein Thema oder Stichwort für einen Wikipedia-Artikel ein  
2. Die KI analysiert den Artikel und generiert ein thematisch passendes Escape Room Szenario  
3. Du wirst durch Fragen geleitet, die du lösen musst  
4. Beantworte alle Fragen korrekt, um zu „entkommen“  
5. Bei falschen Antworten gibt es Hinweise, Sounds oder sogar virtuelle „Strafen“

---

## 🔊 Audio

Das Spiel enthält mehrere **8-Bit-Soundeffekte** für ein retro-inspiriertes Spielerlebnis. Diese befinden sich im `data/` Ordner.

---

## 🛠️ Verwendete Technologien

- **Python 3.11**
- **OpenAI API** (für Fragegenerierung)
- **Wikipedia API**
- **SQLite** (lokale Speicherung von Spielständen oder Einstellungen)
- **Custom Game Framework** (eigene Spiel-Engine mit modularem Aufbau)

---

## 💡 Geplante Features

- GUI-Version (Tkinter oder Pygame)
- Mehrsprachigkeit
- Multiplayer-Optionen
- Artikelvorschläge und Fortschrittsverfolgung

---

## 📜 Lizenz

Dieses Projekt steht unter der [MIT License](LICENSE).

---

## 🙌 Mitwirken

Pull Requests, Ideen und Vorschläge sind herzlich willkommen!

---

**Let’s escape with knowledge. 🔓📚**
