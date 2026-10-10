
# Aprendiendo Git & Github
- Stos son los pasos para iniciar con Git

## Paso 1
- Iniciar el nuevo repositorio
```
Git init
```
## Paso 2
- Enviar los nuevos archivos o archivos modificados al area de preparacion
```
Un Solo archivo en especifico
git add index.html

Todos los archivos
git add .
```
- El area de preparacion es donde se preparan los cambios pendientes

## Paso 3
-Registrar un cambio realizado
```
git commit -m "Proyecto base"
```
-

# Paso 4 Githab
- Une nuestro Git Local a Github
```
git remote add origin https://github.com/alessio034/landing-page-plataforma-chatbot.git
```
-Enviar los cambios al repositorio remoto
```
git push -u origin master
```

## Paso 5
- Actualizar archivos en Github

```
git add .
```
```
git commit -m "Actualizacion de algo"
```
```
git push -u origin master
```
- Como ver el estado de nuestro repositorio local
```
git status
```

------
#### Ejemplo
-Copiar el archivo (.env.example) a (.env) y actualizar las credenciales