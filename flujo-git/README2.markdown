# FLUJO COMPLETO DE GIT

###### Obsercaciones:
si ya se tiene instalado  los respectivos programas tales como Atom y zsh dentro del sistema operativo. sigue con el procedimiento de este articulo.

### procedimiento:

1. Si no has creado una cuenta git. accede al siguiente link -----> [GitHub] (https://github.com/) , si ya lo creaste omite este paso.

2. crea un nuevo repositorio en icono de **+** que se encuentra en ela parte superior izquierda.
*new repotory-asignale un nombre-marca el check como publico-marcar que inicie con un readme.md-marcar un MT-license*

3. Creado el repositorio clona tu repositorio de git en tu local dando clic en *clone or download* dentro de la pagina de git.  

4. La url que aparece copiarla dentro de tu terminal con los siguientes codigos.  **git clone https://github.com/angel1194/ejemplo-md.git**. Una vez clonado entra en la carpeta local que se creo del repositorio de git con: **cd ejemplo-md**

5. Accede a tu repositorio y veras una carpeta y un archivo que se creo anteriormente llamado Readme.md
con el siguiente codigo *git branch*  veras las ramas que tienes creadas.

6. Se mostraran solo una rama llamada **master** la cual no se devera hacer ningun cambio de lo contrario perderas los datos que tengas dentro de ella.

7. Para crear una nueva rama dentro del repositorio que se creo anteriormente usaras la siguiente instruccion dentro de tu terminal: **git branch develop** donde git branch te muestra las ramas creadas y *develop* es la rama creada y te manda directamente e ella. Esa rama la utilizaras más adelante.

8. Te posicionas en la rama develop
 *si no lo estas usa esta instruccion* **git checkout develop** usala para cambiar de rama dentro de tu repositorio.

9. Cuando estes dentro de tu repositorio develop. crearas la siguiente rama apartir de donde estas posicionado.  con el siguiente comando. *git checkout -b add-git-stages* para crear la nueva rama y te posiciones en ella. donde empezaras a realizar tus proyectos.

10. Dentro de esa rama llamda add-git-stages abriras atom en tu terminal con **atom .** donde se abrira automaticamente para poder modicar el archivo Readme.md.

11. Cuando estes en **atom** dentro del archivo Readme.md escribe el contenido que quieres. guardandolo.

12. En tu terminal escribes **git add Readme.md** para que se guarden las modificaciones, realizas un **git status** dentro de la terminal para ver que se guarde la modificacion.

13. Posteriormente despues del paso 12 realizas un **git commit -v** para guardar los cambios.

14. ahora que esten guardados los cambios, subes tu rama a git con la siguiente instruccion: **git push origin add-git-stages** donde add-git-stages es tu rama y compruebas
pidiento tu usuario y password.

15. Ahora que esten en el git realizaras una comparacion con otra rama llamada **develop** creada anteriormente pero no aun en git asi que la subes como en el paso 14 solo que cambias el nombre de la rama.
