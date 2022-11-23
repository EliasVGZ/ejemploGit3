# ejemploGit3

1.Creamos un repositorio nuevo en github con un README y un .gitignore<br>

![image](https://user-images.githubusercontent.com/113994483/203584626-d662f7c8-c970-4b31-95cf-c0feb1dc9554.png)<br>

2.Creamos un proyecto nuevo marcando la opción "Create Git repository"<br>

![image](https://user-images.githubusercontent.com/113994483/203584794-3ca7f5e8-1590-4305-b1ba-8b670aff1430.png)<br>

![image](https://user-images.githubusercontent.com/113994483/203585004-8d61f888-2dbf-44f5-b0a2-9abaaf9217d1.png)<br>

3.Añadimos el repo de github como remoto e intentamos hacer un pull (recordemos que lo hemos creado con un README y un .gitignore)<br>

![image](https://user-images.githubusercontent.com/113994483/203586269-d120ea31-00ca-47cc-972e-566388df8288.png)<br>

![image](https://user-images.githubusercontent.com/113994483/203586431-20dc1c9a-0f8e-434a-a8b0-b542a2a2eb94.png)<br>

No podemos hacer un pull por tener cambios en stage local que no hemos commiteado (los ficheros del proyecto local). Al crear el proyecto marcando la opción "Create Git repository", se ha hecho un git init y, aparentemente, se han añadido al stage (se ha hecho un git add) pero no hemos hecho un commit.<br>

4. Quitamos los cambios del stage (deshacemos el git add)<br>

![image](https://user-images.githubusercontent.com/113994483/203587295-a283d64f-9d75-4137-a279-eccae877e229.png)<br>

5.Ahora los cambios están sin trackear. Intentamos de nuevo hacer un pull.<br>

![image](https://user-images.githubusercontent.com/113994483/203587646-d5ecf7f4-4711-443b-a807-6ee8072f5197.png)<br>

Al haber creado un .gitignore en remoto y otro en local, hay un conflicto entre estos ficheros.

6.Podemos eliminar el .gitignore local si queremos quedarnos con el remoto:<br>

![image](https://user-images.githubusercontent.com/113994483/203588403-a56cf8ad-7580-4d04-98b3-075f9c8af5e5.png)<br>

7. Ya tenemos descargado lo que estaba en remoto (el README y el .gitignore de GitHub) en la rama main (rama por defecto en GitHub) a nuestra rama master local.<br>

Ahora commiteamos el proyecto local y lo subimos al repositorio.

![image](https://user-images.githubusercontent.com/113994483/203588779-f77bc02b-c6bc-498b-b0ef-0027b731b9c7.png)<br>

![image](https://user-images.githubusercontent.com/113994483/203588970-9c935c83-bcca-49f5-8db1-e3d4aed79cfd.png)<br>

![image](https://user-images.githubusercontent.com/113994483/203589307-5c14cda5-6361-4707-be90-fb05fd14fee0.png)<br>

![image](https://user-images.githubusercontent.com/113994483/203589480-84f9e7a2-e172-4004-9c52-7f929ca3af4d.png)<br>

Observamos que se ha subido correctamente pero en la rama master (que era en la que estábamos trabajando en local), mientras que la rama main se mantiene con su primer commit.<br>

![image](https://user-images.githubusercontent.com/113994483/203593772-64672135-eb61-41b2-838f-07e1afc6402d.png)<br>

![image](https://user-images.githubusercontent.com/113994483/203593783-9f418212-8007-4dad-b189-4ba78843e1a9.png)<br>

8. Eliminamos la rama main en el repositorio de GitHub
