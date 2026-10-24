# Tarea-1-PNL

## Dependencias

Instala las dependencias de Python desde esta carpeta:

```bash
python -m pip install -r requirements.txt
```

La sección zero-shot usa Ollama localmente y no requiere un paquete de Python adicional. Instala Ollama, descarga el modelo configurado en el notebook (`ollama pull llama3.1:8b`) e inicia el servicio antes de activar esa celda. Para usar otro modelo, cambia `MODELO_OLLAMA` en el notebook por el tag instalado.