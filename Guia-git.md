# Guía Git: Conectar proyecto con GitHub

## 2. Configurar nombre y correo

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@ejemplo.com"
```

## 3. Conectar tu proyecto con GitHub

```bash
# Inicializar Git en tu carpeta
git init

# Conectar con repositorio de GitHub (crea el repo en GitHub primero)
git remote add origin https://github.com/tu-usuario/tu-repo.git

# Agregar todos los archivos
git add .

# Hacer commit
git commit -m "Primer commit"

# Cambiar rama a main
git branch -M main

# Subir a GitHub
git push -u origin main
```

## 4. Subir cambios posteriores

```bash
git add .
git commit -am "descripción de cambios"
git push
```

---

## Nota importante sobre autenticación

La primera vez que hagas `git push`, GitHub te pedirá usuario y contraseña. 

**Como contraseña debes usar un Token de acceso personal:**
1. Ve a: https://github.com/settings/tokens
2. Click en "Generate new token (classic)"
3. Selecciona el permiso `repo`
4. Copia el token generado
5. Úsalo como contraseña cuando Git te lo pida

## Comandos básicos de referencia

```bash
git status              # Ver estado de archivos
git add .               # Agregar todos los cambios
git commit -m "msg"     # Guardar cambios con mensaje
git push                # Subir cambios a GitHub
git pull                # Descargar cambios de GitHub
git log                 # Ver historial de commits
```