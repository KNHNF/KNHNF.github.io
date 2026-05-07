
# Karan Homayounfar — Personal Portfolio

![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-blue)
![Repo Size](https://img.shields.io/github/repo-size/KNHNF/KNHNF.github.io)

This repo contains the source for my personal portfolio site.  
I built it with **Quarto** because I wanted something clean, lightweight, and easy to maintain, while still giving me full control over the layout and styling.

The site includes my projects, a bit about me, and ways to get in touch.  
It’s intentionally simple — fast to load, easy to navigate, and focused on the content.

🔗 Live site: https://KNHNF.github.io

---

## What’s inside

The site is made up of a few Quarto pages:

- `index.qmd` — the homepage  
- `about.qmd` — who I am and what I do  
- `projects.qmd` — a selection of my work  
- `contact.qmd` — how to reach me  

Styling is handled through `styles.css`, and Quarto handles the build process automatically.

Everything gets rendered into the `docs/` folder, which GitHub Pages uses to publish the site.

---

## Tech I used

- **Quarto** for generating the site  
- **Markdown / QMD** for content  
- **CSS** for styling  
- **GitHub Pages** for hosting  

No JavaScript or frameworks — just a clean static site.

---

## Project structure

```
root/
│── .quarto/          # Quarto system files
│── docs/             # Built site (GitHub Pages serves this)
│── index.qmd         # Home page
│── about.qmd         # About page
│── projects.qmd      # Projects page
│── contact.qmd       # Contact page
│── styles.css        # Custom styling
│── _quarto.yml       # Site configuration
│── README.md
│── LICENSE
│── Karan.jpg
│── profile.jpg
```

---

## Working on it locally

If you want to run the site yourself:

1. Install Quarto: https://quarto.org  
2. In the project folder, run:

```
quarto preview
```

This starts a local server and updates automatically when you edit files.

To build the site manually:

```
quarto render
```

The output goes into the `docs/` folder.

---

## Contact

If you want to connect or collaborate:

- GitHub: https://github.com/KNHNF 
- LinkedIn: https://www.linkedin.com/in/karan-homayounfar
- Email: karanhomayounfar2@gmail.com

---

## License

This project is under the **MIT License**.
```
