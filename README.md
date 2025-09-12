# Kubera Local AI (Windows) — Ollama + Open WebUI (Docker)

Локальный ИИ на ноутбуке (8 ГБ RAM): бесплатные модели через Ollama, интерфейс — Open WebUI (в Docker).  
Проверено на машине Николая: работает модель gemma:2b.

## Быстрый старт
1) Ollama (Windows):  
- Скачай и установи с https://ollama.com/download  
- Открой PowerShell:
  `powershell
  ollama pull gemma:2b
  net start Ollama
  curl http://localhost:11434/api/tags
