# Pokédex básica (para práctica de refactor)

> Implementación deliberadamente simple y repetitiva (sin prepared statements, sin helpers, conexión duplicada) para usar en clase y luego refactorizar.

## Requisitos
- PHP 7+ con mysqli
- MySQL/MariaDB

## Instalación
1. Crear BD e importar `database.sql`.
2. Copiar el contenido del zip en el servidor (colocar la carpeta `imagenes` con permisos de escritura si se va a subir imágenes).
3. Usuario admin: `admin` / `admin`.

## Archivos
- index.php (listado + búsqueda)
- login.php / logout.php
- ver.php (detalle)
- nuevo.php (alta, requiere login)
- editar.php (modificación, requiere login)
- borrar.php (baja, requiere login)
- tipos/ (iconos de tipo)
- imagenes/ (placeholders y futuras subidas)
