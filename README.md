# retroservices1121.github.io

GitHub Pages site for MOBI MEDIA, INC. apps.

- `/app-ads.txt`: AdMob authorized sellers file. It must stay at the domain root. Uncomment the line and add the real `pub-` ID.
- `/the-last-alibi/`: landing page, `/privacy/` and `/support/` for The Last Alibi.

Replace every `SUPPORT_EMAIL` placeholder with the real contact address: `grep -rl SUPPORT_EMAIL . | xargs sed -i 's/SUPPORT_EMAIL/you@example.com/g'`.
