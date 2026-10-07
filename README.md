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

- 🔵 **Review** — flip through photos and videos fast, tag what you don't want with one click, undo with one more. Hover a video or GIF tile for a moment and it plays right inside its own thumbnail, sampling moments across the whole clip so a long video is recognisable at a glance.
- 🩷 **Final Review** — a last safety check before anything is deleted, plus a one-click "I regret everything" undo.
- 🟢 **Sorting** — automatically files everything into dated folders, using the photo's real capture date so it's actually accurate.
- 🟣 **Find Duplicates** — hunts down exact duplicate photos and videos across folders, even renamed or moved ones, so you can clear the clutter with confidence. A status card shows every folder's review progress at a glance, so you always know what's left.
- 🌊 **Depth-aware photo filters & Parallax** — a local AI model estimates how near or far each part of a photo is, then applies ordinary effects (vignette, fog, color grade, grain, and 40+ more) by that real depth instead of flatly across the whole image — a vignette that only darkens the background, fog that thickens with real distance, and so on. A "Face relief" depth source adds fine facial structure (nose ridge, eye sockets, cheekbones) for a portrait, alongside the general scene-depth option. The same depth map drives Parallax: pin a photo to a second screen and it drifts with a subtle, genuine 2.5D camera-move feel instead of a flat pan.
- 🎭 **Dual filter** — apply two completely different filters to the same photo at once, split by depth: one look inside your chosen range, a different one outside it — a sharp, colorful subject against a moody, desaturated background, for example.
- 🪆 **Depth Diorama** — build your own exploded 3D layer view of a photo: click objects (a person, a car), drag a square around anything, or paint a depth-band region to put each into its own layer, then explode, rotate, and tilt the whole scene in a live 3D view. One button can do the obvious work for you — it cuts out the closest people or objects and rebuilds the background behind them — and you adjust from there.
- 🖌️ **Style transfer** — repaint a photo with the brushwork and color palette of any picture you choose, powered by a local AI model. Pick any photo as the style source and build your own saved gallery of styles to reuse — no art is bundled with the app.
- 🟦 **Locations** — an interactive map of where your photos were taken, clustered so it's easy to browse, with optional place names and the option to see every location you've ever cached, not just the current folder. With smart search set up (see Search), a search bar on the map shows only the photos that match what you describe.
- 🔎 **Search** *(downloads a model once, about 633 MB, then fully offline)* — find photos by describing them in your own words, in English or Swedish: "dog in snow", "Ellanor beach summer 2019", "barn på stranden". It looks across every photo LinTabSort has a thumbnail for, not just the folder you have open, and the same box understands a person you named in People, a date or season, a place, a catalogue, video, and star ratings. Right-click any result for **More like this**, tick several for **More like these**, sort and narrow the results, and see at a glance how strong each match is: a result is framed green for a strong match and red for a weak one, so a poor guess does not pass for a good one. Photos that are exact copies show as one result and open straight in Find Duplicates, and a small pin shows a photo on the map. It reads only cached thumbnails, in folders you approve. **No photo, thumbnail or search text is ever sent anywhere.**
- 🗓️ **Timeline** — a year-by-year sidebar to jump straight to any month or folder while reviewing.
- ℹ️ **Photo info** — date, camera, and shooting details at a glance for whatever you're looking at.
- 📊 **My Media** — a stats dashboard for your whole library: busiest shooting days on a GitHub-style heatmap, a camera/phone ownership timeline, "on this day" in past years, how this month compares to last year, and more, with most stats clickable straight through to the matching photos.
- 🙂 **People** — local, offline face recognition. LinTabSort finds and groups faces across your library automatically as you review, so photos of the same person collect together without you tagging a single one by hand. Add an optional birth date for anyone and matching gets noticeably smarter — it learns what that person actually looked like at each age, instead of blurring their whole life into one average, and can flag genuine lookalikes (the classic mixed-up-siblings problem) before you accidentally confirm the wrong one. Everything runs on your own computer — no photo or face data is ever sent anywhere. Can also pick up face names you already gave photos in Google's old Picasa, if you have any lying around.
- 🧵 **Weave of People** — pick anyone from the People tab and see a full-screen storyline of their whole life: a cord tracing their own timeline, splitting into a colored strand (with its own face thumbnail) every time someone else shares a confirmed photo with them, plus a photo-stream band of every solo photo along the same timeline, with birthday markers for anyone whose birth date you've added.
- 🖼️ **Face Morph "profile pic"** — open anyone in People and click to build a small floating polaroid: one real, best photo per half-year of their life, morphing through in order — a real "growth reel," not a random shuffle — with their age shown under each photo and a live progress readout while it builds. No birth date needed. Save the sequence as an animated GIF or MP4, shuffle to a random mix instead, or tune the transition speed, style, resolution, and on-screen size yourself. Faces are aligned by matching the eyes exactly, so nothing drifts or wobbles between photos.
- 🎬 **Custom Morph** — hand-pick specific photos of different people (not just one person's own timeline), in any order, and play them back as your own custom morph sequence, saved as a GIF or MP4. Or let it build a chain of up to 20 photos of one person, earliest to latest, ranked so neighbouring head poses match.
- 🧩 **Collage** — pick a handful of someone's photos in People and build a single collage image out of them. Choose a layout style, background color, and (for the scattered style) how much the photos tilt, with a live preview and a Shuffle button to re-roll the arrangement before saving.
- 🕵️ **Correction run** — re-checks every already-confirmed face tag in People for mistakes (the classic "two similar-looking people swapped in a group photo" case) and flags anything suspicious for a quick review.
- 📱 **Phone import** — plug in an Android phone and copy your photos over. LinTabSort only ever *reads* from your phone — nothing on it is ever touched, moved, or deleted.
- ▶️ **Video playback** — play, pause, change speed, grab a still frame, right in the app.
- 🎨 **Photo filters and adjustments** — dozens of filters from classic effects to real image-processing techniques like CLAHE (auto contrast), Retinex (dehazing), a Vector filter (clean, simplified vector-style regions for a posterized look), a Voronoi mosaic stained-glass look, a Poincaré hyperbolic-disk warp, a retro-computer palette with dithering (Amiga, Game Boy, NES and more), and a Droste spiral, plus exposure/contrast/shadows/highlights — all previewed live and saved without ever touching your original file.
  The filters, in 9 groups (star one to keep it under Favorites):
  - **Depth tools:** Dual filter, Focus, Depth map, Cutout
  - **Fix & enhance:** Inpaint, Remove pattern, CLAHE, Retinex, Sharpen, Guided detail, Wavelet detail
  - **Color & tone:** Color grade, Grayscale, Sepia, Invert, Duotone, Posterize, X-Ray, Night vision, Gradient heatmap
  - **Warp & geometry:** Ripple, Swirl, Fisheye, Pinch, Bulge, Mirror, Kaleidoscope, Möbius warp, Tiny planet, Droste spiral, Poincaré disk, Perspective skew
  - **Camera & lens:** Bokeh, Motion blur, Lens flare, God rays, Bloom, Vignette, Grain, Polaroid, Disposable camera, Light leak
  - **Glitch & retro:** CRT, Scanlines, RGB split, Datamosh, DVD compression, JPEG hell, Retro palette
  - **Pixels & print:** Pixelate, Halftone, Dither, Palette quantize, ASCII
  - **Paint & draw:** Watercolor, Painterly flow, Stained glass, Voronoi mosaic, Neon edges, Style transfer, Comic book, Sketch, Ink lines, Emboss, Edge detect, Vector filter
  - **Builders:** QR code art, Cross-stitch pattern, Carving guide, Depth Diorama
- 🪄 **AI photo restoration & object removal** *(downloads a small model on first use, then fully offline)* — upscale, denoise, colorize, or erase an unwanted object right in the viewer, either by drawing a box around it yourself or letting "Poof!" find every object in the photo automatically — click one and it's gone. Each powered by a small AI model that downloads once and then runs completely on your own computer. **Your photos are never sent anywhere, at any time.**
- 🕰️ **Full edit history with one-click undo** — every filter, adjustment, restoration, and object removal you apply is remembered as its own step, in a free-floating, resizable window. Jump back to any earlier point, or remove just one step from the middle and keep the rest.
- 🖥️ **Pin to second screen** — pop a photo out onto another monitor while you keep browsing, with an optional auto-advancing slideshow.
- 🐸 **Busy frogs** — long operations get a swarm of hopping frogs instead of a boring spinner. Yes, really. Pick one of sixteen built-in sheets - colours and patterns like tiger, zebra and galaxy - or upload your own transparent PNG, in Settings. You can turn it off if you're no fun.
- 🐸 **Frog guide** — in the face-tagging window, a small frog hops beside whichever face you're naming and moves on with you. It talks in a little speech bubble ("Who is this?", "Named!") and is off until you tick the checkbox next to Ignore/Done. A ? button explains the window in a few lines.

## Privacy

By default, your photos and videos never leave your computer — everything runs locally, and no photo is ever sent to any network endpoint. AI photo restoration (upscale/denoise/colorize/object removal), the depth-aware filters/Parallax, Style transfer, People (face recognition), and smart search all run entirely on your own computer — the only network activity any of these involves is a one-time download of the relevant model the first time you use it, after which everything runs fully offline. People and smart search each ask before they scan a folder for the first time, and People asks again before using any old Picasa face tags it finds. Maps, historical weather, and place names are also **off by default** and never turn on by themselves (Settings → Privacy). Once turned on: the Locations map fetches map tiles from OpenStreetMap (and, the first time, its map library from the unpkg.com CDN); selecting a geotagged photo can look up that day's weather from Open-Meteo (free, no account); pausing on a geotagged photo or clicking the map can look up a place name from Nominatim/OpenStreetMap (free, no account). Each of these sends only the rounded location and/or date to that service — never your actual photo — same as any map website. Your photo *files* never leave the computer either way.

Some AI features can optionally use your graphics card (GPU) instead of the CPU, for speed — this is **off by default** and, when turned on (Settings → AI), still never sends any photo anywhere. It uses Microsoft's DirectML, a separate Microsoft component whose own license notes it may report usage information to Microsoft — everything else in LinTabSort stays free of that.

## Questions or feedback?

**Mikael Lindmark** — [lindmark.mikael@gmail.com](mailto:lindmark.mikael@gmail.com)

If LinTabSort saved you an afternoon of folder chaos, a [Ko-fi](https://ko-fi.com/lintabcrux) tip is always appreciated. ☕

