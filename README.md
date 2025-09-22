# Despliegue en Render

Esta landing page está lista para alojarse como un **Static Site** en [Render](https://render.com/).

## Requisitos

- Una cuenta en Render.
- Acceso a este repositorio (o un fork) con el archivo `index.html` en la raíz.

## Instrucciones rápidas

1. Inicia sesión en Render y ve a **New > Static Site**.
2. Conecta tu repositorio y selecciona la rama `work`.
3. Render detectará el tipo de servicio como "Static Site".
4. Configura los siguientes valores:
   - **Build Command**: dejar vacío (no es necesaria una construcción).
   - **Publish directory**: `.`
5. Haz clic en **Create Static Site** y espera a que finalice el despliegue.

> También puedes crear el servicio automáticamente con el archivo [`render.yaml`](./render.yaml).

## Variables de entorno opcionales

No se requieren variables de entorno. Puedes añadir las que necesites para personalizar metadatos o integraciones futuras.

## Actualizaciones

Cada commit que llegue a la rama configurada disparará un nuevo despliegue automático en Render.
