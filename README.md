<h1 align="center"> Generación y Configuración de la API Key de Gemini</h1>

## 1️ Generar la API Key  

Sigue estos pasos para obtener tu clave de API de Gemini:

<p align="center">
  <strong>Paso 1: Acceder a la página de la API</strong>  
</p>
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/9281/9281989.png" alt="Acceder a la API" width="100">
</p>

1. Accede al siguiente enlace: <a href="https://aistudio.google.com/app/u/1/apikey?hl=es-419" target="_blank">aistudio</a>
2. Haz clic en **"Get API Key"**.
3. Acepta los términos y condiciones del servicio.

<p align="center">
  <strong>Paso 2: Crear la clave API</strong>  
</p>
<p align="center">
  <img src="https://i.pinimg.com/originals/f2/77/52/f2775237261c8101f85c980075c13db7.gif" width="100">
</p>

4. Pulsa en **"Crear clave API"**.
5. Selecciona **Gemini** como servicio.
6. Copia la clave generada y guárdala en un lugar seguro.

---

## 2️⃣ Configurar la API Key en el Proyecto  

Para utilizar la API en tu proyecto, es recomendable colocar la clave en un archivo de entorno seguro, pero en este caso la clave ha sido colocada directamente en main.js porque este proyecto no está destinado a producción :

### 🔹 En main.js  
Agrega la clave:  
```js
// API Setup
// API Configuración
const API_KEY = ""; 
