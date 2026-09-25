# Muhammad Hassan – Personal Portfolio

A multi-page personal portfolio built with plain HTML and CSS for **CS313 Web Engineering, Lab 3 (HTML Advanced – Personal Portfolio II)**.

**Live site:** https://muhammadhassan-10.github.io/portfolio/

## Pages

| Page | Content |
|------|---------|
| `index.html` | Home: introduction, profile photo, personal details |
| `skills.html` | Technical skills, spoken languages, soft skills, projects |
| `hobbies.html` | Football, gym, coding and reading, with photos |
| `gallery.html` | Image gallery of 6 photos |
| `contact.html` | Contact details and a message form |

## Folder structure

```
portfolio/
├── index.html
├── skills.html
├── hobbies.html
├── gallery.html
├── contact.html
├── css/
│   └── style.css
├── images/
│   ├── profile.jpeg
│   ├── football.jpg
│   ├── gym.jpg
│   ├── coding.jpeg
│   ├── lib.jpeg
│   └── travel.jpeg
└── README.md
```

## What changed from Lab 2

- All styling moved from internal `<style>` blocks and inline `style=""` attributes into one external stylesheet, `css/style.css`, linked from every page.
- The navigation menu is a list of links floated left so they line up horizontally.
- Layouts use `float` and `clear` in place of flexbox:
  - Home: the profile photo floats left and the introduction wraps beside it.
  - Hobbies: images alternate between `float: left` and `float: right`.
  - Skills and Contact: two columns built with floated `.col-half` blocks.
  - Gallery: three floated items per row; the first item of each row uses `clear: left`.
- A `.clearfix` class on containers and a `.clear` spacer (`clear: both`) stop floats from breaking the layout.
- Files are organised into `css/` and `images/` folders.
- No JavaScript and no CSS frameworks.

## Running locally

Open `index.html` in any web browser.

---
© 2026 Muhammad Hassan · BS Data Science, NUST
