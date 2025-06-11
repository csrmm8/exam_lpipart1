# Examen tipo test LPIC-1 con corrección por IA

Esta aplicación permite practicar preguntas tipo test y obtener corrección y explicación automática usando ChatGPT (OpenAI).

## Instalación

1. Clona el repositorio y entra en la carpeta.
2. Instala dependencias:
    ```
    pip install -r requirements.txt
    ```
3. Configura tu clave de OpenAI:
    - Puedes ponerla en los [secrets de Streamlit](https://docs.streamlit.io/streamlit-community-cloud/deploy-your-app/secrets-management) o como variable de entorno:
    ```
    export OPENAI_API_KEY=tu_clave_aqui
    ```

## Uso

1. Ejecuta la aplicación:
    ```
    streamlit run app.py
    ```
2. Responde las preguntas y presiona "Corregir con IA".
3. La IA te indicará si tus respuestas son correctas, dará la respuesta correcta y explicaciones.

---

## Personalización

- Puedes modificar o añadir preguntas en el array `questions` de `app.py`.
- Para más preguntas, se recomienda cargarlas desde un archivo `.json`.

---

## Notas

- Necesitas una cuenta de OpenAI y una clave API válida.
- El modelo por defecto es `gpt-3.5-turbo`. Puedes cambiarlo a `gpt-4` si tienes acceso.
