![image](https://github.com/user-attachments/assets/816be408-5591-4ff7-aaca-9aa34394b45c)

Cloudflare Deployment Cleanup Script
🧹 Limpieza automática de despliegues en Cloudflare (ES)
Este script elimina despliegues antiguos en Cloudflare Pages automáticamente.
✅ Requisitos:
- Un token de API de Cloudflare con permisos para:
  - Editar Pages deployments
  - Editar Workers scripts
- Variables de entorno configuradas correctamente.
▶️ Instrucciones:
1. Coloca los dos archivos descargados en una carpeta.
2. Abre PowerShell como Administrador.
3. Usa cd para ir a la carpeta.
4. Ejecuta:
node manageDeployments.js
El script conectará con Cloudflare y limpiará los despliegues viejos.
🧹 Auto Cleanup for Cloudflare Deployments (EN)
This script automatically deletes old deployments from Cloudflare Pages.
✅ Requirements:
- A Cloudflare API token with permissions to:
  - Edit Pages deployments
  - Edit Workers scripts
- Environment variables set up correctly.
▶️ Steps:
1. Place the two downloaded files in a folder.
2. Open PowerShell as Administrator.
3. Use cd to go to the folder.
4. Run:
node manageDeployments.js
The script will connect to Cloudflare and clean up old deployments.
