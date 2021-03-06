# Base para Aplicación Web

### Autor: Vicente Fuenzalida Marín

La idea de esta aplicación es servir como un punto de partida para la realización de aplicaciones *sencillas* a modo de **Proof of Concept**.

Se realizó la integración con diversas gemas "típicas" en varias *branches* para poder trabajar solo con las *features* que se necesiten.  

La idea es seleccionar la branch que contenga las caracteristicas apropiadas para el proyecto que se desea desarrollar.

## Las gemas o funcionalidades que se cubren son las siguientes:

* Devise (Autentificación de usuarios)

* Bootstrap (JS y CSS responsive)

* Toastr (notificaciones)

* Slim (motor de templating)

* PostgreSQL (Base de datos)

## Consideraciones

* Ruby 2.5.0p0
* Rails 5.2.0
* RVM 1.29.2 (como gestor de entorno ruby)

> Al menos se debe tener instalado Ruby y bundler para proseguir con el setup!

## Setup

Para probar la aplicación base, los pasos son los siguientes:

### 1. Clonar el repositorio
```
git clone https://github.com/vjfuenzalida/rails-template-app.git
```

### 2. Navegar al directorio raíz
```
cd rails-template-app
```

### 3. Instalar las dependencias
```
bundle install
```

### 4. Inicializar la base de datos
```
rails db:setup
```

### 5. Levantar el servidor
```
rails s
```

Si todo lo anterior se ejecutó correctamente, la aplicación debería estar corriendo localmente en la URL http://localhost:3000/