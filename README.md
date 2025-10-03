# miniChatwhitOpenAI# 💬 Mini Chat con OpenAI en TypeScript

Este proyecto es una mini práctica en **Node.js** y **TypeScript** que implementa un chat en consola utilizando la **API de OpenAI**.  
Permite enviar mensajes de texto y recibir respuestas de un modelo de IA como `gpt-4o-mini` o `gpt-3.5-turbo`.

---

## 📌 Requisitos previos

- **Node.js** >= 18  
- Una **API Key de OpenAI** (obtenla en [OpenAI Platform](https://platform.openai.com/))  
- **npm** o **yarn** como gestor de paquetes  

---

## 📂 Instalación

1. Clona este repositorio:

git clone https://github.com/tuusuario/minichat-openai-ts.git
cd minichat-openai-ts

2. Instala dependencias:
npm install
3. Crea un archivo .env en la raíz del proyecto con tu clave:
OPENAI_API_KEY=tu_api_key_aqui

## Uso
npm run dev

## Ejemplo de ejecución
 Mini práctica IA con TypeScript
Escribe 'salir' para terminar.

Tú: Hola, ¿qué puedes hacer?
IA: ¡Hola! Soy un modelo de lenguaje de OpenAI. Puedo responder preguntas, ayudarte a programar o simplemente conversar contigo.
Para salir, escribe:
Tú: salir
👋 ¡Hasta luego!

## Notas:
El modelo por defecto es gpt-4o-mini, pero puedes cambiarlo por gpt-3.5-turbo u otro en el código.
Asegúrate de que tu API Key de OpenAI tenga créditos o suscripción activa.