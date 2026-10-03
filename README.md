<p align="center">
  <img src="icon-512.png" width="120" alt="Reelcall logo">
</p>

<h1 align="center">Reelcall</h1>

<p align="center">
  <b>Your Instagram saves, finally sorted.</b><br>
  AI reads your saved reels and tucks each one into the right category, so you can actually find them again.
</p>

<p align="center">
  <a href="https://arpithpaliwal.github.io/Reelcall/"><img src="https://img.shields.io/badge/Open%20Reelcall-FF5A7A?style=for-the-badge&logoColor=white" alt="Open Reelcall"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-bring%20your%20own%20key-8B5CFF?style=flat-square" alt="Bring your own AI key">
  <img src="https://img.shields.io/badge/data-stays%20on%20your%20phone-19B7A6?style=flat-square" alt="Data stays on your phone">
  <img src="https://img.shields.io/badge/installs%20as-an%20app-FF9F43?style=flat-square" alt="Installs as an app">
  <img src="https://img.shields.io/badge/build%20step-none-3D8BFF?style=flat-square" alt="No build step">
</p>

<p align="center">
  <img src="screenshot-categories.png" width="200" alt="Categories">
  &nbsp;
  <img src="screenshot-grid.png" width="200" alt="All saves in dark mode">
  &nbsp;
  <img src="screenshot-ask.png" width="200" alt="Ask your saves">
  &nbsp;
  <img src="screenshot-sort.png" width="200" alt="Sort with AI">
</p>

---

## ✨ What it does

You save hundreds of reels "for later" and never find them again. Reelcall fixes that.

| | |
|---|---|
| 🗂️ **Sorts with AI** | Reads each caption, hashtag and creator, then files your saves into categories like *Recipes*, *Workouts* or *AI & Coding*. |
| 🎛️ **Three sorting modes** | **Auto** invents categories, **Strict** uses only yours, **Mixed** uses yours first and creates new ones for the rest. |
| 💬 **Ask your saves** | Type *"that Korean cafe in Hyderabad"* and Reelcall finds it. Paste an Instagram link to add a new reel. |
| 🔑 **Any AI key** | Gemini (free), Claude, OpenAI, OpenRouter, Groq, DeepSeek, Grok, Perplexity, Mistral and more. |
| 📱 **Installs as an app** | Own icon, full screen, and your library opens even offline. |
| 🔒 **Private by design** | No accounts, no servers. Everything lives on your phone. |
| ➕ **Smart updates** | Import new saves later and only the new ones get sorted. Your categories stay as you left them. |

---

## 📲 Install it as an app

### Android (Chrome)

