# Web Scraper Flask - asuanez.inscastellbisbal.net

Aquest projecte és una API basada en Flask que fa scraping de la pàgina **asuanez.inscastellbisbal.net**, processant el contingut de forma recursiva. La informació obtinguda es pot fer servir amb un model d'IA (Gemini) que només respon amb dades de la web esmentada.

## ✨ Funcionalitats

- Extracció de text dels paràgrafs i títols de la web
- Navegació per enllaços interns fins a una profunditat màxima definida
- Exposició del servidor local amb **ngrok**
- Respostes basades exclusivament en el contingut extret
- Configurat amb suport CORS per facilitar connexions externes

## ⚙️ Requisits

- Python 3.7+
- `Flask`, `requests`, `beautifulsoup4`, `pyngrok`, `flask_cors`, `google.generativeai`

## 🔐 Configuració

Abans d'executar, assegura't de definir:

- `GOOGLE_API_KEY` → Clau d’API de Google Gemini
- `NGROK_AUTHTOKEN` → Token de ngrok

