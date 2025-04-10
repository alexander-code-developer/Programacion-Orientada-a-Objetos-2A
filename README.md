# **📚 Guía Completa para Estudiantes: Cómo Entregar Tareas en GitHub Classroom**  

¡Hola, estudiantes! 👋 Esta guía les explicará paso a paso cómo **entregar sus tareas** asignadas en **GitHub Classroom**. Sigan estos pasos cuidadosamente para asegurarse de que sus trabajos sean enviados correctamente.  

---

## **📌 Paso 1: Aceptar la asignación en GitHub Classroom**  
1. **Haz clic en el enlace de invitación** que el profesor les haya proporcionado (por correo o plataforma de clases).  
2. **Inicia sesión** en tu cuenta de GitHub (si no tienes una, créala primero).  
3. **Acepta la tarea** haciendo clic en el botón verde **"Accept this assignment"**.  
4. Espera a que GitHub cree tu repositorio personal (puede tardar unos segundos).  

✅ **Verificación**:  
   - Deberías ver un mensaje como: *"Your assignment repository has been created"* con un enlace a tu repositorio personal.  

---

## **📂 Paso 2: Clonar el repositorio en tu computadora**  
Antes de trabajar, debes **descargar el repositorio** a tu equipo:  

### **Opción A: Usando GitHub Desktop (recomendado para principiantes)**  
1. Descarga e instala [GitHub Desktop](https://desktop.github.com/).  
2. Inicia sesión con tu cuenta de GitHub.  
3. Haz clic en **"Clone a repository"** y selecciona tu repositorio de la tarea.  
4. Elige una carpeta en tu PC y haz clic en **"Clone"**.  

### **Opción B: Usando Git por línea de comandos**  
1. Abre **Git Bash** (Windows) o **Terminal** (Mac/Linux).  
2. Ejecuta:  
   ```bash
   git clone https://github.com/[NOMBRE-DEL-CURSO]/[TU-REPOSITORIO].git
   ```
   (Reemplaza la URL con la de tu repositorio).  
3. Entra a la carpeta del proyecto:  
   ```bash
   cd nombre-del-repositorio
   ```

---

## **✏️ Paso 3: Trabajar en la tarea y guardar cambios**  
1. Abre la carpeta del proyecto en tu editor de código (VS Code, PyCharm, etc.).  
2. **Edita los archivos** necesarios según las instrucciones de la tarea.  
3. **Guarda los cambios** (Ctrl+S / Cmd+S).  

---

## **⬆️ Paso 4: Subir los cambios a GitHub (Git Commit & Push)**  
### **Con GitHub Desktop:**  
1. Abre GitHub Desktop.  
2. Verás los cambios pendientes en la pestaña **"Changes"**.  
3. Escribe un **mensaje descriptivo** (ej: "Agregué ejercicio 1").  
4. Haz clic en **"Commit to main"** y luego en **"Push origin"**.  

### **Con Git Bash/Terminal:**  
1. Verifica los cambios realizados:  
   ```bash
   git status
   ```
2. Agrega los archivos modificados:  
   ```bash
   git add .
   ```
3. Guarda los cambios con un mensaje:  
   ```bash
   git commit -m "Mi entrega de la tarea"
   ```
4. Sube los cambios a GitHub:  
   ```bash
   git push origin main
   ```

---

## **✅ Paso 5: Verificar que la entrega se haya registrado**  
1. **Entra a tu repositorio en GitHub** (el enlace que te llegó al aceptar la tarea).  
2. **Confirma que los últimos cambios aparezcan** en la sección de archivos.  
3. **Revisa la fecha de la última actualización** para asegurarte de que no haya errores.  

⚠️ **Importante:**  
- **La hora de entrega se registrará automáticamente** según el último `git push`.  
- **Si el profesor usa autocalificación**, asegúrate de seguir exactamente las instrucciones.  

---

## **❓ Preguntas frecuentes (FAQ)**  

### **🔹 ¿Qué pasa si me equivoqué y quiero corregir algo?**  
Puedes hacer nuevos cambios, repetir `git add`, `git commit` y `git push`. GitHub actualizará automáticamente tu repositorio.  

### **🔹 ¿Cómo sé si mi tarea fue recibida?**  
- Revisa el historial de commits en tu repositorio.  
- Si el profesor usa **GitHub Classroom con autochecks**, verifica si hay una ✔️ o ❌ en la pestaña **"Actions"**.  

### **🔹 ¿Qué hago si GitHub me da un error al hacer `git push`?**  
1. Asegúrate de estar conectado a Internet.  
2. Verifica que estés en la rama correcta (`git branch` debe mostrar `main`).  
3. Si hay conflictos, ejecuta:  
   ```bash
   git pull origin main
   ```
   (Sincroniza cambios antes de volver a intentar).  

---

## **📅 Recordatorio final**  
⏰ **¡No esperes hasta el último minuto!** GitHub registra la hora exacta de tu `git push`, así que envía tu trabajo con tiempo.  

🚀 **¡Listo!** Ahora sabes cómo entregar tus tareas en GitHub Classroom sin problemas. Si tienes dudas, consulta con tu profesor.  

---
