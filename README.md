Se debe descargar el Spring con las extensiones de Spring Web, PostgreSQL Driver y Spring Data JPA.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/e9cfddda-a2f8-4e3d-a4ef-0ccddfbae9d2)

Debemos crear las siguientes carpetas y clases: una carpeta controllers que contenga la clase HotelController.java, otra carpeta model que incluya la clase Hotel.java, una carpeta repositories con la clase HotelRepository.java, y finalmente, una carpeta services con dos clases: HotelService.java y HotelServiceImp.java.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/44165163-2647-4b89-a8ec-072412242eca)

Presentación brevemente de las clases que se realizó.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/3db6c88c-1c89-46b6-acd1-0dfe00dda133)
![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/429cb8bd-89a4-4a8a-b971-2fe4a802cf58)
![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/09d111c6-2dcb-4861-b7fa-c8577a494f2f)
![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/3e2d2dae-d10f-44c6-abac-a2f89900ba05)
![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/b08f6ac4-41f6-412e-9090-bed50b87a460)

En la carpeta de resources en application.properties se hace la conexión a la base relacional.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/5bee9f7b-aae0-45f1-811c-3d2c28f3cdf3)

Presentación de lo que se implementó en application.properties, debemos colocar el nombre de la base de datos que sería bookingdb y colocar la contraseña de la base relacional que se vaya a utilizar que sería PostgreSQL.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/a279f10d-ebc0-4158-8c1b-269ea461c11f)

En la carpera de resources se crea el data.sql.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/58c18d4d-78d4-4ce1-bd2b-e897b1611ae6)

Dentro de la data.sql se hace la presente codificación.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/edfe67db-b055-48e1-ae23-a9714de50146)

Base relacional siendo PostgreSQL.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/1eff5407-7412-4c3b-bd8b-99d7f1f092d7)

Demostración de la tabla hotel con sus respectivas columnas.

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/2c1e8544-0571-4a66-bbb5-3f2cbf72ed07)

# Ejecución de la conexión a la base relacional PostgreSQL

![image](https://github.com/Diana29004/Cambiar-de-base-de-datos-de-h2-a-una-relacional/assets/170267544/fc320f07-de8e-4ab0-8cde-fea568403c1f)


