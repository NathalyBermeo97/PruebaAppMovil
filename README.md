# PruebaAppMovil 
# Parte inicial del proyecto
Se crea un proyecto en Firebase , esta plataforma permite la creación de mejores apps, minimizando el tiempo de optimización y desarrollo, mediante diferentes funciones, tiene varios tipos de autentificación y permite almacenamiento de nuestros datos.
![image](https://user-images.githubusercontent.com/66235614/145815435-2ba8547a-5cab-4a79-9cf4-8e09e8a504d0.png)
![image](https://user-images.githubusercontent.com/66235614/145815506-82642c60-1a8a-45d9-a79f-b73f6d413241.png)
# Login
Se utilizo varias funciones para el realizar el registro e inicio de sesión.

![image](https://user-images.githubusercontent.com/66235614/145815724-fc57fd8d-dc00-41ac-94cc-fed1a4c4f7f2.png)
![image](https://user-images.githubusercontent.com/66235614/145815739-e518852a-a01f-408a-9d98-6a44537df000.png)
# Recuperación de contraseña 
Para la recuperación de contraseña creamos una pagina llamada forgot-password y en la codificación del forgot-password.page.html agregamos elementos como input de tipo email y un botón para llamar a un método llamado onReset.

![image](https://user-images.githubusercontent.com/66235614/145815833-fe1ef2c5-df73-491b-bad2-a7d9bd34ec29.png)
Verificamos las rutas en app.routing.module.ts
![image](https://user-images.githubusercontent.com/66235614/145815861-b47a33d1-b0ce-4f7c-89ec-e9d4bcaf94c4.png)

Creamos un método asíncrono en chat.service.ts para la recuperación de contraseña, utilizamos un try catch para manejar los errores y para el envio de mensaje para recuperar la contraseña.

![image](https://user-images.githubusercontent.com/66235614/145815975-1ffb3ae4-060e-46f6-818c-cbe9d9655c32.png)

En la parte de forgot-password.page.ts  creamos una función asíncrona  que permita recuperar la contraseña y una alerta para verificar en el envio de mensaje de recuperación de contraseña al correo.

![image](https://user-images.githubusercontent.com/66235614/145816181-d429c097-d290-4548-9407-248b0b943293.png)


