# Plataforma-multimodal-de-IA

# Trabajo Final - Sistemas Inteligentes

Este proyecto es un trabajo grupal para la asignatura de Sistemas Inteligentes (Universidad San Jorge). Consiste en el desarrollo de un chatbot multimodal capaz de interactuar mediante texto, voz e imágenes, utilizando modelos de última generación en IA.

## Características principales

- **Chatbot basado en Llama 3.2-1B-Instruct**: Generación de texto inteligente usando modelos de lenguaje de última generación.
- **Reconocimiento de objetos en imágenes**: Utiliza YOLOv5 para detectar y nombrar objetos en imágenes subidas por el usuario.
- **Text-to-Speech (TTS)**: Convierte las respuestas generadas en audio usando SpeechT5.
- **Reconocimiento de voz**: Transcribe audios a texto usando Whisper.
- **Interfaz interactiva con Gradio**: Permite la interacción sencilla con el sistema desde el navegador.

## Requisitos

- Python 3.9+
- GPU recomendada para acelerar el procesamiento
- Cuenta en [HuggingFace](https://huggingface.co/) y acceso a los modelos utilizados

## Ejecución

Todo el código y las instrucciones están incluidas en el notebook `TrabajoFinal_IA_F.ipynb`.  
Simplemente abre el notebook Jupyter en VSCode y ejecuta las celdas en orden.  
No es necesario instalar dependencias manualmente en la terminal, ya que las celdas de instalación están incluidas al inicio del notebook.

## Uso en Google Colab

**Importante:** Si ejecutas este proyecto en Google Colab, ten en cuenta que los modelos utilizados (por ejemplo, Llama 3.2-1B-Instruct y Whisper-large) pueden exceder la memoria disponible en la versión gratuita de Colab.  
En ese caso, se recomienda utilizar versiones más ligeras de los modelos, o quitar algun modelo.
Modifica las líneas de carga de modelos en el notebook según la disponibilidad y tus necesidades.

## Estructura del proyecto

- `TrabajoFinal_IA.ipynb`: Notebook principal con todo el código y las instrucciones.
- Modelos utilizados:
  - Llama 3.2-1B-Instruct (texto)
  - YOLOv5 (detección de objetos)
  - SpeechT5 (TTS)
  - Whisper (ASR)
- Interfaz Gradio para interacción multimodal.

## Créditos

- HuggingFace y autores de los modelos utilizados
- Equipo de desarrollo del trabajo final: [@LilSamu](https://github.com/LilSamu), [@Javier](), [@jrgim](https://github.com/jrgim)

---

¡Esperamos que disfrutes probando el chatbot!
