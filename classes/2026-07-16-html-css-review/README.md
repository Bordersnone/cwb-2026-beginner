# HTML & CSS Review + Practice

> **📌 Post-class note:** in this class we got through the quiz and the answer review — the page build moved to the [next class](../2026-07-21-guided-page-build/), where we do it step by step together.

Welcome back! Today is all about making the basics stick: a quick warm-up quiz, then building a page that uses **everything** you've learned so far.

---

## 📚 Quick Links

- [Today's Plan](#-todays-plan)
- [In-Class Build: "My Favorite Things"](#-in-class-build-my-favorite-things)
- [Reference Links](./resources.md) — the W3Schools & MDN pages for everything we cover today
- [Homework](#-homework)
- [What You Should Know](#-what-you-should-know-after-this-class)
- [Next Class](#-next-class)

---

## 📝 Today's Plan

1. **Warm-up quiz** — [quiz.md](./quiz.md). It's **not graded**! It just shows us (and you) what's solid and what needs another look. Honest blanks beat lucky guesses.
2. **Review together** — we'll go through the answers as a group. Be ready to explain *why*, not just *what*.
3. **Build!** — everyone makes a "My Favorite Things" page from scratch (checklist below).

---

## 🔨 In-Class Build: "My Favorite Things"

Build a single page from scratch that uses **every element we've covered**. Check items off as you go:

- [ ] One `<h1>` page title, and at least two `<h2>` section headings
- [ ] An `<hr>` separating the sections
- [ ] A paragraph with at least one `<b>` and one `<i>` word
- [ ] An **unordered list** of at least 3 favorite things
- [ ] An **ordered list** (e.g., top 3 movies, ranked)
- [ ] An image loaded with a **relative path** (put it in an `images/` folder!)
- [ ] One **absolute link** to a real website, and one **relative link** to a second page (`page2.html` — it can be nearly empty for now)
- [ ] A `<pre>` block (a tiny ASCII drawing is a fun option)
- [ ] At least one HTML comment labeling a section
- [ ] A `<style>` block with: one **element selector**, one **class selector** used on 2+ elements, and one **ID selector**

**Stuck on a tag?** Don't wait — look it up in the [reference links](./resources.md). Looking things up is what real developers do all day.

### 🔥 Challenge Round (finished early? keep going)

In order — each one is harder than the last:

1. **Descendant selector:** add a `ul li` rule that styles only your list items
2. **External stylesheet:** move all your CSS out of the `<style>` block into a `style.css` file, connected with `<link rel="stylesheet" href="style.css">` — the page should look *identical* after the move
3. **Box it up:** give one section a `background-color`, `padding`, and a `border` — then open DevTools and look at the box model diagram to see your padding
4. **Side by side:** make your two lists sit next to each other using `display: inline-block` on their containers

(The links for all of these are in [resources.md](./resources.md) under Challenge Round.)

---

## 🏠 Homework

Extend your "My Favorite Things" page:

1. Fill in `page2.html` as a real second page (use the same checklist), and make sure the two pages **link to each other**.
2. Add a class named `.highlight` and apply it to your three favorite items across both pages.
3. **Mistake hunt:** deliberately break your page in 3 ways (remove a closing tag, break an image path, misspell a selector), look at what happens in the browser, then fix it. Write the 3 mistakes as HTML comments at the bottom of the page.

Why item 3? Knowing what *broken* looks like is half of fixing it — this is how you build debugging instincts.

---

## ✅ What You Should Know After This Class

- [ ] Every tag from the build checklist, from memory
- [ ] The difference between relative and absolute paths, and when each one breaks
- [ ] Element vs class vs ID selectors, and the `.`/`#` syntax
- [ ] How to spot and fix a missing closing tag

---

## 🔜 Next Class

We start giving your pages some real style: where CSS can live (inline, internal, external), text and color properties, and the **box model** — the foundation for building layouts.
