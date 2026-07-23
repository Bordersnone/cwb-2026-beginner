# The Ladder Continues — GitHub + Rounds 12–15

Last class you climbed [the ladder](../2026-07-21-guided-page-build/README.md). Today you keep climbing from **exactly where you stopped** — and the ladder just grew four new rounds.

## 🗺 Today

1. **GitHub kickoff (15 min, everyone):** what GitHub is, why developers live on it, and how you'll put your work there so we can review it.
2. **Back on the ladder:** open [last class's rounds](../2026-07-21-guided-page-build/README.md), find the round you were on, and climb. Same rules: check **"✅ Done when"**, move on, never wait for the group. Regroups on a timer, short and time-boxed.
3. **New rounds below** for everyone who gets past Round 11 — and Round 12 is for *everyone*, this week.

> 🧭 **Need a GitHub account?** Follow the [GitHub side-quest](./github-setup.md) — do it right after the kickoff, then get back on the ladder.

---

## 🚢 Round 12 — Ship It: Your Code on GitHub

Developers don't email zip files. Code lives on GitHub — versioned, shareable, reviewable. Time to join them. ([Side-quest](./github-setup.md) has the click-by-click if you need it.)

**Target:** a **public GitHub repository** named `my-favorite-things` containing your entire project: every HTML file, your `style.css`, your `images/` folder, and a `README.md` that says what the project is. No git commands needed — uploading through the website is fine.

**✅ Done when:** your teacher can open `github.com/YOUR-USERNAME/my-favorite-things` on *their* machine and see all your files, with your README displayed at the bottom.

**🚀 Go deeper:** make the README worth reading — a heading, a list of what the site includes, and a link. It's written in *Markdown* — a fourth language you now know exists.

---

## 📬 Round 13 — The Contact Form

**Target:** a `contact.html` page with a form that looks like it belongs to your site: a **text input** for name, an **email input** (there's a specific type for that), a **dropdown** ("How did you find me?" — that's the `<select>` element with `<option>`s inside), a **message textarea**, and a **submit button**. Every field has a proper `<label>` — clicking the label puts the cursor in the field. Style it to match your card aesthetic, and give every field a visible **`:focus`** state.

**✅ Done when:** you can put your mouse away and Tab through the entire form, always able to *see* which field you're in — and clicking any label focuses its field.

*(It won't actually send anywhere — that needs a server. That's a later chapter.)*

**🚀 Go deeper:** make fields `required` and watch what the browser does when you submit them empty.

---

## 🧱 Round 14 — The Gallery, For Real

Your gallery wraps, but the rows are ragged. Real galleries use **CSS Grid**.

**Target:** rebuild your gallery section as a grid: images aligned in equal columns with consistent gaps, and **one featured image spanning two columns**. The column count should adapt to the window width (a media query is allowed; if you want the wizard version, research `auto-fit` + `minmax` — no media query needed at all).

**✅ Done when:** resize the window — tiles stay aligned in a clean grid at every width, and whenever the grid has 2+ columns the featured tile visibly spans two of them.

*Images fighting the grid?* Give them `width: 100%; height: 100%; object-fit: cover;` — that's the pros' trick for mixed-shape photos.

**🚀 Go deeper:** captions that appear *on top of* each image when hovered.

---

## 🛰 Round 15 — LIVE ON THE INTERNET

Everything so far only exists on your laptop. Fix that.

**Target:** using **GitHub Pages** (free, built into the repo you made in Round 12), publish your site to a real URL: `your-username.github.io/my-favorite-things`.

The path:

1. **Check first:** your `index.html` must sit at the **top level** of the repo (not inside a folder) — GitHub Pages only auto-serves that exact name
2. In your repo: **Settings** tab → **Pages** (left sidebar)
3. Under "Build and deployment": Source = **Deploy from a branch** → branch **main**, folder **/ (root)** → **Save**
4. Wait 1–2 minutes (really), refresh the Pages settings page — your URL appears at the top

**✅ Done when:** your site loads **on your phone** — not on localhost, on the actual internet — and you've sent the link to your teacher.

**🚀 Go deeper:** pick ONE "Go deeper" you skipped in an earlier round, finish it, push it — and confirm the change shows up at your live URL. That loop (edit → push → live) is how every website you've ever visited gets built.

---

## 🏠 Homework

1. **Everyone reaches Round 12 by next class** — your project on GitHub is how homework gets reviewed from now on
2. Keep climbing from wherever class ended — every round's instructions stand alone
3. Once you pass Round 15: go back and finish every ladder round you skipped — each one you push shows up on your live site

## 📖 Reference

New rounds' links: [resources.md](./resources.md) · Rounds 1–11 links: [last class's resources](../2026-07-21-guided-page-build/resources.md)
