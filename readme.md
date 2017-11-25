# Preguntas

## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

```
git reset --hard HEAD~1
```

> Queremos deshacer el último commit, usamos HEAD~1 para ello, y como queremos perder los cambios del working copy --hard para que el working copy se vea modificado.

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
```
git reset --hard 018cc19
```
> Queremos volver al commit previo ponemos el hash y el --hard para que el working copy vuelva  a estar como estaba en ese commit.

## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
>No genera conflicto. Los cambios en la rama con la que se hace el merge ya están en la rama actual.

## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
>Si genera conflicto. El motivo es que ambas ramas tenían cambios en el fichero en las mismas líneas.

## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
>No genera conflicto. El repo los commits de las ramas a mergear forman una estructura de arbol por lo cual sólo se mueve head y master al commit donde está la rama a mergear. Aun así yo hice un merge no fast forward por lo que se crea un commit nuevo.

## ¿Qué comando o comandos utilizaste en el paso 25?
```
git log --graph --decorate --pretty=oneline
```

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
>Si. El repo los commits de las ramas a mergear forman una estructura de arbol. Aun así yo hice un merge no fastforward.

## ¿Qué comando o comandos utilizaste en el paso 27?
```
git reset HEAD~1
```

## Qué comando o comandos utilizaste en el paso 28?
```
git checkout -- git-nuestro.md
```

## ¿Qué comando o comandos utilizaste en el paso 29?
```
git branch -D title
```

## ¿Qué comando o comandos utilizaste en el paso 30?
```
git reflog
git reset --hard 81bc1cf
```

## ¿Qué comando o comandos usaste en el paso 32?
```
git reset --hard 6f5c800
```

## ¿Qué comando o comandos usaste en el punto 33?
```
git reset --hard 81bc1cf
```
