# Actividad 04: Trabajo colaborativo en GitHub

## Integrantes
- Gianella Alexandra Ramos Ticahuanca
- Aderly Aldair Huillca Monterola
- Angie Zulema Velarde Centeno
- Jesus Alberto Quispe Quenta

## Docente
MGT. ING. Erick Alcca Zela

## Curso
Análisis y Diseño de Sistemas de Información II

## Objetivo
El objetivo de esta actividad fue aprender a utilizar GitHub de manera colaborativa, creando un repositorio, realizando commits y resolviendo conflictos de código.

## Pasos seguidos

### 1. Formación de equipos
Se formó un equipo de 4 integrantes.

### 2. Creación del repositorio
Uno de los miembros del equipo creó un repositorio en GitHub y lo compartió con los demás integrantes mediante invitaciones.

### 3. Clonación del repositorio
Cada miembro del equipo clonó el repositorio en su máquina local usando el siguiente comando:
```bash
git clone <URL_DEL_REPOSITORIO>
```

### 4. Realización de commits colaborativos
Cada miembro del equipo realizó al menos 2 commits con cambios significativos, como la adición de archivos o modificaciones de código. Ejemplo:
```bash
git add nombre_archivo.py
git commit -m "Agregué la función de resta"
git push origin main
```

### 5. Resolución de conflictos
Para generar un conflicto intencional, dos miembros del equipo editaron la misma línea de código en archivos diferentes y realizaron un commit. Luego, al hacer `git pull`, se generó un conflicto. 

Para resolver el conflicto, se siguieron estos pasos:
1. Se identificó el conflicto en el archivo afectado.
2. Se editó manualmente el archivo para integrar los cambios.
3. Se usó el siguiente comando para marcar el conflicto como resuelto:
   ```bash
   git add nombre_archivo.py
   ```
4. Se realizó un nuevo commit con la resolución del conflicto:
   ```bash
   git commit -m "Conflicto resuelto en nombre_archivo.py"
   ```
5. Finalmente, se subieron los cambios al repositorio remoto:
   ```bash
   git push origin main
   ```

### 6. Subida de cambios finales
Después de resolver los conflictos, todos los miembros del equipo realizaron un `git pull` para asegurarse de tener la versión actualizada del repositorio.

### 7. Conclusión
Esta actividad nos permitió reforzar el uso de GitHub para trabajo colaborativo, practicar la gestión de versiones y aprender a resolver conflictos en el código.
