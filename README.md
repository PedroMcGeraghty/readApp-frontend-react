# ReadApp

Trabajo practico de la Facultad para la materia de Algoritmos III , el cual consiste en una Aplicación web de libros Readapp. La misma esta desarrollada con React y Typescript. La misma se impmento solo para diseño mobile utilizando el framework de react, Material UI.
## Casos de uso

**Login**

La aplicación cuenta con una pantalla de autenticación de usuario. Utiliza el mismo endpoint de la aplicación frontend realizada en angular.
- Frontend: https://github.com/PedroMcGeraghty/readApp-frontend-angular
- Backend: https://github.com/PedroMcGeraghty/readApp

![image](https://github.com/user-attachments/assets/ee80bfa9-4f97-4523-8d8e-d99f8e67a84f)


**Home**

En la home podrán verse datos estadísticos de interés para la app. La sumatoria de recomendaciones ofrecidas  y libros del sistema, el total de usuarios y el total de centros de disrtibución. Tenemos dos acciones que son las de borrar usuarios inactivos u centros inactivos. Ambas acciones deberían verse reflejadas en las sumatorias. También disponemos de una botonera al pié que permite:

- Navegar a la home.
- Navegar a la página de libros.
- Navegar a la página de autores.
- salir de la app.

![image](https://github.com/user-attachments/assets/0106421f-cffd-4914-a1dd-597d3696d79a)
![image](https://github.com/user-attachments/assets/ec929fc3-3075-4e02-b1fc-7b2b749286b4)

**Sección de Autores**

Esta pantalla muestra la lista de los autores que permite seleccionar el sistema. Desde esta, haciendo tap en los respectivos iconos, se puede eliminar el autor, o navegar a la edición de la misma. También permite agregar un nuevo autor a la app por medio de un botón flotante, o simplemente ver el detalle del autor al hacer tap sobre ella.
La misma pantalla tiene un sistema de búsqueda que permite filtrar los resultados mostrados por nombre.
En el formulario cuenta con validaciones de los campos tanto en la creación como en la edición. La forma de mostrar los errores es a traves de un toast. La app no permite eliminar un autor que se encuentre relacionado con un libro.

![image](https://github.com/user-attachments/assets/53ee613d-fc2d-4ddb-8aa8-a7624a0a6380)
![image](https://github.com/user-attachments/assets/d7e0b834-0ab3-4abf-aef7-df3fe4e01c1c)
![image](https://github.com/user-attachments/assets/68fd30e9-4ce0-4bcc-b8a9-b26b9f4b81be)

**Sección de Libros**

Al igual que los autores, esta página permite buscar y filtrar los resultados de los posibles libros que se encuentran en el sistema, así como eliminar, editar o ver el detalle de los mismos. 
También permite agregar un libro nuevo, para lo cual se navega al formulario a completar. Los iconos de los libros cambian en base a si son  de lectura desafiante y best seller de acuerdo al cálculo específico. Además el idioma original está ligado al idioma natal del autor. 

![image](https://github.com/user-attachments/assets/4d0ff2f7-4cbb-41f8-b2ad-13038c28bb9f)
![image](https://github.com/user-attachments/assets/0298bfcb-2c29-41d9-be3d-2f4d8a048daa)
![image](https://github.com/user-attachments/assets/d909a098-c241-44df-b604-8cef3982e6fa)

**Modo Nocturno**

La aplicacion cuneta tambien con un modo nocturno el cual se realizo utilizando el hook useTheme().

![image](https://github.com/user-attachments/assets/074e17b7-f55b-45d0-bef6-2346740b0f69)
![image](https://github.com/user-attachments/assets/d35aaf58-a6dd-4dc8-b2f1-7114edbf95f2)
![image](https://github.com/user-attachments/assets/5aa5579a-3114-4f70-b0e2-4825fd87edff)









