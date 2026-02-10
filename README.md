#  Text Portrait — README
Text Portrait can convert your given image into a text- portrait/ascii art. The user uploads an image and it generates  a ascii art which is also called calligram, text art, or typography art

# Readme ....
Convert any photo into a beautiful ASCII / text art portrait, right in your browser. No installs, no server, no internet needed after the first load.

---

## 📁 Project Files

```
text-portrait/
├── index.html   ← the app  (open this in your browser)
├── style.css    ← all the styling
└── README.md    ← this file
```

> Both `index.html` and `style.css` **must be in the same folder** — the HTML file links to the CSS by name.

---

## 🚀 How to Use

1. **Open `index.html`** in any modern browser (Chrome, Firefox, Edge, Safari)
2. **Upload a photo** — click the upload box or drag-and-drop an image onto it
3. **Adjust the settings** in the left panel to your taste
4. **Click "Generate Portrait"** — your ASCII portrait appears on the right
5. **Download or copy** the result using the buttons that appear

That's it. No sign-up, no server, everything runs locally.

---

## ⚙️ Settings Explained

| Setting | What it does | Recommended |
|---|---|---|
| **Width (chars)** | How many characters wide the portrait is. Higher = more detail. | 100 – 160 |
| **Font Size (px)** | How large each character is drawn on the canvas. | 6 – 9 |
| **Char Set** | The set of characters used to represent brightness levels. | Dense gradient |
| **Custom chars** | Your own character set, ordered from darkest to lightest. | e.g. `@#*+;:,. ` |
| **Invert** | Flips dark/light — gives white text on black background. | Off by default |
| **Coloured output** | Uses the original image colours on each character. | Fun for portraits |
| **Auto-contrast boost** | Stretches the brightness range for crisper, punchier results. | Keep ON |

---

## 🎛 Tips for the Best Results

- **Portraits with a plain background** work best — the subject stands out clearly.
- **High contrast photos** (strong light, dark shadows) produce the most detailed ASCII art.
- **Increase width to 140–180** for sharp facial detail.
- **Try "Invert"** for a dramatic dark-background version.
- **Use "Coloured output"** with a landscape or colourful portrait for a vivid effect.
- If the result looks too light or washed out, make sure **Auto-contrast** is turned on.

---

## 📥 Outputs

| Button | What it does |
|---|---|
| **Generate Portrait** | Runs the ASCII conversion and draws to the canvas |
| **↓ Download PNG** | Saves the canvas as a full-resolution `.png` image |
| **Copy Text** | Copies raw ASCII text to your clipboard (paste into a text editor or terminal) |

The **Stats bar** at the bottom of the output shows the portrait dimensions in characters and the final canvas size in pixels.

---

## 🌐 Browser Compatibility

Works in all modern browsers. Requires JavaScript enabled.

| Browser | Supported |
|---|---|
| Chrome / Edge | ✅ |
| Firefox | ✅ |
| Safari | ✅ |
| IE 11 | ❌ |

---

## 📐 Char Set Reference

| Name | Characters | Best for |
|---|---|---|
| Dense gradient | 70-character set from space to `$` | Photorealistic portraits |
| Block elements | `░ ▒ ▓ █` | Bold, graphic look |
| Braille dots | `⠂ ⠆ ⠇ ⠿ ⣿` | Subtle, fine-textured |
| Minimal | `. : ; | # @` | Clean, minimal style |
| Custom | Your own string | Anything you like |

---

## 🔧 No Internet? No Problem

The app loads Google Fonts (`Bebas Neue`, `Space Mono`, `Courier Prime`) on first open. After that it works fully offline — fonts will gracefully fall back to `monospace` if unavailable.
