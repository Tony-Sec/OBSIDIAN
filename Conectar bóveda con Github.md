1. Crea un repositorio en github.
2. [Descargar Git](https://git-scm.com/downloads)
3. Crea un [token de acceso personal](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-personal-access-token-classic) desde github. Establece el alcance en repo y la caducidad en sin caducidad.![crear-pat-github.png](https://linked-blog-starter.vercel.app/md_assets/attachments/create-pat-github.png)
4. Instalar el complemento de la comunidad [Git de Obsidian](https://github.com/denolehov/obsidian-git/wiki/Installation)
5. Crea en obsidian una carpeta para almacenar el repositorio (por ejemplo, `remote-blog/`). Y dejar vacío el directorio.![remote-blog.png](https://github.com/Tony-Sec/OBSIDIAN/blob/main/img/remote-blog.png)
7. Ejecute el comando (CMD/Ctrl + P): `Clone an existing remote repo`![complemento-git-clon-repositorio.png](https://linked-blog-starter.vercel.app/md_assets/attachments/clone-repo-git-plugin.png)
8. Pegue la URL del repositorio bifurcado en el siguiente formato

```
https://<PERSONAL_ACCESS_TOKEN>@github.com/<USERNAME>/<REPO>.git
```

Por ejemplo podría verse así:

```
https://ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX@github.com/ithinkwong/linked-blog-starter-md.git
```

7. Luego escribe en la carpeta que creaste en el paso 5 (por ejemplo `remote-blog/`).
8. Ejecuta el comando (Ctrl + P) para obtener la vista de Git : Open Source Control View .
9. Reiniciar Obsidian.
10. Realizar modificaciones a tus notas.
11. En la vista Git : Open Source Control View se veran los cambios ejecutados:
	1. Clickar en el boton `+` en `Changes` .
	2. Clickar en el tick para verificar el `commit`.
	3. Clickar en `push` para subir los cambios.
![https://github.com/Tony-Sec/OBSIDIAN/blob/main/img/change-commit-push.png](change-commit-push.png)