# Sección 2: Crear un repositorio local

## Crear carpeta del proyecto
```bash
mkdir primer-repo
cd primer-repo
```

## Inicializar Git
```bash
git init
```

## Crear un archivo y verificar estado
```bash
echo "Hola Mundo" > archivo.txt
git status
```

## Añadir archivo al staging area y hacer commit
```bash
git add archivo.txt
git commit -m "Archivo 'archivo.txt' creado"
```