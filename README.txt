INSTRUCCIONES RÁPIDAS – Dashboard Comercial (lista para subir)

CONTENIDO
- index.html  → el dashboard
- /data/datos.csv  → tus datos (puedes reemplazar este archivo con la versión nueva)

CÓMO PUBLICAR (opción A – GitHub Pages; gratis)
1) Crea una cuenta en GitHub (si no tienes).
2) Crea un repositorio llamado, por ejemplo, comercial-dashboard.
3) Sube (drag & drop) la carpeta completa: index.html y la carpeta /data.
4) Activa GitHub Pages en Settings → Pages → Source: Deploy from a branch → main /(root).
5) Abre el link público que te entrega GitHub Pages. Verás el dashboard y, al cargar, buscará /data/datos.csv automáticamente.

CÓMO PUBLICAR (opción B – Netlify; muy simple)
1) Entra a Netlify y usa "Deploy a site" → "Import an existing project" (desde Git) o "Drag & Drop" (sube la carpeta).
2) Una vez desplegado, abre la URL que Netlify te da.

CÓMO ACTUALIZAR DATOS
- Reemplaza /data/datos.csv por la versión nueva (mismo nombre).
- Refresca la página (Ctrl/Cmd+R). El dashboard leerá la nueva data.

NOTAS
- Si la carga automática fallara, puedes usar el botón "Cargar CSV" dentro del dashboard para seleccionar el archivo manualmente.
- Evita cambiar el nombre del archivo (datos.csv) o su ubicación. Si lo haces, edita el index.html y cambia la variable AUTO_URL.
- Si vas a compartir el dashboard de forma privada, considera proteger la URL con contraseña (Netlify) o usar un control de acceso.

SOPORTE RÁPIDO
- Si no ves datos: revisa que /data/datos.csv exista en el hosting y refresca con Ctrl+F5.
- Si el CSV tiene nuevas columnas/nombres: asegúrate de mantener los encabezados requeridos por tu template original (Periodo, Semana, Ejecutivo, TeamLeader, etc.).