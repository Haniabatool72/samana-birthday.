# Samana — A Little Universe of Memories ♡

## Description

A dreamy, interactive birthday surprise website for Samana: a 3D gift reveal, polaroid memory gallery, inside jokes, 10 reasons, a secret letter, a friendship quiz, a birthday cake with candles, wishes and fireworks. Built with plain HTML, CSS and JavaScript (no frameworks, no build step).

**Journey:** secret opening → 3D gift reveal → memory lane → inside jokes → 10 reasons → secret letter → friendship quiz → birthday cake, wish and fireworks → replay.

Designed & Developed by Hania Batool.

## Run it
Double-click `index.html`, or open it in any browser. That's it.

## Put it online with GitHub Pages (free)
1. Create a new repository on GitHub and upload everything in this folder (keep the `assets` folder).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`. Send that link to Samana.

## Customise (everything is in `script.js`)
Open `script.js` and edit the `CONTENT` block at the top:

| What | Where |
|---|---|
| Photo captions and file names | `photos` |
| Inside-joke cards | `usCards` |
| The 10 reasons | `reasons` |
| Birthday letter (use `\n` for a new line) | `letter` |
| Quiz questions, options and correct answer (`answer` starts at 0) | `quiz` |
| Quiz result messages | `quizResults` |
| Final message | `finalMessage` |
| WhatsApp number that receives her wish (country code, no `+` or leading 0) | `whatsapp` |
| Music file | `music` |

Colours are variables at the top of `style.css` (`:root`).

## Photos
Put 5–10 photos in `assets/images/` named `photo1.jpg`, `photo2.jpg` … (or change the names in `CONTENT.photos`). Square-ish photos under about 300 KB each load fastest. Missing photos show a soft pink placeholder, nothing breaks. To add or remove photos, add or remove lines in `CONTENT.photos`.

## Music
Put a song at `assets/music/music.mp3`. Music starts when Samana taps "Open Your Surprise" and keeps playing (browsers do not allow sound before a tap). If there is no mp3, a soft built-in romantic melody plays instead.

## Her wish
When Samana types a wish and taps "Send my wish ♡", it floats up to the stars and WhatsApp opens with the message ready for the number in `CONTENT.whatsapp`. She has to press send in WhatsApp; a website cannot send messages by itself.

## Structure
```
index.html      page structure
style.css       design and responsive layout
script.js       content, animations, music, quiz, cake, fireworks
assets/images/  put photos here
assets/music/   put music.mp3 here
```

## GitHub repository details
**About / description:** A dreamy interactive birthday surprise website for Samana, built with HTML, CSS and JavaScript.

**Topics:** `birthday` `surprise` `html` `css` `javascript` `interactive` `gift` `github-pages`
