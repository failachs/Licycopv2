Despliegue en Vercel

Contenido:
- index.html  -> archivo principal de la aplicación
- vercel.json -> configuración mínima para despliegue estático

Cómo subir:
1. Entra a Vercel
2. Add New Project
3. Arrastra esta carpeta o este zip
4. Framework Preset: Other
5. Deploy

Nota:
- El archivo usa USE_MOCK_AI = true, por lo que la interfaz puede desplegarse sin backend.
- Si luego quieres que /api/interpretar-turno funcione de verdad, debes agregar una función serverless en /api.
