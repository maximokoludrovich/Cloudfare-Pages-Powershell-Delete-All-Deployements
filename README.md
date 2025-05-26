![image](https://github.com/user-attachments/assets/816be408-5591-4ff7-aaca-9aa34394b45c)

🧹 Auto Cleanup for Cloudflare Deployments
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
