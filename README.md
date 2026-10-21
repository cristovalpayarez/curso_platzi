🎮 Mokepon
¡Bienvenido a Mokepon! 🐾

Mokepon es un pequeño videojuego web desarrollado como proyecto de práctica de programación básica. El jugador elige una mascota, recorre un mapa usando los controles y puede enfrentarse a otros jugadores conectados al servidor.
✨ Características
- 🐲 Selección de Mokepon: Hipodoge, Capipepo o Ratigueya.
- 🗺️ Mapa interactivo dibujado con HTML Canvas.
- 🎮 Movimiento mediante las teclas de dirección.
- 🌐 Servidor creado con Node.js y Express.
- 🔄 Envío de posiciones y datos de jugadores entre clientes.
- ⚔️ Sistema básico de ataques y resultados de combate.
ℹ️ La sincronización depende de que el servidor esté ejecutándose y de que los archivos del proyecto estén configurados correctamente.

🧰 Tecnologías utilizadas
- HTML para la estructura de la página.
- CSS para los estilos.
- JavaScript para la lógica del juego.
- Node.js para ejecutar el servidor.
- Express para crear las rutas del servidor.
- CORS para permitir las peticiones desde el cliente.
📁 Estructura del proyecto
mokepon/
├── mokepon.html       # Página principal del juego
├── mokepon.css        # Estilos de la interfaz
├── mokepon.js         # Lógica del juego y movimiento
├── index.js           # Servidor Express
└── assets/            # Imágenes del mapa y de los Mokepon
Los nombres de archivos y carpetas pueden variar según tu proyecto.
🚀 Cómo ejecutar el proyecto
1. Requisitos
Instala Node.js y asegúrate de tener los archivos del proyecto, incluida la carpeta assets.
2. Instalar dependencias
Abre una terminal en la carpeta donde está index.js y ejecuta:
npm init -y
npm install express cors
Si ya existe un archivo package.json, normalmente basta con ejecutar:
npm install
3. Iniciar el servidor
En la terminal, ejecuta:
node index.js
Deberías ver un mensaje similar a:
Servidor funcionando en http://localhost:8080
Mantén esa terminal abierta mientras juegas.
4. Abrir el juego
Abre mokepon.html con tu servidor de desarrollo local, por ejemplo, Live Server en Visual Studio Code. El cliente espera que el servidor de Node.js esté disponible en http://localhost:8080.

Para probar la comunicación entre jugadores, abre el juego en dos pestañas o ventanas del navegador.
🎮 Cómo jugar
1. Abre el juego en el navegador.
2. Selecciona un Mokepon.
3. Usa las teclas ⬆️ Arriba, ⬇️ Abajo, ⬅️ Izquierda y ➡️ Derecha para moverte.
4. Con el servidor encendido, prueba la conexión con otra pestaña del juego.
5. Si se produce un error, abre las herramientas de desarrollador del navegador y revisa la pestaña Console.
🧠 Qué practiqué con este proyecto
- Variables, funciones, clases y objetos en JavaScript.
- Eventos del teclado y botones.
- Dibujo de imágenes en HTML Canvas.
- Peticiones HTTP con fetch.
- Creación de rutas GET y POST con Express.
- Envío y recepción de datos JSON.
- Comunicación básica entre el frontend y el backend.
🎓 Certificado de Programación Básica
Puedes consultar el enlace que compartí relacionado con el certificado de Programación Básica de Platzi:

🔗 Certificado / https://platzi.com/p/cristovalpayares/curso/3208-course/diploma/detalle/