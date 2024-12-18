Aquí tienes un ejemplo de archivo **README.md** para tu proyecto WordPress:

---

# FN - Flash News WordPress Theme

**Descripción del Proyecto:**  
"FN - Flash News" es un sitio WordPress que proporciona noticias organizadas por categorías como Deportes, Economía, Naturaleza, Política y Tecnología.

---

## 📂 Estructura del Proyecto
```
wordpress/
│
├── wp-admin/         # Archivos de administración de WordPress
├── wp-content/       # Contenido personalizado del sitio
│   ├── languages/    # Archivos de idioma
│   ├── plugins/      # Plugins instalados
│   └── themes/
│       └── blogrift/ # Tema personalizado
│           ├── css/        # Estilos CSS
│           ├── hooks/      # Hooks personalizados
│           ├── images/     # Imágenes del tema
│           ├── content.php # Contenido principal
│           ├── favicon.ico # Ícono del sitio
│           ├── functions.php # Funciones personalizadas
│           ├── header.php  # Cabecera del tema
│           ├── index.php   # Página principal del tema
│           ├── readme.txt  # Archivo de información adicional
│           └── style.css   # Estilos generales del tema
└── wp-includes/      # Archivos de soporte de WordPress
```

---

## 📰 Categorías de Noticias
El sitio organiza las noticias en las siguientes categorías:
1. **Deportes:** Noticias sobre eventos y actividades deportivas.
2. **Economía:** Información sobre la economía global.
3. **Naturaleza:** Artículos sobre el medio ambiente y la naturaleza.
4. **Política:** Actualizaciones de la política mundial.
5. **Tecnología:** Noticias sobre innovación y tecnología.

---

## 🚀 Instalación
1. Descarga y copia la carpeta del tema `blogrift` en `wp-content/themes/`.
2. Activa el tema desde el panel de administración de WordPress.
3. Asegúrate de tener las siguientes dependencias configuradas:
   - **PHP 7.4+**
   - **WordPress 6.7.1**

---

## 🖼️ Personalización
- **Favicon:**  
   Asegúrate de que el archivo `favicon.ico` está ubicado en `wp-content/themes/blogrift/`.  
   Modifica la línea en `header.php` si es necesario:
   ```php
   <link rel="icon" type="image/x-icon" href="<?php echo get_template_directory_uri(); ?>/favicon.ico">
   ```
- **Estilos CSS:**  
   Personaliza la apariencia en `style.css` o en archivos CSS adicionales ubicados en la carpeta `css/`.

---

## ✍️ Contribuciones
Las contribuciones son bienvenidas. Por favor, abre un *Pull Request* o crea un *Issue* si encuentras algún problema.

---

## 📧 Contacto
Autor: **39009471**  
Email: **eferreirac01@educantabria.es**  

---

Este README proporciona una guía básica para configurar y utilizar el proyecto **FN - Flash News** en WordPress.