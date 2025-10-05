# repositorio-2
#API REST de Productos con Node.js

Una API sencilla para manejar un inventario de productos. Permite listar, agregar, editar y eliminar productos.

### ✨ Características
- Endpoint para listar productos.
- Endpoint para agregar un producto nuevo.
- Endpoint para actualizar datos.
- Endpoint para eliminar productos.

### 📚 Tecnologías utilizadas
- Node.js
- Express.js
- JSON como base de datos simulada

### ⚙️ Instrucciones de uso
1. Clona el repositorio.
2. Instala dependencias:
   ```bash
   npm install
Inicia el servidor:

bash
Copiar código
npm start
Prueba con Postman o navegador:

GET http://localhost:3000/products

POST http://localhost:3000/products

Funcionamiento del código
El servidor usa Express.js para crear endpoints REST. Los productos se almacenan en un archivo JSON y se manipulan con funciones de lectura/escritura.

yaml
Copiar código
