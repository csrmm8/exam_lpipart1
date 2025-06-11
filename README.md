# Exam PDF Interactivo

Este repositorio permite subir un PDF de examen, extraer las preguntas y responderlas desde una interfaz web simple.

## ¿Cómo funciona?

1. Sube un PDF de examen a través de la app web.
2. La app extrae las preguntas del PDF.
3. Responde las preguntas en la misma interfaz.
4. (Opcional) Guarda tus respuestas en un archivo.

## Requisitos

- Python 3.8+
- Instala las dependencias:
  ```
  pip install -r requirements.txt
  ```

## Uso

Ejecuta la aplicación con:
```
streamlit run app.py
```

Luego abre la URL que te indica Streamlit (usualmente http://localhost:8501).

## Estructura

- `app.py`: Código principal de la app.
- `/pdfs/`: Carpeta para almacenar los PDFs subidos.
- `requirements.txt`: Dependencias.
