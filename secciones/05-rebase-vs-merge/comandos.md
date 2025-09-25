# Sección 5: Rebase vs Merge

## Merge
```bash
git checkout master
git merge rama-feature
```

## Rebase
```bash
git checkout rama-feature
git rebase master
```

## Resolver conflictos
1. Editar los archivos con conflicto
2. `git add .`
3. `git rebase --continue`

## Ventaja del rebase
- Historial más lineal y limpio
