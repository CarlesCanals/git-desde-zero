# Sección 4: Ramas y flujo de trabajo

## Crear y cambiar a una nueva rama
```bash
git checkout -b nueva-rama
```

## Hacer commits en la nueva rama
```bash
echo "Cambio en rama nueva" > archivo.txt
git add .
git commit -m "Cambio en nueva rama"
```

## Volver a master y hacer merge
```bash
git checkout master
git merge nueva-rama
```

## Ver ramas
```bash
git branch
```