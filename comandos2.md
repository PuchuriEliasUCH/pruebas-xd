# Comandos para git/github - parte 2

HOLIIII :D

ahora podrás subir tu propia parte del trabajo jiji

## Repositorio

[fundamentos de programación](https://github.com/PuchuriEliasUCH/fundamentosDeProgramacion-UCH.git)

clonalo y que comience la magia

## Comenzamos :D

### Creando tu espacio de trabajo (rama / branch)

para comenzar, crearás tu propio espacio de trabajo!!

para ello, en la consola esa fea escribe

```bash
git checkout -b nombre
```

y mira!! eso que está en azul, ya no dice (main)

ahora ya puedes hacer lo que quieras con el proyecto :D

no te preocupes, no se va a eliminar...

borra mmm no sé... el ejercicio 3 por ejemplo xd

### Viendo los espacios de trabajo del proyecto

para poder ver los espacios de trabajo puedes utilizar este comando

```bash
git branch
```

y te dirá en que espacio de trabajo estás resaltando en verde tu posición actual

> #### Importante!!
>
> si te sale una vaina rara con puntos y guiones, NO TE ASUSTES XD
>
> se llama VIM ... en pocas palabras es un editor todo feo para gente pro :C
>
> LO IMPORTANTE!!
>
> para salir de ahí solo escribe `:q` tal cual, dos puntos q

### Moviendote entre las ramas de tu proyecto

también puedes moverte entre los espacios de trabajo xd
con este comando

```bash
git checkout <nombre>
```

y de hecho, verás que el ejercicio 3 está otra vez en su sitio xD
te dije! no te preocupes :D

si te das cuenta, para crear tu espacio usamos el mismo comando
pero con un -b ... son parámetros de uso :D y hay un montón

### Subiendo los cambios al repositorio

con esto ya puedes subir tu espacio de trabajo al github :D
y como se hace? pues igual como si estuvieras subiendo los cambios
como lo hicimos el otro día

```bash
git add .
git commit -m ""
git pu...
```

espera, que pasa si intentas el `git push origin main`???

intentalo xd

**_Fer en estos momentos:_**

AHHHH PERO YO ESTOY SEGURA QUE HICE CAMBIOS Y NO SE HAN GUARDADO!!
LO VUELVO A INTENTAR...

AHHH LO MISMO!!

espera espera xD

recuerdas que te dije que los comandos son un poco más extensos
de lo que te decía en el repo??

al utilizar

    git push origin main

le estas diciendo esto:

```
    tu: git
		tu: sube mi codigo (push)
		tu: al repositorio remoto (origin)

	         											que quieres que suba? : git

		tu: el espacio de trabajo principal (main)
```

vez? -> `git push origin main`

siguiendo esta lógica... cual es el espacio de trabajo
que quieres subir?
exacto!! el tuyo... entonces sería

    git push origin <nombre>

### Elimina tu espacio de trabajo

ya subido al repositorio, ya puedes eliminar esta rama que haz creado jiji

**_Por qué eliminar la rama de trabajo?_**

la respuesta facil es, para que no te confundas al momento de seguir trabajando...

al igual que tú, tus compañeros de trabajo tambien realizarán sus cambios y el proyecto va a cambiar

por ello, bajo mi punto de vista, es mejor eliminar esa rama de trabajo para luego crear otra CON el proyecto actualizado

como hacemos esto?

    git branch -D <nombre>

si vemos nuevamente las ramas del proyecto, ya habrá sido eliminada tu rama de trabajo

### Hasta la prossimaaaaaa...

Esto es todo por hoy!! :D

puedes ir practicando con el repo, o me avisas para crear otro solo para ir jugando...

siguiente clase, errores :v
