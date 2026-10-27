# srk-officetv-youtube

A single static page that loops the public **[@srk_honda](https://www.youtube.com/@srk_honda)**
YouTube uploads playlist with sound. It is shown inside the SRK Honda office-TV display app
(LG webOS) in an iframe, because YouTube embeds do not play from a packaged app's `file://` origin.

Served on GitHub Pages: **https://rmshc1.github.io/srk-officetv-youtube/**

No secrets, no tracking — it only embeds a public YouTube channel. The TV app can ask it to turn
the sound on via `postMessage({srk:'unmute'})`.
