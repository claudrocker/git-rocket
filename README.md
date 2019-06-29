# git-tips
Lista de comandos git más usados

## Comandos básicos

Ver estado del repositorio local
```
git status
```

Ver log de commits del repositorio local
```
git log
```

Revisar cambios uno a uno. Dejar en stage los cambios.
```
git add -p
```
- Aceptar los cambios uno a uno
- Una vez aceptados todos los cambios podemos hacer el commit

Hacer un commit
```
git commit -m '<mensage>'
```

Para hacer un push
```
git fetch origin ramaBase
```
```
git rebase origin/ramaBase
```
```
git push origin miRama
```
