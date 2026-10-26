# Musicians Warehouse website

A static one-page site (HTML + CSS, no build step), made by Simply Art Creative.
Open `index.html` in a browser to preview.

## Still to fill in before launch
- WhatsApp: +263 77 676 7372 (set as `WHATSAPP` near the bottom of index.html).
- Hours: Monday – Saturday, 9am – 5pm.
- Confirm the client is happy with the gear categories and brand names shown.

## Free hosting (GitHub Pages)
1. Create a **public** repo `musicians-warehouse` on GitHub (nothing ticked).
2. In Terminal:
   ```
   cd ~/Projects/musicians-warehouse
   git init -b main && git add . && git commit -m "Musicians Warehouse site v1"
   git remote add origin git@github.com:thefirstbornTino/musicians-warehouse.git
   git push -u origin main
   ```
3. On GitHub: repo → Settings → Pages → Source "Deploy from a branch" → `main` / `(root)` → Save.
4. After about a minute it's live at https://thefirstborntino.github.io/musicians-warehouse/

To update later: edit, then `git commit -am "message" && git push`.
A custom domain (or the client's Wix domain) can be pointed at it later under Settings → Pages.
