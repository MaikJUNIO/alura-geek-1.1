

AluraGeek es una aplicación web diseñada para pequeñas y medianas empresas, emprendedores o particulares que desean gestionar y exhibir sus productos en línea de manera eficiente. La plataforma ofrece una interfaz moderna, intuitiva y totalmente personalizable, permitiendo a los usuarios interactuar con un catálogo digital de productos.



_________________________________________________________________________________________________________________
Características:

Con esta aplicacion usted podrá

1- Visualizar Productos : Los productos se cargan automáticamente desde el servidor simulado al abrir la página.

<img width="1847" height="925" alt="image" src="https://github.com/user-attachments/assets/0344f194-3df0-49a1-8db1-67f2345bca7d" />

2- Agregar Producto : Completa el formulario con nombre, precio y URL de la imagen, luego haz clic en "Enviar" .

<img width="668" height="843" alt="image" src="https://github.com/user-attachments/assets/3fbfc6ed-d415-421e-8870-705822b8844a" />
<img width="535" height="520" alt="image" src="https://github.com/user-attachments/assets/2f5e705b-4a3b-47d8-8010-17024cab7c9b" />

3- Eliminar Producto : Haga clic en el ícono de la papelera para eliminar un producto.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/15507674-455c-419a-bffd-464370638f8f" />


4- Buscar productos, mediante palabra clave


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b1a147df-8982-4e3d-9b1c-f818a2f350f7" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/84dfe8f0-d799-48ad-bff8-dfab03b056a8" />




_________________________________________________________________________________________________________________


## **💻 Tecnologías utilizadas**

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> 
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript%20-%23F7DF1E.svg?style=plastic&logo=javascript&logoColor=black">
</a> 
&emsp; 
<a href="https://www.w3.org/html/" target="_blank"> 
  <img alt="HTML" src="https://img.shields.io/badge/HTML5%20-%23E34F26.svg?style=plastic&logo=html5&logoColor=white">
</a>   
&emsp;
<a href="https://www.w3schools.com/css/" target="_blank">
  <img alt="CSS" src="https://img.shields.io/badge/CSS%20-%231572B6.svg?style=plastic&logo=css3&logoColor=white">
</a>  
&emsp;
<a href="https://nodejs.org/" target="_blank"> 
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js%20-%2343853D.svg?style=plastic&logo=node.js&logoColor=white">
</a>
&emsp;
<a href="https://github.com/typicode/json-server" target="_blank"> 
  <img alt="JSON Server" src="https://img.shields.io/badge/json--server%20-%230A0A0A.svg?style=plastic&logo=json&logoColor=white">
</a>
&emsp;
<a href="https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API" target="_blank"> 
  <img alt="Fetch API" src="https://img.shields.io/badge/Fetch%20API%20-%23FF8800.svg?style=plastic&logo=javascript&logoColor=white">
</a>
&emsp;
<a href="https://code.visualstudio.com/" target="_blank"> 
  <img alt="Visual Studio Code" src="https://img.shields.io/badge/VS%20Code%20-%23007ACC.svg?style=plastic&logo=visual-studio-code&logoColor=white">
</a>
&emsp;
<a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer" target="_blank"> 
  <img alt="Live Server" src="https://img.shields.io/badge/Live%20Server%20-%23F05032.svg?style=plastic&logo=visual-studio-code&logoColor=white">
</a>
&emsp;
<a href="https://openai.com/chatgpt" target="_blank"> 
  <img alt="ChatGPT" src="https://img.shields.io/badge/ChatGPT%20-%2366CCFF.svg?style=plastic&logo=openai&logoColor=white">
</a>

 




_________________________________________________________________________________________________________________

## **💻 Etructura**

```perl
ALURAGEEK-CHARLOTTE/
│
├── css/                          # Archivos de estilos CSS
│   ├── estilos.css               # Hoja de estilos principal
│   └── reset.css                 # Reseteo de estilos para normalizar
│
├── img/                          # Imágenes utilizadas en el proyecto
│   ├── encabezado/               # Imágenes para el encabezado
│   │   ├── Corazon.png
│   │   └── search.png
│   ├── descarga.jfif
│   ├── favicon.ico               # Ícono principal del sitio web
│   ├── Ganchito.png
│   ├── logo.png                  # Logo del sitio web
│   ├── papelera.png
│   ├── shortcut icon.jfif
│   ├── shortcut-icon.jfif
│   └── upload.png
│
├── js/                           # Archivos JavaScript
│   ├── buscarProducto.js         # Funcionalidad para buscar productos
│   ├── conexionJsonServer.js     # Conexión al servidor JSON
│   ├── editarProductos.js        # Edición de productos existentes
│   ├── mostrarProductos.js       # Mostrar la lista de productos
│   └── nuevoProducto.js          # Añadir nuevos productos
│
├── pages/                        # Páginas HTML adicionales
│   └── envio-concluido.html      # Página de confirmación de envío
│
├── db copy.json                  # Copia de base de datos JSON
├── db.json                       # Base de datos principal
├── index.html                    # Página principal del proyecto
├── node_modules/                 # Módulos de Node.js instalados
├── package-lock.json             # Archivo de bloqueo para dependencias
├── package.json                  # Configuración de dependencias y scripts
└── README.md                     # Documentación del proyecto
```


____________________________________________________________________________________________________________________________


⚠️ Consideraciones generales del proyecto

1. **Configuración inicial**  
   - Asegúrate de tener **Node.js** instalado en tu sistema.  
   - Instala las dependencias necesarias ejecutando el siguiente comando:  
     ```bash
     npm install
     ```

2. **Servidor JSON**  
   - Para simular una base de datos, este proyecto utiliza **json-server**.
     ```bash
     npm install -g json-server
     ```
   - Inicia el servidor con el siguiente comando:  
     ```bash
     json-server --watch db.json
     ```
   - El servidor se ejecutará en `http://localhost:3002`.
     ```bash
     npx json-server --watch db.json --port 3002
     ```

3. **Estructura del proyecto**  
   - El código está dividido en carpetas organizadas por funcionalidad:  
     - **CSS**: Estilos para el diseño visual.  
     - **JS**: Archivos JavaScript con lógica del proyecto.  
     - **IMG**: Recursos gráficos e imágenes.  
     - **Pages**: Páginas adicionales como confirmaciones de envío.

4. **Funcionalidades principales**  
   - Buscar productos.  
   - Mostrar la lista de productos disponibles.  
   - Editar productos existentes.  
   - Agregar nuevos productos al sistema.  
   - Confirmar envíos de productos.

5. **Recomendaciones**  
   - Utiliza **Live Server** en VS Code para visualizar los cambios en tiempo real.  
   - Asegúrate de que el servidor JSON esté corriendo antes de interactuar con las funcionalidades del proyecto.  
   - Valida los datos ingresados para evitar errores en la base de datos.



