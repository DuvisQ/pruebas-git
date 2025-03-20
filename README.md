# SOCIAL OPLESK
### 💼 KIT 
<br/>

## ⚡️ Kit comandos git ⚡️
<br/> 

## 🏆 K-1 (CREAR CUENTA LOCAL)
Al tener git descargado, es hora de consfigurar una cuenta local:
```
   - git config --global user.name "Tu nombre"
   - git config --globaL user.email "Tu correo"
```


## 🏆 K-2 (HACER UN PUSH)
```
   - git init
   - echo. > foo.txt
   - git add .
   - git commit -m "primer commit"
   - git remote add origin https://github.com/usuario/repositorio.git
   - git branch -M main
   - git push -u origin main

```

## 🏆 K-3 (PUSH CON MODIFICACIONES)
 Si quieres hacer un push y antes deseas extraer ciertos recursos del staging:
```
    - echo. > bar.txt
    - echo. > qux.txt
    - git add bar.txt
    - git status
    - git reset bar.txt
    - git status
    - git commit -m "Segundo commit"
    - git commit --amend -m "Segundo commit modificado"
    - git add qux.txt
    - git commit --amend --no-edit
    - git push origin main
```

## 🏆 K-4 (PUSH CON RAMA)
  Enviar un push con una rama:
```  
    - git branch nombre-de-la-rama
    - git branch
    - git switch nombre-de-la-rama-antes-creada
    - git add bat.txt
    - git commit -m "Commit para enviar la rama creada"
    - git push -u origin nombre-de-la-rama
```

## 🏆 K-5 (ELIMINAR RAMA REMOTA Y LOCAL)
 Ahora toca eliminar la rama remota antes enviada y la local:
 ``` 
    (remota): - git push origin --delete nombre-de-la-rama-enviada
    (local):  - git branch -d nombre-de-la-rama-local
```



---
<h3 align="center">SOCIAL OPLESK</h3>
