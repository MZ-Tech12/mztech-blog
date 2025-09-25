
MZ Tech - Netlify CMS demo site
--------------------------------

This project is a static site with Netlify CMS integrated via Git Gateway.
Steps to use (short):

1. Push these files to a GitHub repository (root must contain index.html).
2. On Netlify: "Add new site" -> Import from GitHub -> select this repository.
3. In Netlify site settings: enable Identity (Netlify Identity) and then enable Git Gateway.
4. Visit /admin on your deployed site, login with GitHub (or invite users), and create posts.
5. Netlify CMS will save new posts to the `posts_markdown` folder in your repo.

Notes:
- You must authorize Netlify to access your GitHub repo when connecting.
- If you prefer manual deploys, upload the built files via drag & drop in Deploys.
