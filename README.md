# 👋 ¡Hola, soy Daniel, bienvenido a mi perfil de GitHub!

## 🚀 Sobre mí
Soy un estudiante apasionado de **Desarrollo de Aplicaciones Multiplataforma (DAM)** con experiencia en:

- **Java** ☕
- **HTML** 🌐
- **CSS** 🎨
- **Git y GitHub** 🌟

Actualmente, estoy profundizando en **Java** y explorando nuevas tecnologías relacionadas con la programación. Mi objetivo es construir soluciones innovadoras que combinen funcionalidad y diseño.

---

## 🛠️ Tecnologías y herramientas

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)

---

## 🌟 Formación
- 🎓 **FP Grado Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)**
- 🏅 **Certificación en Git y GitHub**

---

## ✨ Frase que me define
> "La programación no es solo código, es creatividad transformada en soluciones." ✨

---

## 📫 Cómo contactarme
¡No dudes en enviarme un mensaje si quieres colaborar o intercambiar ideas!


# Guía rápida de Git y GitHub  

Esta guía está diseñada para todos los niveles. Contiene comandos esenciales y avanzados explicados de manera sencilla, con ejemplos prácticos y consejos útiles para evitar errores comunes.  

---

## 1. Configuración inicial  

Configurar nombre de usuario y correo electrónico:  
```bash
git config --global user.name "TuNombre"  
git config --global user.email "TuCorreo@example.com"  
```  
Verificar la configuración actual:  
```bash
git config --list  
```  

> **Consejo:** Usa configuraciones específicas para repositorios con `git config user.name` (sin `--global`).  

---

## 2. Crear o clonar un repositorio  

Inicializar un nuevo repositorio en la carpeta actual:  
```bash
git init  
```  

Clonar un repositorio remoto:  
```bash
git clone URL_DEL_REPOSITORIO  
```  
> **Sugerencia:** Añade un nombre personalizado para la carpeta al clonar:  
```bash
git clone URL_DEL_REPOSITORIO NUEVA_CARPETA  
```  

---

## 3. Añadir y guardar cambios  

Ver el estado actual del repositorio:  
```bash
git status  
```  

Añadir archivos al área de preparación:  
```bash
git add NOMBRE_DEL_ARCHIVO  
git add .  # Añadir todos los cambios  
```  

Hacer un commit con un mensaje descriptivo:  
```bash
git commit -m "Descripción breve y clara del cambio"  
```  

> **Consejo:** Usa `git commit -am "Mensaje"` para añadir y hacer commit de cambios en archivos ya versionados.  

---

## 4. Trabajar con ramas  

Crear una nueva rama:  
```bash
git branch NOMBRE_DE_LA_RAMA  
```  

Cambiar a otra rama:  
```bash
git switch NOMBRE_DE_LA_RAMA  
# O también:  
git checkout NOMBRE_DE_LA_RAMA  
```  

Crear y cambiar a una nueva rama en un solo paso:  
```bash
git switch -c NOMBRE_DE_LA_RAMA  
```  

Listar todas las ramas:  
```bash
git branch  
```  

Fusionar una rama con la actual:  
```bash
git merge NOMBRE_DE_LA_RAMA  
```  

> **Sugerencia:** Borra una rama que ya no necesites:  
```bash
git branch -d NOMBRE_DE_LA_RAMA  
```  

---

## 5. Sincronizar con un repositorio remoto  

Añadir un repositorio remoto:  
```bash
git remote add origin URL_DEL_REPOSITORIO  
```  

Subir cambios al repositorio remoto:  
```bash
git push origin NOMBRE_DE_LA_RAMA  
```  

Descargar cambios del repositorio remoto:  
```bash
git pull origin NOMBRE_DE_LA_RAMA  
```  

> **Consejo:** Usa `git fetch` para descargar cambios sin fusionarlos automáticamente.  

---

## 6. Resolver conflictos  

Ver archivos en conflicto después de un merge:  
```bash
git status  
```  

Editar los archivos en conflicto, decidir los cambios y añadirlos:  
```bash
git add ARCHIVO  
git commit -m "Conflictos resueltos"  
```  

> **Sugerencia:** Usa herramientas gráficas como VS Code para resolver conflictos más fácilmente.  

---

## 7. Historial y revisión  

Ver el historial de commits:  
```bash
git log  
```  

Ver un historial más compacto:  
```bash
git log --oneline  
```  

Ver cambios realizados en un archivo específico:  
```bash
git diff NOMBRE_DEL_ARCHIVO  
```  

> **Consejo:** Usa `git diff HEAD` para comparar los cambios en todo el proyecto con el último commit.  

---

## 8. Comandos avanzados  

Deshacer un commit (manteniendo los cambios):  
```bash
git reset --soft HEAD~1  
```  

Eliminar los cambios locales sin afectar al historial:  
```bash
git checkout .  
```  

Eliminar el último commit permanentemente:  
```bash
git reset --hard HEAD~1  
```  

> **Advertencia:** Usa `--hard` con precaución, ya que elimina los cambios no guardados.  

---

## 9. Consejos y errores comunes  

- **Usa ramas:** Trabaja siempre en una rama diferente a `main` para evitar problemas.  
- **Sincroniza a menudo:** Realiza `git pull` regularmente si trabajas en equipo.  
- **Escribe buenos mensajes de commit:** Detalla qué cambiaste y por qué.  

> **Errores comunes:**  
> - Olvidar hacer `git add` antes de un commit.  
> - Intentar fusionar ramas sin haber guardado cambios locales.  

