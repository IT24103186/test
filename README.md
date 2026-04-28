git init
git add .
git commit -m "MERNAPP"
git remote add origin <repolink>
git branch -M main
git push -u origin main

chmod +x node_modules/.bin/vite && npm run build
