# Guided Build — "My Favorite Things" Page

Last class we took the quiz and reviewed the answers. Today we **build** — a complete page, from an empty folder to a styled, multi-page mini-site.

## 🎮 How Today Works

Today is a **ladder** of rounds — easy at the bottom, brutal at the top. You climb at **your own pace**:

1. **Build solo.** When a round's **"✅ Done when"** check passes, either take the **"🚀 Finished early?"** detour or climb straight to the next round. **Never wait for the group.**
2. **Regroups on a timer.** Every ~15 minutes we all stop — wherever we are — for a *short, time-boxed* review: someone shows their work, we talk through the *why*, then right back to building.
3. **Struggling is the point.** Getting stuck and unstuck is how this skill is actually learned. Use the [reference links](./resources.md) first; ask for help after two real attempts.

The minutes on each round are a **pace guide**, not a rule. And fair warning: at the top of the ladder waits a **🏆 BOSS**. It does not care how fast you climbed. Nobody is expected to beat it today.

---

## Round 1 — The Skeleton (~5 min)

**Goal:** a valid page you can open in your browser.

1. Make a new folder called `my-favorite-things`, and inside it a file `index.html`
2. Write the full page structure from memory if you can: `<!DOCTYPE html>`, `<html>`, `<head>` (with a `<title>`), `<body>`
3. In the body: one `<h1>` page title, two `<h2>` section headings, and a paragraph under each `<h2>`
4. Make one word **bold** and one word *italic* somewhere in your paragraphs

**✅ Done when:** your browser tab shows your title, and the headings appear in decreasing size.

**🚀 Finished early?** Add a third section. Then put a `<br>` in the middle of a paragraph and observe exactly what changes.

---

## Round 2 — Lists, Lines & Notes (~7 min)

1. Under your first section: an **unordered list** of at least 3 favorite things
2. Under your second section: an **ordered list** — your top 3 of something, ranked
3. Put an `<hr>` between the two sections
4. Add an HTML **comment** above each section labeling it (invisible on the page!)
5. At the bottom: a `<pre>` block with a tiny ASCII drawing

**✅ Done when:** one list has bullets, the other has numbers, your comments do NOT show up in the browser, and your ASCII art keeps its exact shape.

**🚀 Finished early?** Nest a `<ul>` *inside* one of your `<li>` items — sub-favorites!

---

## Round 3 — Images & Links (~10 min)

1. Create an `images/` folder inside `my-favorite-things` and put any image file in it
2. Show it on your page with a **relative path** — and don't forget the `alt` attribute
3. Add an **absolute link** to a real website you like
4. Create a second file, `page2.html`, with just an `<h1>` for now
5. Link `index.html` → `page2.html` with a **relative link**, and link back from `page2.html` → `index.html`

**✅ Done when:** your image displays, and you can click from page 1 to page 2 and back without touching the address bar.

**🚀 Finished early?** Make your absolute link open in a new tab. Then rename your `images/` folder to `img/` and watch what breaks — then fix it.

---

## Round 4 — First CSS (~8 min)

1. Add a `<style>` block inside your `<head>`
2. Using **element selectors only**, write three rules:
   - give `body` a `font-family` (try `Arial, sans-serif`)
   - give `h1` a `color`
   - change something about every `p` (color? `line-height`?)

**✅ Done when:** every paragraph on the page changed — and you only wrote ONE rule to do it.

**🚀 Finished early?** Style your `h2`s differently from your `h1`. Try `font-size` on your list items.

---

## Round 5 — Classes & IDs (~10 min)

1. Add `class="highlight"` to at least two **different kinds** of elements (an `<li>` and a `<p>`, for example)
2. Write a `.highlight` rule — a `background-color` shows up well
3. Give ONE special element an `id` and style it with a `#` rule

**✅ Done when:** several elements share the highlight look from a single rule, and exactly one element has its own unique style.

**🚀 Finished early?** Try `li.highlight` — how is it different from `.highlight`? Then put two classes on one element: `class="highlight big"`.

---

## Round 6 — Level Up (~10 min)

1. Add a rule with the **descendant selector** `ul li` — it should style list items in your `ul` but not your `ol`
2. The big move: create `style.css`, cut ALL your CSS into it, and connect it with
   `<link rel="stylesheet" href="style.css">`

**✅ Done when:** your `<style>` block is gone and the page looks **exactly** the same.

**🚀 Finished early?** Add the same `<link>` to `page2.html` — two pages, one stylesheet. That's why external files win.

---

## 🏆 Round 7 — BOSS FIGHT: The Business Card

No step-by-step instructions this time. **That's the point.** You get a target; how to build it is your problem. Everything you need exists on W3Schools and MDN — searching and reading docs is allowed, encouraged, and *is the actual skill being tested*.

**Build this** — a new file, `card.html`:

```
┌────────────────────────────────────────┐
│                                        │
│                                        │
│           ╭───────────────╮            │
│           │    (image)    │            │
│           │   Your Name   │            │
│           │ one line about│            │
│           │      you      │            │
│           │ [A]  [B]  [C] │            │
│           ╰───────────────╯            │
│                                        │
│                                        │
└────────────────────────────────────────┘
        the whole browser window
```

A "business card" floating **dead center of the browser window** — centered left-right AND top-bottom. The card has: rounded corners, a visible border, a drop shadow, a different background than the page behind it, an image at the top, your name as a heading, a one-line description, and **three links sitting side by side in a row** that change color when you hover over them.

**Progress levels** — how far did you get?

- 🥉 **Level 1:** the card looks like a card — border, rounded corners, shadow, padding, fixed width
- 🥈 **Level 2:** the card is centered **horizontally**
- 🥇 **Level 3:** the three links sit in a horizontal row and react to hover
- 🏆 **Level 4:** the card is centered **vertically too** — perfectly dead-center, even when you resize the window

Level 4 has made professional developers cry. There is a *reason* our next classes exist. If you beat it: screenshot it, and prepare to explain every line at the next regroup.

---

## 🏠 Homework

1. **Finish any rounds you didn't get to in class** — the instructions above stand alone
2. Make `page2.html` a real page: headings, a list, an image, and styling via the shared `style.css`
3. **Keep fighting the boss.** Bring your best attempt to next class — we'll dissect it together, and what we learn from it is exactly where the course goes next
4. **Mistake hunt:** break your page in 3 deliberate ways (remove a closing tag, break your image path, misspell a selector), observe each in the browser, fix it, and document all 3 as HTML comments at the bottom of the page

---

## 📖 Reference

Every tag and selector used today: [resources.md](./resources.md) — keep it open while you build.
