# Nutri-IA Frontend

Interfaz web de Nutri-IA. Se despliega gratis en Vercel.

## Antes de desplegar

Abre `index.html` y busca esta línea cerca del final:

```js


const BACKEND_URL = 'https://nutria-backend-xxxx.onrender.com';


```

Cámbiala por la URL real que te dio Render al desplegar el backend. Ejemplo:

```js
const BACKEND_URL = 'https://nutria-backend-xyz.onrender.com';
```

## Deploy en Vercel (gratis)

1. Sube esta carpeta a un repositorio en GitHub
2. Ve a https://vercel.com y crea una cuenta gratuita (puedes entrar con GitHub)
3. Haz clic en "Add New Project"
4. Selecciona tu repositorio de nutria-frontend
5. Deja toda la configuración por defecto
6. Haz clic en "Deploy"

Vercel te dará una URL como: `https://nutria-ia.vercel.app`

¡Esa URL ya funciona desde cualquier celular o computadora!

## Estructura del proyecto

```
nutria-frontend/
└── index.html    ← toda la aplicación en un solo archivo
```
