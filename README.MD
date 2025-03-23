# 📌 Proyecto C: Conversor de Monedas

## 📖 Descripción
Este proyecto es un conversor de monedas desarrollado en el lenguaje de programación **C**. Permite realizar conversiones entre **Quetzales (GTQ), Dólares Estadounidenses (USD) y Euros (EUR)** mediante un menú interactivo en la terminal.

## 🛠 Prerrequisitos
Antes de ejecutar este proyecto, asegúrate de tener instalado **Apache2** y **Git** en tu sistema Ubuntu. Para instalarlos, ejecuta los siguientes comandos en la terminal:

```sh
sudo apt update
sudo apt install apache2 git -y
```

También necesitas tener instalado **GCC (GNU Compiler Collection)** para compilar programas en C:

```sh
sudo apt install gcc -y
```

## 🚀 Pasos para la Ejecución
1. **Clonar el repositorio**:
   ```sh
   git clone https://github.com/tu-usuario/conversor-monedas-c.git
   cd conversor-monedas-c
   ```
2. **Compilar el código**:
   ```sh
   gcc conversor.c -o conversor
   ```
3. **Ejecutar el programa**:
   ```sh
   ./conversor
   ```

---

# 📌 Proyecto PHP: Página Web "Hola Mundo"

## 📖 Descripción
Este proyecto consiste en una página web simple desarrollada en **PHP**. La página mostrará un mensaje "Hola Mundo" junto con el nombre del autor y una imagen generada con inteligencia artificial.

## 🛠 Prerrequisitos
Antes de ejecutar este proyecto, asegúrate de tener instalado **Apache2** y **PHP** en tu sistema Ubuntu. Puedes instalarlos con los siguientes comandos:

```sh
sudo apt update
sudo apt install apache2 php -y
```

Para verificar que PHP está instalado correctamente, ejecuta:
```sh
php -v
```

## 🚀 Pasos para la Ejecución
1. **Clonar el repositorio**:
   ```sh
   git clone https://github.com/tu-usuario/hola-mundo-php.git
   cd hola-mundo-php
   ```
2. **Copiar los archivos al directorio de Apache**:
   ```sh
   sudo cp -r * /var/www/html/
   ```
3. **Reiniciar Apache**:
   ```sh
   sudo systemctl restart apache2
   ```
4. **Abrir la página en el navegador**:
   ```
   http://localhost/hola-mundo.php
   ```

## ✍️ Datos del Autor
- **Nombre:** Jeremy Flores  
- **Correo:** jeremyflores@example.com  
- **Carnet:** 25001422

