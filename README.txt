Iftee Raiyan Portfolio — static deployment package

These files are the ready-to-deploy site. Keep index.html, 404.html, and the assets folder together at the project root.

Cloudflare Pages (Git-connected):
- Build command: leave blank
- Build output directory: .

GitHub push from the extracted folder (replace the URL with your new GitHub repository URL):
  git init
  git add .
  git commit -m "Deploy portfolio"
  git branch -M main
  git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
  git push -u origin main
