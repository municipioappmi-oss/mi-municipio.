MI MUNICIPIO — PROTOTIPO WEB INTERACTIVO

Contenido
- index.html: prototipo ejecutable en un navegador moderno, sin instalar dependencias.

Cómo abrirlo
1. Descarga y extrae el archivo ZIP.
2. Abre index.html en Chrome, Edge o Firefox.
3. La aplicación ciudadana es de acceso libre. Para acceder al panel del personal, pulsa “Acceso institucional”.
4. Selecciona el tipo de acceso y escribe usuario y contraseña.

Credenciales de demostración
- Administrador: usuario admin · contraseña Admin2026!
- Obras Públicas: usuario jperez · contraseña Obras2026!
- Servicios Públicos Municipales: usuario alopez · contraseña Servicios2026!
- Agua Potable y Alcantarillado: usuario cruiz · contraseña Agua2026!

También se puede entrar con el correo institucional en vez del nombre de usuario. Desde el panel administrativo, en “Usuarios y permisos”, se pueden crear cuentas nuevas y asignarles usuario, contraseña, rol y dependencia.

Funciones de demostración
- Crear reportes con categoría, descripción, ubicación, fotografía y folio automático.
- Obtener coordenadas mediante la API de geolocalización del navegador (requiere permiso y un contexto seguro; localhost suele funcionar).
- Consultar el estado de un reporte por folio.
- Panel de dependencia para actualizar el estado de los reportes de su área y registrar anotaciones públicas o internas.
- Panel de administración para consultar reportes, dependencias, usuarios, reglas de asignación, estadísticas y auditoría.
- Exportación imprimible: los botones de PDF abren el diálogo de impresión del navegador. Elige “Guardar como PDF”.
- Guardado local en el navegador con localStorage.
- Identidad visual con emblema municipal y la leyenda “H. Ayuntamiento de San Juan de los Lagos”.

Importante antes de publicar
Este prototipo todavía no es una plataforma de producción. La autenticación de demostración compara las contraseñas en JavaScript y los datos se guardan únicamente en el navegador; no constituye seguridad real. No existe base de datos central, gestión segura de sesiones ni permisos en el servidor. No uses contraseñas reales. Antes de operar con personal y ciudadanía, integrar un backend, almacenamiento seguro de contraseñas (hash robusto), autenticación de servidor, sesiones, autorización por rol y dependencia, almacenamiento privado de imágenes, auditoría del servidor, respaldos y un proveedor cartográfico real. Las cifras y reportes de ejemplo son ficticios.


IDENTIDAD MUNICIPAL
- Se integró el escudo oficial proporcionado para el H. Ayuntamiento de San Juan de los Lagos en el encabezado institucional y los documentos imprimibles.
- Archivo incluido: escudo_oficial_san_juan_de_los_lagos.png. La imagen también está incrustada en index.html para que se muestre al abrir directamente el archivo.
