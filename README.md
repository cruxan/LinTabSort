<img width="800" height="750" alt="{2EDD9292-EBF4-4C78-9834-90CA78D404E8}" src="https://github.com/user-attachments/assets/96b68f5c-5c29-4a8c-8f0c-7740ab39a995" />





# LinTabSort 📸

A free Windows app that helps you actually get through that folder of unsorted photos.

Point it at a folder, breeze through tagging what to keep and what to bin, and let LinTabSort sort the rest into a tidy, dated folder structure for you. No cloud, no account, no subscription — just a fast desktop tool that respects your files.

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
- 🌊 **Depth-aware photo filters & Parallax** — a local AI model estimates how near or far each part of a photo is, then applies ordinary effects (vignette, fog, color grade, grain, and 40+ more) by that real depth instead of flatly across the whole image — a vignette that only darkens the background, fog that thickens with real distance, and so on. The same depth map drives Parallax: pin a photo to a second screen and it drifts with a subtle, genuine 2.5D camera-move feel instead of a flat pan.
- 🎭 **Dual filter** — apply two completely different filters to the same photo at once, split by depth: one look inside your chosen range, a different one outside it — a sharp, colorful subject against a moody, desaturated background, for example.
- 🖌️ **Style transfer** — repaint a photo with the brushwork and color palette of a painting, powered by a local AI model. 13 bundled presets (Van Gogh's Starry Night, Hokusai's Great Wave, a cyberpunk neon-street look, and more) or bring your own style image.
- 🟦 **Locations** — an interactive map of where your photos were taken, clustered so it's easy to browse, with optional place names and the option to see every location you've ever cached, not just the current folder.
- 🗓️ **Timeline** — a year-by-year sidebar to jump straight to any month or folder while reviewing.
- ℹ️ **Photo info** — date, camera, and shooting details at a glance for whatever you're looking at.
- 📊 **My Media** — a stats dashboard for your whole library: busiest shooting days on a GitHub-style heatmap, a camera/phone ownership timeline, "on this day" in past years, how this month compares to last year, and more, with most stats clickable straight through to the matching photos.
- 🙂 **People** — local, offline face recognition. LinTabSort finds and groups faces across your library automatically as you review, so photos of the same person collect together without you tagging a single one by hand. Add an optional birth date for anyone and matching gets noticeably smarter — it learns what that person actually looked like at each age, instead of blurring their whole life into one average, and can flag genuine lookalikes (the classic mixed-up-siblings problem) before you accidentally confirm the wrong one. Everything runs on your own computer — no photo or face data is ever sent anywhere. Can also pick up face names you already gave photos in Google's old Picasa, if you have any lying around.
- 🧵 **Weave of People** — pick anyone from the People tab and see a full-screen storyline of their whole life: a cord tracing their own timeline, splitting into a colored strand (with its own face thumbnail) every time someone else shares a confirmed photo with them, plus a photo-stream band of every solo photo along the same timeline, with birthday markers for anyone whose birth date you've added.
- 🖼️ **Face Morph "profile pic"** — open anyone in People and a small floating polaroid appears, continuously and smoothly blending between their own confirmed photos to show them growing and changing over time. Save the sequence as an animated GIF, reshuffle to a different set of photos, or tune the transition speed and style yourself.
- 📱 **Phone import** — plug in an Android phone and copy your photos over. LinTabSort only ever *reads* from your phone — nothing on it is ever touched, moved, or deleted.
- ▶️ **Video playback** — play, pause, change speed, grab a still frame, right in the app.
- 🎨 **Photo filters and adjustments** — dozens of filters from classic effects to real image-processing techniques like CLAHE (auto contrast), Retinex (dehazing), and a Voronoi mosaic stained-glass look, plus exposure/contrast/shadows/highlights — all previewed live and saved without ever touching your original file.
- 🪄 **AI photo restoration & object removal** *(downloads a small model on first use, then fully offline)* — upscale, denoise, colorize, or erase an unwanted object right in the viewer, either by drawing a box around it yourself or letting "Poof!" find every object in the photo automatically — click one and it's gone. Each powered by a small AI model that downloads once and then runs completely on your own computer. **Your photos are never sent anywhere, at any time.**
- 🔎 **Objects filter** — scans the photos you've currently got loaded and builds a menu of what's actually in them (people, animals, vehicles, and more), so you can filter down to "photos with a cat" in one click. Off by default, and results are saved and deletable per folder — same privacy model as People. A fun bonus feature, not a precise one: it can occasionally mix up a similar-looking object.
- 🕰️ **Full edit history with one-click undo** — every filter, adjustment, restoration, and object removal you apply is remembered as its own step; a small thumbnail strip lets you jump back to any earlier point, discarding just the edits after it.
- 🖥️ **Pin to second screen** — pop a photo out onto another monitor while you keep browsing, with an optional auto-advancing slideshow.
- 🐸 **Busy frogs** — long operations get a swarm of hopping frogs instead of a boring spinner. Yes, really. You can turn it off if you're no fun.

## Privacy

By default, your photos and videos never leave your computer — everything runs locally, and no photo is ever sent to any network endpoint. AI photo restoration (upscale/denoise/colorize/object removal), the depth-aware filters/Parallax, Style transfer, People (face recognition), and the Objects filter all run entirely on your own computer — the only network activity any of these involves is a one-time download of the relevant model the first time you use it, after which everything runs fully offline. Style transfer's model ships bundled with the app. People and Objects each ask before they scan a folder for the first time (and Objects also has its own separate on/off switch), and People asks again before using any old Picasa face tags it finds. Maps, historical weather, and place names are also **off by default** and never turn on by themselves (Settings → Privacy). Once turned on: the Locations map fetches map tiles from OpenStreetMap; selecting a geotagged photo can look up that day's weather from Open-Meteo (free, no account); pausing on a geotagged photo or clicking the map can look up a place name from Nominatim/OpenStreetMap (free, no account). Each of these sends only the rounded location and/or date to that service — never your actual photo — same as any map website. Your photo *files* never leave the computer either way.

## Questions or feedback?

**Mikael Lindmark** — [lindmark.mikael@gmail.com](mailto:lindmark.mikael@gmail.com)

If LinTabSort saved you an afternoon of folder chaos, a [Ko-fi](https://ko-fi.com/lintabcrux) tip is always appreciated. ☕
