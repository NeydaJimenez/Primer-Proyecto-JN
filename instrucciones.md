# Creando tu cuenta y tu primer repositorio  

## Paso 1: Crea tu cuenta de GitHub  

1. Ve al sitio web: Abre tu navegador y visita [GitHub.com](https://github.com/).  
2. Regístrate: Busca y haz clic en el botón **"Sign up"** o **"Registrarse"**.  
3. Completa la información: Te pedirá un correo electrónico, una contraseña y un nombre de usuario.  
   - Elige un nombre de usuario profesional porque será público y te representará en la comunidad de desarrolladores.  
4. Verifica tu cuenta siguiendo las instrucciones para confirmar tu correo electrónico.  

## Paso 2: Instala y configura Git en tu computadora  

1. Descarga Git desde [git-scm.com/downloads](https://git-scm.com/downloads).  
2. Instala Git ejecutando el instalador y dejando las opciones predeterminadas.  
3. Configura tu identidad en Git ejecutando en la Terminal:  

   ```bash
   git config --global user.name "Tu Nombre Completo"
   git config --global user.email "tu.email@ejemplo.com"
   ```

4. Verifica la configuración:  

   ```bash
   git config --global --list
   ```

## Paso 3: Crea tu primer repositorio en GitHub  

1. Inicia sesión en tu cuenta de GitHub.  
2. Crea un nuevo repositorio desde el botón **+** en la esquina superior derecha.  
3. Completa los detalles:  
   - **Repository name**: Ejemplo `mi-primer-proyecto-prepa`.  
   - **Description (optional)**: Una breve descripción de tu proyecto.  
   - **Public/Private**: Selecciona según prefieras.  
   - **Initialize this repository with**: Marca la casilla **"Add a README file"**.  
4. Haz clic en **"Create repository"**.  
5. Modifica el archivo `README.md` agregando tus datos generales y una foto en formato Markdown.  
6. Crea un archivo `instrucciones.md` con esta información en formato Markdown.  

## Paso 4: Clona tu repositorio en tu computadora  

1. En tu repositorio en GitHub, haz clic en el botón verde **"Code"**.  
2. Copia la URL HTTPS.  
3. En la Terminal navega a la carpeta donde guardarás tus proyectos:  

   ```bash
   cd Documents/Projects
   ```

4. Clona el repositorio:  

   ```bash
   git clone [URL_DEL_REPOSITORIO]
   ```

   Ejemplo:  

   ```bash
   git clone https://github.com/tu-usuario/mi-primer-proyecto-prepa.git
   ```

5. Entra a la carpeta del proyecto:  

   ```bash
   cd mi-primer-proyecto-prepa
   ```

## Conceptos clave  

- **Repositorio (repo)**: Donde se guarda tu proyecto en local y en GitHub.  
- **Rama (branch)**: Línea principal de desarrollo, usualmente `main`.  
- **Commit**: Una fotografía de tus cambios en un momento dado.  
- **Clonar (clone)**: Descargar una copia de un repositorio remoto.  
- **Push**: Enviar cambios desde tu repositorio local a GitHub.  
- **Pull**: Recibir los cambios más recientes de GitHub a tu repositorio local.  
- **README.md**: Archivo que describe tu proyecto, escrito en Markdown.  
- **.gitignore**: Archivo que lista qué archivos o carpetas Git debe ignorar.  