1. Open **[arpithpaliwal.github.io/Reelcall](https://arpithpaliwal.github.io/Reelcall/)** in **Chrome**.
2. Check that you see the **Reelcall** page with the pink-and-purple logo.
3. Tap **⋮** (top right) → **Install app**.
   *On some phones it says **Add to home screen** → choose **Install**, not "Create shortcut".*
4. Tap **Install** to confirm.
5. **Reelcall** now appears in your app drawer and home screen. Open it from there.

> **Seeing "Install GitHub" instead?** You're on the github.com page. Open the **github.io** link above instead.

### iPhone (Safari)

1. Open **[arpithpaliwal.github.io/Reelcall](https://arpithpaliwal.github.io/Reelcall/)** in **Safari**.
2. Tap the **Share** button (square with an arrow).
3. Tap **Add to Home Screen** → **Add**.

---

## 🚀 How to use it

### Step 1: Add your AI key

Reelcall uses your own AI key, so sorting is free with Gemini and nobody else sees your saves.

1. Get a free key at **[aistudio.google.com/apikey](https://aistudio.google.com/apikey)** → **Create API key** → copy it.
2. In Reelcall, tap **Add AI key** (or **⋯ → AI key**).
3. Paste the key. Reelcall detects the service, picks a model and tests it on its own.
4. You'll see **Connected: Google Gemini**. Done.

<details>
<summary><b>Supported AI services</b></summary>

| Service | Key starts with | Notes |
|---|---|---|
| Google Gemini | `AIza` | Free tier, recommended |
| Claude | `sk-ant-` | |
| OpenAI | `sk-` | |
| OpenRouter | `sk-or-` | Access to many models with one key |
| Groq | `gsk_` | Very fast |
| xAI Grok | `xai-` | |
| Perplexity | `pplx-` | Has built-in web search |
| DeepSeek, Mistral, Together, Cohere, DeepInfra | varies | Pick the service from the list when asked |
| Anything else | any | Choose **Other (OpenAI-compatible)** and paste its API address |

Some services block requests from web pages. If one does, Reelcall tells you clearly. Gemini is the safe choice.
</details>

### Step 2: Bring in your saved posts

**Option A: Instagram's export file** (works for everyone)

1. In Instagram, go to **Accounts Center → Your information and permissions → Export your information**.
2. Choose **Some of your information**, tick **Saved**, and set **Format** to **JSON**.
3. When Instagram says it's ready (usually within an hour), download it.
4. In Reelcall, tap **Choose files** (or **⋯ → Import files**) and pick the `.zip`, or just `saved_posts.json` from inside it.

**Option B: the Instagram bookmark** (fetch new saves in one tap)

1. In Reelcall, tap **⋯ → Get new saves from Instagram** → **Copy bookmark**.
2. In Chrome, tap **⋮ → ☆** to bookmark any page, then **Edit**. Name it `Reelcall` and paste what you copied as the URL.
3. Open **instagram.com** in Chrome (logged in), tap the address bar, type `Reelcall`, and tap the bookmark.
4. It reads your latest saves and brings you back to Reelcall with them added and sorted.

### Step 3: Sort with AI

1. Tap **Sort with AI**.
2. Pick a mode:

   | Mode | What happens |
   |---|---|
   | **Auto** | AI invents categories from your saves |
   | **Strict** | Only your categories; the rest stay in *Uncategorized* |
   | **Mixed** | Your categories first, AI creates new ones for leftovers |

3. Choose **Which saves** (most recent 100 to 600, or all) and how sure the AI must be.
4. Tap **Sort**. Watch your saves fly into their shelves.

### Step 4: Browse, watch and tidy up

- **Categories** shows one row of reels per category, and **All** shows a searchable grid.
- **Tap a tile** to watch the reel on Instagram.
- **Tap ⋯ on a tile** to change its category, add a note or remove it.
- **Select** (in *All*) moves or removes many saves at once.
- Categories can be renamed or deleted from their page.

### Step 5: Ask

Open the **Ask** tab and type what you remember: *"easy pasta recipes"*, *"AI agent roadmap"*, *"Goa sunset cafes"*. Reelcall searches captions, hashtags, creators and notes, and shows the matching reels.

Not in your saves? Use **Find more on Instagram**, or paste any Instagram link into Ask to add it.

### Step 6: Keep your sorting safe

Your library lives on your phone. To keep a permanent copy:

1. Tap **Save to phone** (or **⋯ → Save to phone**).
2. Reelcall downloads `reelcall-library.html`, which is the app with all your saves and categories inside.
3. Open that file anytime to get everything back, even on a new phone.

### Step 7: Add new saves later

Import a newer export (or use the bookmark). Reelcall asks:

- **Add new and sort**: adds only saves made after your last import and sorts **just those**.
- **Clear and start over**: wipes the current sorting and sorts the new file from scratch.

---

## 🛠️ Host your own copy

1. **Fork** this repository (or upload these files to a new **public** repo):
   `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`
2. Go to **Settings → Pages**, set **Branch** to **main** and **/(root)**, and **Save**.
3. After a minute your copy is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.
4. Open it in Chrome and install it as shown above.

**Updating:** upload the new `index.html` (same name) and commit. The installed app picks it up the next time you open it online.

---

## ❓ Troubleshooting

<details>
<summary><b>Chrome offers to install GitHub instead of Reelcall</b></summary>

You're on github.com. Open <code>https://arpithpaliwal.github.io/Reelcall/</code> instead, then tap <b>⋮ → Install app</b>.
</details>

<details>
<summary><b>The link shows "404 – There isn't a GitHub Pages site here"</b></summary>

Turn on Pages: <b>Settings → Pages → Branch: main, /(root) → Save</b>. Wait 1–2 minutes and reload.
</details>

<details>
<summary><b>"Gemini is busy" or "had a problem"</b></summary>

Free tiers get busy. Reelcall retries automatically up to 4 times. If it still fails, wait a minute and tap <b>Sort</b> again. Posts already sorted are kept.
</details>

<details>
<summary><b>"The key was rejected"</b></summary>

Copy the key again carefully (no spaces), or create a new one. Check it in <b>⋯ → AI key</b>.
</details>

<details>
<summary><b>My data disappeared</b></summary>

Clearing Chrome's site data removes it. Open your latest <code>reelcall-library.html</code> (from <b>Save to phone</b>) to restore everything.
</details>

---

## 🔒 Privacy

- No accounts, no analytics, no server. Reelcall is a static page (fonts load from Google Fonts).
- Your saves, categories and notes are stored only in your browser on your device.
- Your AI key stays on your device and is sent only to the AI service you chose.
- Only short text about your posts (creator, caption, hashtags) is sent to that AI service for sorting and search.

---

## 🧩 How it's built

One self-contained `index.html` with plain HTML, CSS and JavaScript: no framework and no build step. `manifest.json` and `sw.js` make it installable and let it open offline. Fonts: [Gluten](https://fonts.google.com/specimen/Gluten) and [Figtree](https://fonts.google.com/specimen/Figtree).

---

<p align="center">
  <sub>Reelcall is an independent personal project and is not affiliated with Instagram or Meta.</sub><br>
  <sub>Made by <a href="https://github.com/ArpithPaliwal">Arpith Paliwal</a></sub>
</p>
