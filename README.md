## 🛠️ Tecnologías Actualizadas
- **Modelo Base**: [DeepSeek-R1](https://huggingface.co/deepseek-ai/DeepSeek-R1) (236B parámetros)
- **Ajuste Fino**: Usando LoRA en 4-bit (optimizado para GPU T4)
- **Dataset**: 36 diálogos terapéuticos originales en español
- **Formato de Prompt**: Adaptado al esquema `<|im_start|>` de DeepSeek

## 🌟 Características Técnicas
```python
# Esquema de prompt especial para DeepSeek
"<|im_start|>user\n{pregunta}<|im_end|>\n<|im_start|>assistant\n{respuesta}<|im_end|>"
