# Review & Practice — HTML Basics + CSS Selectors

**Format:** Warm-up quiz → group review → hands-on build → homework

> **Where the class is:** Previous classes covered HTML basics (tags: `br`, `hr`, `pre`, `b`, `i`), headings, comments, images, relative & absolute links, lists, and an introduction to CSS selectors. Previous teacher's note: *"I think they need more practice and homework."*

---

## 🗓 Class Plan

### 1. Warm-up quiz (~15–20 min)
Hand out [quiz.md](./quiz.md) — 15 questions plus a "find the mistakes" bonus.

- Emphasize up front: **not graded, diagnostic only.** Honest blanks are more useful than lucky guesses.
- While students work, circulate and note which questions cause the most hesitation.

### 2. Review answers together (~15 min)
Go through the answers as a group (answer key: `quiz-answers.md` — kept out of this repo on purpose; teachers have it locally).

- Have **students** explain the answers where possible — teaching back is the best retention check.
- Spend extra time on whatever the quiz reveals as weak. Likely candidates based on last year: `src` vs `href`, relative paths, and the class-vs-ID distinction.
- The bonus "find the mistakes" question makes a great live demo: paste it into VS Code, open it in the browser, and fix mistakes one at a time so students see the effect of each fix.

### 3. Hands-on build: "My Favorite Things" page (~40 min)
Everyone builds a single page from scratch that uses **every element covered so far**. Checklist for students:

- [ ] One `<h1>` page title, and at least two `<h2>` section headings
- [ ] An `<hr>` separating the sections
- [ ] A paragraph with at least one `<b>` and one `<i>` word
- [ ] An **unordered list** of at least 3 favorite things
- [ ] An **ordered list** (e.g., top 3 movies, ranked)
- [ ] An image loaded with a **relative path** (put it in an `images/` folder!)
- [ ] One **absolute link** to a real website, and one **relative link** to a second page (`page2.html` — it can be nearly empty)
- [ ] A `<pre>` block (a tiny ASCII drawing is a fun option)
- [ ] At least one HTML comment labeling a section
- [ ] A `<style>` block with: one **element selector**, one **class selector** used on 2+ elements, and one **ID selector**

Fast finishers: add a `ul li` descendant selector that styles only list items, or style the two lists differently using classes.

### 4. Wrap-up (~5 min)
Preview what's next (see roadmap below) and assign homework.

---

## 🏠 Homework

Extend your "My Favorite Things" page:

1. Fill in `page2.html` as a real second page (same checklist spirit), and make sure the two pages **link to each other**.
2. Add a class named `.highlight` and apply it to your three favorite items across both pages.
3. **Mistake hunt:** deliberately break your page in 3 ways (remove a closing tag, break an image path, misspell a selector), observe what happens in the browser, then fix it. Write the 3 mistakes as HTML comments at the bottom of the page.

Item 3 builds debugging instinct — knowing what *broken* looks like is half of fixing it.

---

## 🔜 Roadmap: what stands between here and Flexbox

Before Flexbox makes sense, students need (roughly 2–3 classes, mirroring last year's classes 08–09):

1. **Where CSS lives** — inline vs `<style>` vs external stylesheet
2. **Text & color properties** — `color`, `font-size`, `font-family`, `text-align` (gives selectors something meaningful to do)
3. **The box model** — content → padding → border → margin (non-negotiable prerequisite: Flexbox is about distributing boxes, so students must know what a box is)
4. **`display: block` vs `inline`** — you can't appreciate `display: flex` until you've seen the default behavior it replaces
5. **Cascade & specificity basics** — why some rules "win"

Last year Flexbox was introduced in class 09 *after* all of the above, and still needed classes 12–15 for practice and review. Skipping ahead is a false economy.

---

## ✅ What students should know after this class

- [ ] Every tag from the checklist above, from memory
- [ ] The difference between relative and absolute paths, and when each breaks
- [ ] Element vs class vs ID selectors, and the `.`/`#` syntax
- [ ] How to spot and fix a missing closing tag
