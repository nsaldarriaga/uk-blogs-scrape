# 🇬🇧 UK Blogs Scraper

Este proyecto es un scraper automatizado que extrae información del sitio oficial del gobierno del Reino Unido: [blog.gov.uk](https://www.blog.gov.uk/).

---

## 📌 ¿Qué hace?

- Recolecta datos de los artículos publicados en el blog.
- Extrae:
  - Título del artículo
  - Autor
  - Categorías
  - Descripción
- Agrupa los artículos por semana de publicación.
- Guarda la información en un archivo `.json`.

---

## ⚙️ Automatización

El scraping se ejecuta automáticamente utilizando **GitHub Actions**, lo que permite mantener el dataset actualizado sin intervención manual.

---

## 🛠️ Tecnologías utilizadas

- `Python`
- `Requests`
- `BeautifulSoup`
- `GitHub Actions` (para la automatización)

---

## 🚀 Cómo ejecutarlo localmente

---

1. Cloná el repositorio:

git clone https://github.com/nsaldarriaga/uk-blogs-scrape.git
cd uk-blogs-scrape

2. Creá el entorno virtual:

python -m venv .venv
.venv\Scripts\activate   # En Windows

3. Instalá las dependencias:
pip install -r requirements.txt

4.Ejecutá el script:
python scrape.py

---

## 📂 Estructura del archivo .json

El archivo contiene una estructura como la siguiente:

{
  "2024-03-25": [
    {
      "title": "Ejemplo de título",
      "author": "Nombre del autor",
      "categories": ["Categoría1", "Categoría2"],
      "description": "Primer párrafo del artículo..."
    }
  ]
}

---

## 🤝 Contribuciones

Este proyecto es de código abierto. Se aceptan sugerencias, mejoras y pull requests.

---

## 📝 Licencia

Este repositorio se publica con fines educativos.

---
