# SpringBootVentas
Este es un proyecto para compartir conocimiento con desarrolladores hispanohablantes

1.- Trabajaremos con el IDE Spring Tool 4, lo pueden descargar de la siguiente URL: https://spring.io/tools

2.- Usaremos Java versión 11, motivo por el cual usaremos JDK versión 11, pueden descargar del proveedor que deseen, de igual manera les dejo la URL de donde yo descargué: https://adoptium.net/es/temurin/releases/

3.- Usaremos PostgreSQL para la base de datos, pueden descargarla de la siguiente URL: https://www.postgresql.org/download/

Para cualquier consulta pueden escribir en el discord: https://discord.gg/QCDZU2PA

*******************INICIO - Creación del Proyecto en Spring Tool 4*******************

1.- File -> New -> Spring Starter Project

2.- LLenaremos los siguientes campos

	2.1.- Name -> Ventas
	2.2.- Type -> Maven
	2.3.- Java Version: 11
	2.4.- Group -> com.tienda
	2.5.- Version -> 0.0.1
	2.6.- Description -> Proyecto backend ventas
	2.7.- Package -> com.tienda
	2.8.- Next

3.- Elegimos la versión del Spring Boot -> 2.7.8

4.- Agregamos las siguientes dependencias

	4.1.- Spring Data JPA
	4.2.- PostgreSQL Driver
	4.3.- Spring Web
	4.4.- Finish


*******************INICIO - PostgreSQL*******************

1.- Crear una base de datos llamada tiendasperu


*******************INICIO - Configuración del archivo application.properties*******************

	1.- spring.jpa.database=postgresql
	2.- spring.jpa.show-sql=false
	3.- spring.jpa.hibernate.ddl-auto=update
	4.- spring.datasource.driver-class-name=org.postgresql.Driver
	5.- spring.datasource.url=jdbc:postgresql://localhost/tiendasperu
	6.- spring.datasource.username=postgres
	7.- spring.datasource.password=root




