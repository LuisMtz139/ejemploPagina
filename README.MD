# Prueba 
1.- crear el proyecto

2.- cambiar el mombre generado al crear el build por docs

3.- configurar vite.config.js para poder tomar los datos de docs



## Pasos de vite.config.js

```javascript
import {defineConfig} from 'vite';
export default defineConfig({
    base: '/ejemploPagina/'
})
