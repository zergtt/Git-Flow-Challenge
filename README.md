## Git Workflow Challenge

Un cliente con un blog famoso de código está escribiendo una serie de blogposts acerca de Markdown.

Tú eres un escritor famoso de markdown y te ha pedido que lo apoyes con varias secciones del post.

El cliente te informa que su sitio web es monitoreado con git usando gitflow.

Ya tiene un branch `master` y un branch `develop`.

### Material

- [Contenido de los posts](https://gist.github.com/walreyes/7292940d5679ac98780202b5082dc208)
- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### ¿Qué aprendere con el reto?

- Crear branches
- El framework de Git
- Cómo hacer un Pull Request
- Buenas prácticas de un Pull Request
- Resolver Merge Conflicts
- Colaborar Open Source

### Retos.

#### 1. Haz un `fork` del repo de tu cliente

1.  Ve a https://github.com/walreyes/Git-Flow-Challenge
2.  Da click en `fork`
3.  Clona ese `fork` en tu máquina local.

#### 2. Tu cliente te pide que agregues un post sobre `Images`

1.  Crea un feature branch de `develop` llamada `feature/images-post`

- Recuerda tener un nombre descriptivo.

2.  Copia el contenido de `images.md` debajo de `markdown-series.md`.
3.  Simula varios commits al estar copiando el contenido.
4.  Haz un `Pull Request` en github para hacer `merge` a `develop`.

- Recuerda usar buenas prácticas en las descripción de tu PR.

5.  Haz merge a `develop`.

#### 3. Tu cliente te pide que agregues un post sobre `código`

1.  Excluyendo el paso 5, sigue los mismos pasos del reto anterior.

- Usa `code-part-1.md`

2.  **Se te ha presentado un imprevisto y no vas a poder terminar el post ahora mismo**
3.  Agrega un `[WIP]` justo al inicio del título de tu branch

- Esto es considerado una buena práctica para saber si un feature branch ya ha sido terminado o no.

#### 4. Tu cliente te pide que agregues un post sobre `Links`

1.  Sigue los mismos pasos que el reto número 2 pero con el post de `Links`
2.  Incluye el merge a `develop`

#### 5. Ya tienes tiempo para terminar la sección de `Código`.

1.  Agrega la sección de `code-part-2.md`
2.  Haz merge a `develop`

### 6. Haz terminado el trabajo, crea un release branch para unir el código a tu cliente.

1.  Crea un release branch desde `develop`
2.  Haz un `Pull Request` en Github
3.  Haz un merge a `walreyes:Git-Flow-Challenge` en lugar de tu master.

- Recuerda que hiciste un fork del repositorio de tu cliente

4.  Avisa que ya hiciste el PR a tu cliente para que lo revise y lo libere

### Bonus.

1.  Encuentra la manera de hacer `tag` de una versión de master a un `commit`.
