# Volatility 3 - Discord Conversation Viewer

Visualizador de conversaciones de Discord para análisis forense de memoria con Volatility 3.

## 📋 Descripción

Esta herramienta permite visualizar de forma legible las conversaciones de Discord extraídas de volcados de memoria mediante Volatility 3. El script toma un archivo JSON con los mensajes y los muestra en una interfaz web tipo chat.

## 🚀 Uso rápido

### 1. Extraer mensajes con Volatility 3

```bash
sudo vol -f memoria.dmp windows.discord.Discord > mensajes.json
