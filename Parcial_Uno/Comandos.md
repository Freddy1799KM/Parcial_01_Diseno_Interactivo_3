# Guía Rápida de Git

### 1. Guardar tus avances locales (El flujo diario)
Cada vez que hagas un cambio importante en tus archivos de diseño o código, ejecuta estos tres comandos en orden:

* **`git status`**
  Muestra qué archivos has modificado o creado. Te sirve para revisar antes de guardar.
* **`git add .`**
  Prepara todos tus cambios para ser guardados (el punto significa "todo").
* **`git commit -m "Explicación breve de lo que hiciste"`**
  Guarda tus cambios localmente con un mensaje. Intenta que sea descriptivo (ej. "Ajuste de colores en el banner").

---

### 2. Enviar tus cambios a GitHub (Subir la entrega)
Cuando quieras que tus cambios se vean reflejados en internet para que tu profesor los vea:

* **`git push origin main`**
  Sube todos tus commits guardados a tu repositorio de GitHub. 
  *(Nota: Si tu rama principal se llama `master` en lugar de `main`, usa `git push origin master`).*

---

### 3. Traer cambios desde GitHub (Actualizar)
Si llegas a modificar algo desde la página web de GitHub o trabajas desde otra computadora:

* **`git pull origin main`**
  Descarga e integra los cambios más recientes que estén en internet a tu computadora.

---

### 4. En caso de emergencia (¿Algo se rompió?)
Si hiciste un cambio que arruinó el diseño y quieres volver exactamente al estado de tu último commit guardado:

* **`git checkout .`**
  Borra todos los cambios locales que no hayas guardado en un commit y te devuelve a la última versión limpia.
