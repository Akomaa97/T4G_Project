# T4G_Project — The Love Project Website

A 7-page responsive website for **The Love Project**, an orphanage-support charity providing children with safe housing, education, and mentorship.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `pages/about.html` | About Us |
| `pages/programs.html` | Our Children & Programs |
| `pages/volunteer.html` | Get Involved (Volunteer) |
| `pages/donate.html` | Donate & Sponsor |
| `pages/gallery.html` | Gallery & Stories |
| `pages/contact.html` | Contact Us |

## Project Structure

```
T4G_Project/
├── index.html
├── pages/
│   ├── about.html
│   ├── programs.html
│   ├── volunteer.html
│   ├── donate.html
│   ├── gallery.html
│   └── contact.html
├── css/
│   └── style.css        # single shared stylesheet for all pages
├── images/               # add real photography here (see note below)
├── js/                   # reserved for future interactivity
└── README.md
```

## Tech Used

- Semantic HTML5
- One shared CSS file (`css/style.css`) using CSS variables for the brand's
  design system (colors, spacing, radius) so every page stays visually consistent
- [Font Awesome 6](https://fontawesome.com/) (via CDN) for icons
- Google Fonts: Poppins (headings) + Lora (body)

## Design System

- **Colors:** Forest Green `#2E6F5E`, Warm Amber `#E8A33D`, Warm Off-White `#F4F1EA`,
  Charcoal `#2B2B2B`, Soft Sky Blue `#A9C9CA`
- **Type:** Poppins for headings, Lora for body copy
- **Layout:** 12-column concept, 8px spacing scale, 12px rounded corners on
  images/cards, consistent header + footer on every page

## Images

Photo, avatar, and gallery spots currently use soft gradient placeholders
(`.ph` class in `style.css`) instead of real photography, since no images were
supplied. Drop real images into `/images` and replace the placeholder `<div>`s
with `<img src="images/your-file.jpg" alt="...">` tags when ready.

## Running Locally

No build step required — just open `index.html` in a browser, or serve the
folder with a simple local server:

```bash
npx serve .
```

## Pushing to GitHub as T4G_Project

This folder is already a git repository with an initial commit. To push it to
GitHub:

```bash
git remote add origin https://github.com/<your-username>/T4G_Project.git
git branch -M main
git push -u origin main
```

(Create the empty `T4G_Project` repository on GitHub first, without a README,
then run the commands above from inside this folder.)
