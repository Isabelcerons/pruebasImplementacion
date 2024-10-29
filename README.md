# Bienvenidos al Repositorio
## Distri-Rivera


# 1. Título del Proyecto
Distri-Rivera: Sistema de Inventario para Tiendas  

# 2. Descripción
Distri-Rivera es un sistema de gestión de inventario diseñado específicamente para tiendas minoristas. Este software permite a los usuarios llevar un control eficiente de sus productos, gestionar entradas y salidas de stock, y generar reportes de ventas. 


# 3. Instalación
## Requisitos Previos
Antes de comenzar, asegúrate de tener instalados los siguientes componentes:
- Node.js (versión 14 o superior)

 Editor de codigo: en este Caso **Visual Studio Code**

### Pasos de Instalación
Sigue estos pasos para instalar y configurar Distri-Rivera:

1. ***Clona el repositorio:***
    abrimos desde la terminal en  la carpeta que vamos a clonar el respositorio le damos  en git bash seguido de esto inciamos el repositorio con
   
        'git init'
   
   , luego el comando
   
    'git clone https://github.com/dev-Alejo24/proyect_impleSoftware.git'
   
   y pegamos la direccion de nuestro repositorio 
   
2. ***Navega al directorio del proyecto***:
   abrimos nuevamente el git bash desde la carpeta donde clonamos el respositorio y le damos el comando
   
      'code .'
   
   y este nos abre nuestro proyecto directamente con visual code
   
3. ***Instala las dependencias***:

  nos dirigimos al archivo **package.json** y abrimos la terminal y le colocamos el comando

    'npm install'
   
4. ***Configura la ejecucion del proyecto***: 

   - Crea un archivo **"start": "vite"**,en la parte baja del archivo script  del archivo package.json
   
5. ***Inicia el servidor***:

   nos dirijimos a cualquier arichvo y le colocamos el comando

    'npm start'

Ahora tu sistema de inventario debería estar funcionando en http://localhost:5173/

# 4. TEST
## Librerias
Desde la terminal de nuestro editor en la ruta de la carpeta del proyecto implementamos los siguientes comandos para usar las librerias:

1. La libreria principal es [Vitest](https://vitest.dev/) la cual es proporcionada por los creadores de [Vite](https://vite.dev/)

   'npm install -D vitest'
   
2. Usamos [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)

   'npm install --save-dev @testing-library/react @testing-library/dom'

Despues de la correcta instalacion de las librerias para testing, en el archivo **package.json** en la parte baja de **scripts** implementamos la siguiente linea:
   '"test":"vitest"'
   
Lo anterios es para correr las pruebas con el siguiente comando desde la terminal del editos de codigo:
    'npm test'

# 5. Contribución
Si deseas contribuir a Distri-Rivera, aquí tienes algunas pautas:

1. *Forkea el repositorio* y crea tu rama de características (git checkout -b feature/nuevaCaracteristica).
2. *Realiza tus cambios* y asegúrate de que todo funciona correctamente.

3. *Haz un commit de tus cambios* (git commit -m 'Añadir nueva característica').

4. *Sube tus cambios* a tu repositorio (git push origin feature/nuevaCaracteristica).
