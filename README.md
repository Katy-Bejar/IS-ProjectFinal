# Sistema de Publicación de Eventos 
# Relacionados con Ciencia de la Computación

## Propósito del proyecto


El propósito de este proyecto es realizar una página web que nos muestre los
eventos relacionados con "Ciencia de la computación" , con esta página web podremos tener un sistema de consulta, registro y creación 
de eventos relacionados con la computación, los usuarios tendrán la oportunidad de informarse sobre más eventos tecnológicos, 
al mismo tiempo que podrán registrarse si alguno de ellos es de su interés, incluso los organizadores de eventos podrán publicitar
su evento en nuestra página web para que tenga mayor alcance. 

## Funcionalidades

## Prácticas de código legible aplicadas

### 1. Comentarios y documentación 

    Comentar el código es de mucha utilidad hoy en día porque permite entender mejor la funcionalidad del mismo para que
    demás desarrolladores puedan utilizarlo de diferentes maneras. 
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen1.png)
    
### 2. Sangría consistente 

    Las sangrías ayudan a mantener un orden visual para mayor entendimiento.
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen2.png)
    
 ### 3. Agrupación de códigos 

    En ocasiones un conjunto de tareas no ocupa mucha realización de código.
    Por lo que es recomendable mantenerlos en bloques para localizarlos mas rápido.
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen3.png)   
    

  ### 4. Esquema con nombres coherentes

    Los nombres deben tener límites de palabras para ello se usa el subquión 
    o mayúsculas.
    Un ejemplo en nuestro codigo es el siguiente:
    
  ![Screenshot](Imagenes/screen4.png)   
  
  
  ### 5. Límite de longitud de línea

    Es mejor tener un límite de línea que una línea extensa de código de
    difícil legibilidad.
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen5.png)   
    
    
   ### 6. Evite el anidamiento profundo

    Demasiados niveles de anidamiento hacen que el código sea menos legible
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen6.png) 


## Estilos de programación aplicados

### 1. CookBook 

    Para realizar una acción se dividen las subtareas en funciones más pequeñas
    y al final se juntan para resolver un mismo objetivo.
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen7.png)

### 2. Programación orientada a objetos

    Una forma mas fácil de manejar un escenario con muchas partes es crear objetos
    que nos permitan un mejor manejo y estructuración de nuestro escenario. 
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen8.png)
  
  ![Screenshot](Imagenes/screen9.png)

### 3. Trinity

    La aplicación se divide en tres componentes que son el modelo, la vista y
    el controlador. 
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen10.png)

## Principios SOLID aplicados

### 1. Principio de inversión de dependencias 
    
    Un modo de emplear este principio es cuando para un servicio web utilizamos conexión a base de datos,
    es mejor colocar en un archivo o función aparte las configuraciones de la conexión de base de datos,
    para así evitar modificar adicionales líneas de código donde hacemos uso de la base de datos.
    Un ejemplo en nuestro código es el siguiente:
    
  ![Screenshot](Imagenes/screen11.png)
  
### 2. Principio abierto/cerrado
    
    En el proyecto se tiene la opción de agregar evento lo cual representa a la parte de abierto del principio, pero además 
    muestra todos los eventos que hay sin necesidad de modificar la parte del código que lo muestra, pues se utiliza una 
    iteración, lo que representa la parte de cerrado del principio.
    Como se muestra a continuación:
    
    -OPEN: Agregar evento
   ![Screenshot](Imagenes/screen13.png)
   
    -CLOSE: Mostrar eventos
   ![Screenshot](Imagenes/screen12.png)
    
    


## Conceptos DDD aplicados 

### 1. Lenguaje Obicuo
    
    Para tener una mayor comprensión entre todos los desarrolladores establecimos palabras que
    serán de uso grupal a la hora de implementar, asi entendemos mejor el codigo de los demás.
    Un ejemplo de nuestro lenguaje oblicuo son los siguientes términos:
    
    - login --> operaciones de acceso
    - register --> operaciones de registro
    - base --> pantalla principal
    - view--> implementacion para vistas
    - config --> configuraciones principales
    - static --> archivos estaticos de diseño
    - models --> implementación de los modelos del proyecto
    - templates --> plantillas html para las vistas 
    
 ### 2. Corazón del Software
    
    El modelo es el corazón del software por lo cual se usan repositorios, mediante los cuales
    se puede visualizar, probrar y visualizar los avances y modficaciones del proyecto.
    En nuestro caso utilizamos el repositorio de GITHUB.
    
    ![Screenshot](Imagenes/screen16.png)
    
    
 ### 3. Mocks
    Una de las ventajas de utilizar DDD es que permite las pruebas MOCK la cual consiste 
    en realizar examenes de prueba unitaria para hallar errores de codigo antes de juntar
    todos los objetos y archivos que componen el proyecto.
    
    - Utilizamos pruebas MOCK con cada una de las vistas antes de unir todo el proyecto.
    
    
  









