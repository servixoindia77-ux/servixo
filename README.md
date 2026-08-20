# Servixo — Website Package

Files included:
- index.html (main site)
- manifest.json
- README.md

How to create a ZIP (local):
1. Put all files into a folder named `servixo-site`.
2. On macOS / Linux:
   zip -r servixo-site.zip servixo-site
   On Windows (PowerShell):
   Compress-Archive -Path servixo-site -DestinationPath servixo-site.zip

Deploy options:
1. GitHub Pages
   - Push the `site-deploy` branch (or merge to your default branch) and then in repo Settings -> Pages select the branch and publish.
   - Suggested Pages URL: https://servixoindia77-ux.github.io/servixo
2. Netlify
   - Create an account at netlify.com, drag-and-drop the ZIP or connect your GitHub repo.
   - Netlify will serve `/index.html` automatically.
3. Vercel
   - Create a project, import from GitHub or drag the folder; choose static site.

Next steps I performed for you:
- Created branch `site-deploy` in your repository.
- Added `index.html` (clean, responsive landing page), `manifest.json`, and this `README.md` to the `site-deploy` branch.

What you should do next to publish (two options):

A) Publish via GitHub Pages (recommended, you keep full control):
1. Go to your repository on GitHub -> Settings -> Pages.
2. Under "Source", select branch `site-deploy` and folder `/ (root)`, then Save.
3. After a minute, GitHub will show the live URL (likely https://servixoindia77-ux.github.io/servixo).

B) Merge to your default branch (if you want the site on your main branch):
1. Create a Pull Request from `site-deploy` into your default branch and merge it.
2. Enable Pages from that branch or keep as-is.

If you want, I can also:
- Create the Pull Request for you from `site-deploy` into the default branch.
- Try to enable Pages (I cannot change repository settings without explicit extra API/permission — if you want I can provide exact curl/steps or do it if you give me permission).

If you want me to proceed further (create PR / open Pages / add custom domain), reply with the option you prefer.
