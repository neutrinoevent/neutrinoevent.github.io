------

## 🛠️ How to Create & Publish Posts on Your Jekyll Blog

### 📄 1. **Create a New Markdown Post Locally**

All blog posts live in the `_posts/` directory. They **must follow** this filename format:

```
YYYY-MM-DD-title-of-post.md
```

For example:

```
_posts/2025-06-01-electric-fields-healing.md
```

Start it with **YAML front matter** like this:

```markdown
---
layout: post
title: "Electric Fields and Healing"
tags: [bioelectricity, healing, pemf]
---

This is your post body in Markdown. You can use:

- **Headings:** `## Subheading`
- **Lists, links, images**
- **LaTeX math** (if enabled)
```

------

### 🚀 2. **Preview the Site Locally**

In your repo root:

```bash
bundle exec jekyll serve
```

Then go to `http://127.0.0.1:4000` in your browser.

------

### 📤 3. **Push Changes to GitHub Pages**

After editing or creating posts:

```bash
git add _posts/2025-06-01-electric-fields-healing.md
git commit -m "Add new post on electric fields and healing"
git push origin main
```

Give it 30–60 seconds, then check your site at:
 👉 `https://neutrinoevent.github.io`

------

## 🔮 Next Steps You Can Take

Since dark mode is already working, here are powerful enhancements we can explore next:

------

### 🔧 1. **Homepage Redesign / Hero Intro**

Right now your site loads into the latest post. We could instead create:

- A **hero section** introducing *Elektonik*
- Short descriptions of core topics: PEMF, bioelectricity, brain modulation, etc.
- A **"Recent Posts"** feed below that
- Clean grid, Helvetica vibe, maybe with subtle animations

Example intro block:

> **Elektonik** explores the cutting edge of electricity in biology — from regenerative medicine to human performance enhancement.

------

### 🧱 2. **Topic/Category Pages**

Helps organize posts and establish this as a deep scientific archive.

How it works:

- Posts get tagged (e.g. `tags: [pemf, regeneration]`)
- We generate tag index pages:
  - `elektonic.com/tags/pemf`
  - `elektonic.com/tags/voltage-gated-channels`
- Sidebar or header nav links to them

Bonus: We can even auto-generate tag pages dynamically if you want.

------

### 🧠 3. **Write or Expand a Scientific Post**

Right now your post is short — I can help you develop a full, cited article.

Examples:

- **“Bioelectric Fields and Regeneration”** (expanded to cover research, diagrams, applications)
- **“Electricity and the Mind: A Survey of Neurostimulation”**
- **“What Is PEMF and Why It Matters”**

I'll write the Markdown if you want.

------

### 🌐 4. **Set Up Favicon + Metadata**

Make the site look professional on browser tabs and in social previews:

- Custom favicon
- Open Graph/Twitter cards for posts
- Better title/description metadata

------

### 🧰 5. **Enhance Layout: Sidebar or Header**

Current layout is minimal (which is good), but we can:

- Add a fixed **sidebar** with links to core topics
- Or a clean **header/nav bar** with Elektonik title and dropdowns

------

