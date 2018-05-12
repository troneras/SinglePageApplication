    ### Paso 8
    Añadir el framework css Bulma
    Añadir componentes y clases al proyecto, crear nuevos ficheros blade
    para separar el header del layout, y de la navegación
    Repetir el proceso de creación de un nuevo recurso, (Contact)
    Preparado para empezar a utilizar Vue

    ### Paso 7
    Crear routes de Vue.js
    instalar npm i vue-router
    Bind de vue-router a la instancia de Vue
    Añadir en las vistas los links de home y about con <router-link>
    - para ver el contenido de los Vue modules, añadir dentro del tag #app <router-view>
    compilar con node_modules/.bin/webpack --watch
    - Añadir exact al link de home para que no asuma que si la uri empieza por
    / de por echo que está activo
    - Cambiar la clase que Vue añade por defecto cuando el link está activo:
    -- en el routes.js añadimos linkActiveClass
    
    ### Paso 6
    Crear el layout master y dejar el punto de entrada de la aplicación en welcome.blade.php
    ### Paso 5
    Compilar cambios en el directorio de resources de manera manual:
         node_modules/.bin/webpack --hide-modules --progress
         -> no muestra los comandos ejecutados
         -> muestra el progreso de la compilación

    ### Paso 4
    Limpieza del boilerplate en resources sass
    Limpieza del boilerplate en resources js
      sólo importo Vue y axios en el bootstrap
      en app.js creo nueva instancia de Vue y la añado al elemento #app del html

    ### Paso 3
    Configurar webpack.mix
    Cambiar el directorio de compilación de js y sass

    ### Paso 2
    Instalado: npm i laravel-mix
    Copiado el contenido de laravel-mix a la raiz del proyecto:
    cp -r node_modules/laravel-mix/setup/** ./

    ### Paso 1
    clean laravel install
