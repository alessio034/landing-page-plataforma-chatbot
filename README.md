
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
git add index.html
git add .
```
- El area de preparacion es donde se preparan los cambios pendientes

## Paso 2
-Registrar un cambio realizado
```
git commit -m "Proyecto base"
```
-

# Githab
- Une nuestro Git Local a Github
```
git remote add origin https://github.com/alessio034/landing-page-plataforma-chatbot.git
```
-Enviar los cambios al repositorio remoto
```
git push -u origin master
```



------
#### Ejemplo
-Copiar el archivo (.env.example) a (.env) y actualizar las credenciales