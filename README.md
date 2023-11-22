# INSTRUCCIONES PARA CLONAR Y CORRER DOCKER COMPOSE DE MOODLE

## ¿CÓMO CLONAR EL REPOSITORIO moodle?

## 1. Nos dirijimos a nuestro perfil de github y hacemos un repositorio nuevo llamado moodle

![Texto alternativo](./imgs/new.png)

- Asignamos un nombre
- Indicamos si va a ser un repositorio privado o público
- Añadimos un archivo README.md
- Creamos el repositorio

![Texto alternativo](./imgs/create.png)

## 2. CLONAR NUESTRO REPOSITORIO "moodle"

- Abrir repositorio moodle
- Seleccionar la opción code
- Utilizamos la opción HTTPS
- copiamos el código

https://github.com/gallardowolfcode/moodle.git
![Texto alternativo](./imgs/clone.png)

- Abrimos nuestra terminal y pegamos el código -- git clone


https://github.com/gallardowolfcode/moodle.git

- Abrimos nuestro entorno de Visual studio
code .
![Texto alternativo](./imgs/gitclone.png)

### Ejecutar docker compose


## 3. DOCKER COMPOSE
![Texto alternativo](./imgs/dockercompose.png)

## 4. ARCHIVO DOCKER COMPOSE.YML
> Usaremos el comando: 
> cat docker-compose.yml

para verificar el contenido de nuestro archivo.

![Texto alternativo](./imgs/dockercompose3.png)
## 5. INSTRUCCIONES BÁSICAS PARA INICIAR MOODLE
- http://localhost:8080
- Username: user
- Password: bitnami
- 172.21.43.22:80
![Texto alternativo](./imgs/moodleinit.png)
> Insertamos datos en el login

![Texto alternativo](./imgs/login1.png)
> configuramos perfil

![Texto alternativo](./imgs/config1.png)

## 6. CREANDO UN NUEVO CURSO
- En nuestro dashboard vamos a la sección de Add new course

![Texto alternativo](./imgs/addnewcourse.png)

- Al entrar a este menú vemos las opciones disponibles para describir el curso

![Texto alternativo](./imgs/editcourse.png)

![Texto alternativo](./imgs/description.png)

- Llenamos los datos y damos continuar para su creación el cual nos aparece en la pantalla principal de cursos

![Texto alternativo](./imgs/creado.png)

### Con esto tenemos las instrucciones básicas para la creación de un curso en moodle con docker compose.