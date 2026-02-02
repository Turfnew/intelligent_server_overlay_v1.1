# 🚀 Personal Service Hub & Llama3 Turbo

Willkommen bei deinem persönlichen Server-Hub. Dieses System verwandelt deinen Server in eine Schaltzentrale mit KI-Chat (Llama3), News-Aggregator und Projekt-Portfolio, optimiert für die Nutzung auf dem iPhone 11.

---

## 🛠️ Schritt 1: Vorbereitung

Bevor du beginnst, benötigst du:
* Einen Server oder PC mit **Linux** (Debian oder Ubuntu empfohlen).
* Root-Zugriff oder `sudo`-Rechte.
* Eine aktive Internetverbindung (zum Herunterladen der KI-Modelle).

---

## ⚡ Schritt 2: Nutzung des automatischen Setup-Scripts

Das Script `setup.sh` ist das Herzstück der Installation. Es automatisiert die Konfiguration von Apache, Ollama und den Web-Dateien.

### 1. Dateien übertragen
Kopiere alle Dateien (`index.html`, `llama.html`, etc.) und das `setup.sh` in einen Ordner auf deinen Server.

### 2. Script ausführbar machen
Damit Linux das Script starten darf, musst du die Rechte anpassen:
```bash
chmod +x setup.sh
