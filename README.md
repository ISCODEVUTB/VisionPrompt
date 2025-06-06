# 📸 Busca con tus palabras

**Busca con tus palabras** es una aplicación web que permite realizar búsquedas de imágenes a partir de descripciones escritas en lenguaje natural, utilizando el poder de modelos multimodales como CLIP (Contrastive Language–Image Pretraining) de OpenAI.

<p align="center">
  <img src="images/app_screenshot.png" alt="App Screenshot" width="600"/>
</p>

## 🚀 Características

- 🔍 Búsqueda intuitiva de imágenes mediante texto libre
- 🧠 Basado en aprendizaje cero ("zero-shot") con el modelo CLIP
- 🖼️ Soporte para carga de imágenes individuales o por lote
- 🧮 Cálculo de similitud semántica entre texto e imagen
- 📊 Interfaz visual con resultados ordenados por relevancia
- ☁️ Implementado con Streamlit y desplegado en Streamlit Cloud

## 🛠️ Tecnologías usadas

- **Lenguaje**: Python 3.9
- **Frontend**: Streamlit
- **Backend**: PyTorch, CLIP
- **Librerías**:
  - `clip` (implementación oficial de OpenAI)
  - `PIL` (procesamiento de imágenes)
  - `scikit-learn` (similitud coseno)
  - `numpy` (operaciones vectoriales)

## 📦 Instalación local

1. Clona el repositorio:

```bash
git clone [https://github.com/equipo-busca-imagenes/clip-search.git](https://github.com/ISCODEVUTB/VisionPrompt)
cd clip-search
