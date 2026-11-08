# UniMate (web app)

Static single-page app (plain HTML, CSS, JavaScript). No build step, no dependencies.
Data is saved in the browser (localStorage), separately for each account.

## Deploy to Vercel

Option 1: GitHub
1. Create a new GitHub repository and upload these files (index.html, vercel.json).
2. In Vercel, choose Add New > Project, import the repository, leave every setting as default, click Deploy.

Option 2: Vercel CLI
1. npm i -g vercel
2. In this folder run: vercel --prod

Framework preset: "Other". Build command and output directory: leave empty.
