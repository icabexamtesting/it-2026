ICAB INFORMATION TECHNOLOGY 2026 — READY-TO-HOST WEBSITE
====================================================

WHAT IS INCLUDED
  index.html             Main website. Contains all 4,000 questions and all styles/scripts.
  favicon.svg            Website icon.
  site.webmanifest       Mobile home-screen / app information.
  service-worker.js      Optional offline cache after the first online visit.
  .nojekyll              GitHub Pages compatibility.

HOW TO PUBLISH
1. Extract the ZIP archive to your computer.
2. Upload ALL FILES INSIDE this folder to the document root of your website.
   The file index.html must be inside the folder you want visitors to open.
3. Open your website URL in a browser; e.g., https://your-domain.example/

Common platforms:
  - cPanel / shared hosting: Upload and extract these files into public_html/
    (or into public_html/quiz/ for https://your-domain.example/quiz/).
  - Netlify Drop: Drag the extracted website folder into Netlify Drop.
  - Vercel: Deploy this folder as a static site without any build command.
  - GitHub Pages: Upload these files to the repository publishing root,
    then enable GitHub Pages for that branch/folder.
  - Cloudflare Pages: Upload the folder via Direct Upload.

DETAILS
  - Four chapters, 1,000 questions each, with 20 model tests per chapter.
  - Each test: 50 questions, 90-minute time limit, instant explanations.
  - Practice mode, topic filters, score review and progress saving.
  - No PHP, Node.js, Python, database, API key, or build process required.
  - HTTPS recommended for best offline caching and home-screen app support.
  - The site works without the service worker when online, and index.html
    can be opened directly as a file for fully offline single-device use.
  - Progress is saved per browser/device using localStorage; it is NOT
    synchronized between devices or saved to your hosting account.
  - Static site timers are for self-practice, not secure proctored exams.
  - If you replace the site later, keep the same website domain/path and
    avoid clearing browser site data to retain saved attempts.
  - Independent ICAB-style questions based on the user-supplied 2026 book.
    This is not an official ICAB exam portal.

IMPORTANT
  Host only material you have the rights or permission to publish.
  The website does not upload candidate answers or store personal data
  on a server. Check your hosting provider's separate logging and analytics.
