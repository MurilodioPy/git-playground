## Armazenar as mudanças em Stach:

```bash
git stash
```

## Listar todas as mudanças armazenadas:

```bash
git stash list
```

![alt text](images/git_stash.png)

## Recuperar o stash mais recente:

```bash
git stash pop
```

![alt text](images/git_stash_pop.png)


## Recuperar um stash específico sem removê-lo da lista:
```bash
git stash apply stash@{0}
```

## Remover um stash específico:
```bash
git stash drop stash@{0}
```

![alt text](images/git_stash_drop.png)

