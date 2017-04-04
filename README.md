## The-side-of-the-source2
Este repositorio es para que tu Sami y yo -tu hermano,
compartamos un lugar en internet donde almacenar información
de distinta índole, sease logs y tal!

Ambos podemos ver y modificar el repositorio -usea este directorio

#### Configuración global

    $ git config --global user.name "miNombre"  
    $ git config --global user.email john@doe.net

Esto configura tu nombre de usuario y correo para trabajar remotamente.

Para trabajar con git únicamente necesitas configurar esto y el repositorio
master/origin. 

- _Master:_ normalmente se refiere al repositorio local de la ramma principal.
- _Origin:_ se refiere al repositorio remoto, en este caso es la rama principal
de nuestro repositorio en git. DVCS- distriburted version control system. Git.

#### clonar un repositorio

    $ git clone <repositorio>

- Esto clona el repositorio. Es muy simple. Mira por ejemplo nuestro repositorio.  
El botón berde -en la página de git sobre el repositorio que queramos clonar.
Click sobre este, aparece una ventanita con una dirección _https://_ por
defecto, y sobre la dirección, `use SSH`. 
Son dos formas de enlazar hacia/desde el repositorio. Nosotros usaremos `SSH`.
Al final de la línea con la dirección hacia el repositorio, aparece algo
parecido a una _pila con una flecha??_. Esto copia la dirección al portapapeles.

Abres la cónsola, esquina superior con el puntero sin clicar y escribes: 
    gnome-terminal
    o quizás terminal 

- A continuación, nos situamos sobre un directorio, `cd mi-directorio`.
- y escribimos lo siguiente:
    git clone <direcion del portapapeles> return

#### subir archivos 
Hemos copiado el truco de turno, para nuestro game, o hemos encontrado un
parche, de la _o***_ y queremos compartirlo con el mundo. 

- copiamos el archivo al repositorio.
    $ git add .

Esto añade todo. todo lo que hayamos metido ahí, será _registrado_ para 
posteriores acciones.

    $ git commit -m "fecha o comentario".

Esto es necesario para validar que nuestra acción previa. Con este comando
estamos confirmado todos los archivos _añadidos/quitados/modificados_ y
estableciendo un `-m` comentario que servirá para levar un registro de lo 
que hicimos.

    git push

Esto lleva a cabo la acción confirmada,  sincroniza ambos repositorios:
remoto y local.


Saludos, 


> pd. este texto cambiará sin previo aviso cuando lo hayas leído.
