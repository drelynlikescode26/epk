# epk

## Update your EPK content

All editable content is now imported from [epk-data.js](epk-data.js).

- Edit `hero` for name, title, tagline, and hero image.
- Edit `bio` for the 2–3 paragraph artist bio.
- Edit `highlights` for metric cards.
- Edit `music.spotifyEmbed`, `music.appleEmbed`, `music.appleEmbedHeight`, and `music.youtubeVisuals` for players/visuals.
- Edit `gallery` for press photo URLs and alt text.
- Edit `contact` for email, location, and Instagram.

The page in [index.html](index.html) auto-renders from that file by loading [epk-data.js](epk-data.js) as a script.

## Local gallery images

Drop your final gallery photos into [assets/gallery](assets/gallery) using these filenames:

- `deric-gallery-1.jpg`
- `deric-gallery-4.jpg`
- `deric-gallery-5.jpg`
- `deric-gallery-6.jpg`
- `deric-gallery-7.jpg`
- `deric-gallery-8.jpg`

These are already referenced in [epk-data.js](epk-data.js), so once files are added, the gallery updates automatically.