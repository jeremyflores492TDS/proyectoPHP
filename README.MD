📌 Proyecto PHP: Página Web "Hola Mundo"

📖 Descripción

Este proyecto consiste en una página web simple desarrollada en PHP. La página mostrará un mensaje "Hola Mundo" junto con el nombre del autor y una imagen generada con inteligencia artificial.

🛠 Prerrequisitos

Antes de ejecutar este proyecto, asegúrate de tener instalado Apache2 y PHP en tu sistema Ubuntu. Puedes instalarlos con los siguientes comandos:

sudo apt update
sudo apt install apache2 php -y

Para verificar que PHP está instalado correctamente, ejecuta:

php -v

🚀 Pasos para la Ejecución

Clonar el repositorio:

git clone https://github.com/jeremyflores492TDS/proyectoPHP.git
cd hola-mundo-php

Copiar los archivos al directorio de Apache:

sudo cp -r * /var/www/html/

Reiniciar Apache:

sudo systemctl restart apache2

Abrir la página en el navegador:

http://localhost/hola-mundo.php

✍️ Datos del Autor

Nombre: Jeremy Flores

Correo: 25001422@galileo.edu

Carnet: 25001422

