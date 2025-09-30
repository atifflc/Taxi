Download freetaxi_site.zip, extract and you'll have index.html.
Quick deploy options:
1) GitHub Pages:
   - Create a new GitHub repo, add index.html to root, commit & push.
   - In repo Settings > Pages, set source to main branch root (or create gh-pages branch).
   - Your site will be available at https://<your-username>.github.io/<repo-name> within a few minutes.

2) Netlify (drag & drop):
   - Go to netlify.com, sign up, and drag the extracted folder (or zip) onto the 'Sites' dashboard.
   - Netlify will host at a public netlify.app URL.

3) Vercel:
   - Create a new project, import from GitHub or drag folder. Vercel auto-deploys static sites.

4) Firebase Hosting:
   - Install Firebase CLI and run: firebase init hosting; place index.html in public/; firebase deploy

After hosting, copy the public URL and reply to the Google Cloud email with:
 - Public URL
 - Technical POC (name, email, LinkedIn)
 - Short one-line proof (e.g., link to press PDF or donor page)

If you want, tell me which deploy option you prefer and I will give exact step-by-step commands for your platform.
