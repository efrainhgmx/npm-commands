#  Comandos de NPM 

JavaScript es un lenguaje que fue diseñado para dar interactividad a la web, del lado del cliente **(Frontend)**  y este mismo se ha podido usar del lado del servidor gracias **Node.js** el cual es un entorno de ejecución del lado del servidor.

Para poder trabajar con Node, es necesario ir implementando modulos según nuestro proyecto lo requiera, es ahí donde entra **npm**.

## ¿Qué es NPM?

**Node Package Manager** es un gestor de manejo de paquetes escritos en JavaScript lo cual **npm** nos permite obtener cualquier librería de JS con una sola linea de código en nuestro entorno de trabajo. 

Aquí los comando que necesitas saber para manejar **npm** como un experto.

### Comandos Básicos

`$ npm init` // Nos permite inciar un npm en nuestro proyecto y crea un package.json con los datos del proyecto.

`$ npm init -y` // Crea un package.json con los datos vacios o los configurados por el usuario dentro del proyecto.

`$ npm set init.author.email "me@email.com"` // Deja configurado.

`$ npm set init.author.name "Tu nombre"` // Guarda el nombre del autor para futuros proyectos.

`$ npm set init.license "MIT"` //Guarda la configuración de licencias predeterminada para todos los proyectos.

### Instalación de dependencias.

Las dependencias deben ser instaladas en la carpeta raíz del proyecto.

`$ npm i package `,
`$ npm install package` // Instalan la dependencia.

`$ npm install package -D` // Instala solo lo necesario para un entorno de desarrollo. Es decir, no irá a producción.

`$ npm install package -g` // Instala una dependencia de forma globa. Esto permite que podamos utilizar este paquete en diferentes proyectos. Por lo general debe instalarse con permisos de administrador.

`$ npm list -g --depth 0` // Muestra los paquetes que están instalados de forma global.

`$ npm list` // Muestra los paquétes que tiene el proyecto.

`$ npm install package -O` // Podemos instalar de forma opcional un paquete con este comando.

`$ npm install package --dry-run` // No instala el paquete, solo es para simulación y muestra el output como si estuviese instalado.

`$ npm install package -f` // Instala un paquete forzando la instalación.

`$ npm install package@<version>` // Instala la dependencia en una versión en especifico.

`$ npm install npm@latest`  // Actualiza la dependencia a la ultima versión disponible.
