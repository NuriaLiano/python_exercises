# PYTHON_EXERCISES

Este repositorio ha sido creado con el fin de practicar y entender cómo funciona Git, un sistema de control de versiones ampliamente utilizado. Aquí, llevaremos a cabo diversas actividades para familiarizarnos con los conceptos de control de versiones, clonación, ramificación, fusiones y mucho más.

Además de ser un repositorio de prueba de Git, también contendrá ejercicios de Python que iremos realizando durante nuestras clases. Estos ejercicios nos permitirán mejorar nuestras habilidades de programación en Python, resolver problemas prácticos y aprender sobre diferentes conceptos del lenguaje.

## ¿Cómo me descargo y contribuyo al repositorio?

### Clonar repositorio

#### Con carpeta ZIP

1. Abre el explorador web y navega a la página principal del repositorio en GitHub.
2. Haz clic en el botón verde "Code" que se encuentra en la esquina derecha de la página y luego haz clic en "Download ZIP". Esto descargará el repositorio en formato ZIP.
3. Descomprime el archivo ZIP en una ubicación de tu elección en tu computadora. Ahora tendrás una carpeta con el nombre del repositorio y todo su contenido.

#### Git clone ssh

Desde el directorio donde quieras almacenar el repositorio en tu equipo local escribe el siguiente comando desde la terminal:

>:warning: **ADVERTENCIA** es importante tener las claves ssh del usuario de tu equipo local en los perfiles de gitlab y/o github

**GITLAB**

~~~git
git@gitlab.com:Nuria_Liano/python_exercises.git
~~~

**GITHUB**

~~~git
git@github.com:NuriaLiano/python_exercises.git
~~~

#### Git clone https

Desde el directorio donde quieras almacenar el repositorio en tu equipo local escribe el siguiente comando desde la terminal:

**GITLAB**

~~~git
https://gitlab.com/Nuria_Liano/python_exercises.git
~~~

**GITHUB**

~~~git
https://github.com/NuriaLiano/python_exercises.git
~~~

### Subir cambios al repositorio

1. Abre la carpeta del repositorio que clonaste en tu computadora utilizando el Explorador de Archivos de Windows.
2. Realiza las modificaciones o añade nuevos archivos en la carpeta del repositorio según sea necesario.
3. Abre una terminal en Windows 11 (puedes usar PowerShell, Command Prompt o cualquier otra terminal que prefieras).
4. Navega a la ubicación de la carpeta del repositorio usando el comando cd (por ejemplo, si la carpeta está en el escritorio, puedes usar cd C:\Users\TuUsuario\Desktop\nombre_del_repositorio).
5. Verifica el estado de los cambios locales en el repositorio utilizando el comando **git status**. Esto te mostrará una lista de los archivos modificados o nuevos que estás a punto de añadir al repositorio.
6. Utiliza el comando **git add** para agregar todos los cambios locales al área de preparación (staging area). Si solo deseas añadir archivos específicos, puedes utilizar **git add nombre_del_archivo**.
7. Realiza un commit para guardar los cambios en el repositorio local utilizando el comando **git commit -m "Mensaje descriptivo del commit"**. Asegúrate de proporcionar un mensaje claro y descriptivo que explique los cambios realizados.
8. Finalmente, sube los cambios al repositorio remoto en GitHub utilizando el comando **git push** origin nombre_de_la_rama. Por defecto, el nombre de la rama principal es "main". Si has creado una rama diferente, reemplaza "nombre_de_la_rama" con el nombre de tu rama.

---

## License

All content in this repository is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International Public License](./LICENSE)

## Contact

You can write to me at <hola@nurialiano.es>

Visit my profiles or my website

<div>
    <p align="center">
        <a href="https://www.twitch.tv/nurialiano" target="_blank"><img height="50" src="https://github.com/NuriaLiano/NuriaLiano/raw/master/img/icons/twitch.svg" /></a>
        <a href="https://gitlab.com/nuria_liano" target="_blank"><img height="50" src="https://github.com/NuriaLiano/NuriaLiano/raw/master/img/icons/gitlab.svg" /></a>
        <a href="https://github.com/nurialiano" target="_blank"><img height="50" src="https://github.com/NuriaLiano/NuriaLiano/raw/master/img/icons/github.svg" /></a>
        <a href="https://twitter.com/nuria_liano" target="_blank"><img height="50" src="https://github.com/NuriaLiano/NuriaLiano/raw/master/img/icons/twitter.svg"  /></a>
        <a href="https://discord.gg/jSytrMk8" target="_blank"><img height="50" src="https://github.com/NuriaLiano/NuriaLiano/raw/master/img/icons/discord.svg"/></a>
        <a href="https://www.buymeacoffee.com/lianonuria" target="_blank"><img height="50" src="https://github.com/NuriaLiano/NuriaLiano/raw/master/img/icons/by-me-a-coffee.png" /></a>
    </p>
</div>

---

<div>
    <p align="center">Desarrollado en <a href="https://turismodecantabria.com/inicio"></a> <img src="https://github.com/NuriaLiano/NuriaLiano/blob/master/img/icons/cantabria.png?raw=true" height="30" alt="Cantabria">  con mucho <img src="https://github.com/NuriaLiano/NuriaLiano/blob/master/img/icons/metal.png?raw=true" height="30" alt="metal"> y <img src="https://github.com/NuriaLiano/NuriaLiano/blob/master/img/icons/beer.png?raw=true" height="30" alt="cerveza"></p>
</div>