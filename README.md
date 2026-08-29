<img width="800" height="750" alt="{2EDD9292-EBF4-4C78-9834-90CA78D404E8}" src="https://github.com/user-attachments/assets/96b68f5c-5c29-4a8c-8f0c-7740ab39a995" />





# LinTabSort 📸

A free Windows app that helps you actually get through that folder of unsorted photos.

Point it at a folder, breeze through tagging what to keep and what to bin, and let LinTabSort sort the rest into a tidy, dated folder structure for you. **No cloud, no account, no subscription — your photos never leave your computer.**

I built this for my own photo library, because I wanted a tool that was capable but simple, with no subscription attached.

## Get it

**[⬇ Download the latest version](../../releases/latest)**

Grab `LinTabSort.exe` and run it — no installer, nothing to set up. Windows 10 or 11.

> **Windows may show a blue "Windows protected your PC" screen.** This is normal for small independent apps that haven't paid for a code-signing certificate — it doesn't mean anything is wrong. Click **"More info"**, then **"Run anyway"** to continue.

## What it does

- 🔵 **Review** — flip through photos and videos fast, tag what you don't want with one click, undo with one more.
- 🩷 **Final Review** — a last safety check before anything is deleted, plus a one-click "I regret everything" undo.
- 🟢 **Sorting** — automatically files everything into dated folders, using the photo's real capture date so it's actually accurate.
- 🟣 **Find Duplicates** — hunts down exact duplicate photos and videos across folders, even renamed or moved ones, so you can clear the clutter with confidence. A status card shows every folder's review progress at a glance, so you always know what's left.
- 🌊 **Depth-aware photo filters & Parallax** — a local AI model estimates how near or far each part of a photo is, then applies ordinary effects (vignette, fog, color grade, grain, and more) by that real depth instead of flatly across the whole image — a vignette that only darkens the background, fog that thickens with real distance, and so on. The same depth map drives Parallax: pin a photo to a second screen and it drifts with a subtle, genuine 2.5D camera-move feel instead of a flat pan.
- 🟦 **Locations** — an interactive map of where your photos were taken, clustered so it's easy to browse, with optional place names and the option to see every location you've ever cached, not just the current folder.
- 🗓️ **Timeline** — a year-by-year sidebar to jump straight to any month or folder while reviewing.
- ℹ️ **Photo info** — date, camera, and shooting details at a glance for whatever you're looking at.
- 📱 **Phone import** — plug in an Android phone and copy your photos over. LinTabSort only ever *reads* from your phone — nothing on it is ever touched, moved, or deleted.
- ▶️ **Video playback** — play, pause, change speed, grab a still frame, right in the app.
- 🎨 **Photo filters and adjustments** — dozens of filters from classic effects to real image-processing techniques like CLAHE (auto contrast), Retinex (dehazing), and a Voronoi mosaic stained-glass look, plus exposure/contrast/shadows/highlights — all previewed live and saved without ever touching your original file.
- 🪄 **AI photo restoration & object removal** *(downloads a small model on first use, then fully offline)* — upscale, denoise, colorize, or erase an unwanted object right in the viewer (draw a box around it, one click to remove), each powered by a small AI model that downloads once and then runs completely on your own computer. **Your photos are never sent anywhere, at any time.**
- 🕰️ **Full edit history with one-click undo** — every filter, adjustment, restoration, and object removal you apply is remembered as its own step; a small thumbnail strip lets you jump back to any earlier point, discarding just the edits after it.
- 🖥️ **Pin to second screen** — pop a photo out onto another monitor while you keep browsing, with an optional auto-advancing slideshow.
- 🐸 **Busy frogs** — long operations get a swarm of hopping frogs instead of a boring spinner. Yes, really. You can turn it off if you're no fun.

## Privacy

By default, your photos and videos never leave your computer — everything runs locally, and no photo is ever sent to any network endpoint. AI photo restoration (upscale/denoise/colorize/object removal) and the depth-aware filters/Parallax both run entirely on your own computer — the only network activity either involves is a one-time download of the relevant model the first time you use it, after which everything runs fully offline. Maps, historical weather, and place names are also **off by default** and never turn on by themselves (Settings → Privacy). Once turned on: the Locations map fetches map tiles from OpenStreetMap; selecting a geotagged photo can look up that day's weather from Open-Meteo (free, no account); pausing on a geotagged photo or clicking the map can look up a place name from Nominatim/OpenStreetMap (free, no account). Each of these sends only the rounded location and/or date to that service — never your actual photo — same as any map website. Your photo *files* never leave the computer either way.

## Questions or feedback?

**Mikael Lindmark** — [lindmark.mikael@gmail.com](mailto:lindmark.mikael@gmail.com)

If LinTabSort saved you an afternoon of folder chaos, a [Ko-fi](https://ko-fi.com/lintabcrux) tip is always appreciated. ☕
