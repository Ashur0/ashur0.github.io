# Adding project screenshots

The Play cards show placeholder tiles. To use a real image:

1. Drop a PNG/JPG in this folder, e.g. `neon-sanction.png` (ideally 16:10, ~1200px wide).
2. In `index.html`, find the matching placeholder, e.g.
   `<div class="shot"><span>screenshot → neon-sanction.png</span></div>`
   and replace it with:
   `<div class="shot"><img src="neon-sanction.png" alt="Neon Sanction gameplay"></div>`
3. Commit + push: `git add -A && git commit -m "add screenshots" && git push`

Expected filenames referenced on the page:
neon-sanction.png · gait-lab.png · garak-demo.png · portfolio.png
