<div align="center">

# 🎬 SkillTube

### The open, free home for AI skills. Discover. Read. Download. Plug into your assistant.

*Think "YouTube", but instead of videos you browse skills that make AI assistants more capable.*

[![Status](https://img.shields.io/badge/status-early%20development-orange)](#-roadmap)
[![Free](https://img.shields.io/badge/cost-100%25%20free-brightgreen)](#-our-principles)
[![Open Source](https://img.shields.io/badge/open%20source-yes-blue)](#-license)
[![Built by](https://img.shields.io/badge/built%20by-Let's%20Code%20India-ff6b00)](https://github.com/Let-s-Code-India)

</div>

---

## ✨ What is SkillTube?

AI assistants get much more useful when you give them **skills**: small, reusable packages of instructions and files that teach them how to do one job well.

The problem: skills are scattered across thousands of GitHub repositories, and there is no single friendly place to find them.

**SkillTube is that place.** Developers list their skills. Everyone else browses them as simple cards, reads what each skill does in depth, and downloads the ones they like, straight from the developer's own GitHub repository.

> SkillTube does **not** host skill files. Every download goes directly to the developer's repository, so developers stay in control of their work.

---

## 🧭 How it works

**For people who want skills**

1. Open SkillTube and browse the skill cards (image, name, short description, and the developer's name).
2. Click a card to read the full description: what the skill does and how it works.
3. Press **Download**. You are sent to the developer's GitHub repository.
4. Add the skill to your own assistant and start using it.

**For developers who build skills**

1. Sign in with your **GitHub account**. There is no separate password to remember.
2. Add your skill: paste your repository link, then give it a title, a name, a short description, and a long description. An image is optional. If you skip it, a clean letter avatar is made for you.
3. SkillTube checks with GitHub that the repository really belongs to you. Verified skills get a ✔ badge.
4. Edit your skill's details whenever you like from your dashboard.

**Behind the scenes**

Every **6 hours** an automatic catalog job checks every listed skill against GitHub. If a repository has been deleted or made private, the skill is removed from SkillTube automatically. If a repository is renamed, SkillTube follows it and updates the listing.

---

## 🔒 Trust and verification

- **GitHub only.** Sign-in and skills both come from GitHub, which most developers already use.
- **Ownership is checked, not claimed.** SkillTube matches the signed-in GitHub account against the repository's owner on GitHub itself, using permanent numeric IDs rather than names that can change.
- **Always re-checked.** The 6-hour catalog keeps verifying that each repository still exists and still belongs to the same owner.
- **Be careful with third-party skills.** Skills are made by the community. Read what a skill does before adding it to your assistant.

---

## 🧱 Tech stack (all free tiers, no credit card)

| Part | Tool |
|---|---|
| Website | HTML, CSS, JavaScript on **GitHub Pages** |
| Login, database, small files | **Supabase** (GitHub sign-in, Postgres, Row Level Security) |
| Automatic 6-hour catalog | **GitHub Actions** |
| Ownership checks | **GitHub API** |

---

## 🗺️ Roadmap

- [ ] Project setup: Supabase project, database tables, security rules
- [ ] Sign in with GitHub
- [ ] Add a skill with automatic ownership verification
- [ ] Skill cards grid and skill detail page
- [ ] Download button
- [ ] Developer dashboard: edit and delete your skills
- [ ] 6-hour catalog job: verify, rename-follow, and auto-remove missing skills
- [ ] ✔ Verified badge, Report button, and fork labels
- [ ] Trending dashboard: most downloaded and most viewed skills
- [ ] Search and categories

---

## 🧡 Our principles

- **Free forever for everyone.** No paid tools, no subscriptions, no credit card needed to build or run this.
- **Open source.** Built in the open by the community.
- **Developers stay in control.** Your skill lives in your repository. Delete it there and it disappears here.
- **Lightweight.** Designed to be built and run even on modest hardware.

---

## 🤝 Contributing

SkillTube is just getting started, and every kind of help is welcome: ideas, design, code, testing, and writing docs.

1. Open an **Issue** to share an idea or report a problem.
2. Fork the repository and create a branch for your change.
3. Open a **Pull Request** and describe what you changed and why.

Please be kind and respectful to everyone in the project.

---

## 📄 License

Released under the **MIT License**. See the `LICENSE` file for details.

---

<div align="center">

**Made with ❤️ by [Let's Code India](https://github.com/Let-s-Code-India)**

*Free software, built from scratch, for everyone.*

</div>
