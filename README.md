# 🎛️ Techno & EDM Festival

A responsive festival website built with PHP, SCSS, HTML, and JavaScript, featuring a dynamic event layout with a festival lineup, gallery, ticket packages, and multimedia content.

## 🎶 What is Techno & EDM Festival?

Techno & EDM Festival is a web project designed around a fictional electronic music festival in San Juan, Dominican Republic.

The website presents the festival through a visually focused interface that combines a video hero section, event information, artist schedules, a gallery area, and ticket packages. The project was adapted to PHP while maintaining a modern frontend workflow based on SCSS, JavaScript, NPM, and Gulp.

The application is deployed and publicly accessible through Wasmer.

## 📌 Features

* 🎧 Techno & EDM festival landing page
* Festival hero section with background video
* Festival date and location information
* Two-day artist lineup
* Separate Techno and EDM stages
* Artist schedules organized by day and time
* Festival gallery section
* One-day and two-day ticket packages
* Responsive frontend layout
* SCSS-based styling
* JavaScript asset processing and minification
* Image optimization and format generation
* PHP-based page entry point

## ☝️ Festival Lineup

The website includes two festival days with separate Techno and EDM stages.

### Friday 21

**Techno**

* Adam Beyer
* Carl Cox
* HI-LO
* Amelie Lens
* CamelPhat
* ARTBAT

**EDM**

* David Guetta
* Tïesto
* Martin Garrix
* Steve Aoki
* Afrojack
* Vintage Culture

### Saturday 22

**Techno**

* Reinier Zonneveld
* Eric Prydz
* Deadmau5
* Joris Voorn
* Nina Kraviz
* Argy

**EDM**

* Armin Van Buuren
* Calvin Harris
* Hardwell
* Above & Beyond
* Diplo
* Steve Angello

## 🎫 Ticket Packages

The interface includes two ticket options:

### One-Day Pass

Includes:

* Access to both stages
* Unlimited drinks
* Event shirt / wristband

Price displayed by the website: **$100**

### Two-Day Pass

Includes:

* Access to both stages
* Unlimited drinks
* Event shirt / wristband
* VIP access

Price displayed by the website: **$180**

> The ticket section is a frontend presentation. The repository does not implement an online payment or ticket purchasing system.

## 🤖 Tech Stack

* **PHP** — Application entry point and server-side integration
* **HTML5** — Page structure and content
* **SCSS / Sass** — Stylesheet development
* **JavaScript** — Client-side functionality
* **NPM** — Package and development dependency management
* **Gulp** — Development and production build automation
* **Terser** — JavaScript minification
* **Sharp** — Image processing and optimization
* **Google Fonts** — Montserrat typography
* **Wasmer** — Deployment
* **Git** — Version control

## 🚣 Build Workflow

The project uses Gulp to automate several development and production tasks.

The build process handles:

* SCSS compilation
* JavaScript minification
* Gallery thumbnail generation
* Image processing
* WebP generation
* AVIF generation
* Output organization inside the `build` directory

The repository defines separate development and build commands through NPM.

## 🏗️ Project Structure

```text
technoAndEDMFestival/
├── api/
├── build/
│   ├── css/
│   ├── img/
│   └── js/
├── src/
│   ├── img/
│   ├── js/
│   └── scss/
├── video/
├── index.php
├── gulpfile.js
├── package.json
├── package-lock.json
├── vercel.json
└── .gitignore
```

## 📸 Image Optimization

The Gulp workflow uses Sharp to process project images and generate optimized formats.

The build process can generate:

* JPEG
* WebP
* AVIF

It also creates resized gallery thumbnails for the project.

## 🚀 Deployment

The project is deployed as a PHP-based web application.

**Live Demo:**

https://technoandedmfestival-michaelacostadev.wasmer.app/

The deployed version exposes the main festival experience, including the lineup, gallery, ticket section, and multimedia presentation.

## 🔮 Purpose

This project demonstrates practical frontend and web development skills while working with a PHP-based application and a modern asset compilation workflow.

It also provides experience with:

* SCSS architecture and compilation
* JavaScript optimization
* Automated asset processing
* Responsive web interfaces
* Multimedia integration
* PHP deployment
* NPM and Gulp workflows

## 🧑‍💻 Author

Developed by **Michael Acosta**.

* LinkedIn: https://www.linkedin.com/in/michael-acosta-dev/

## 🌐 Support the Project

If you find the project useful or want to explore the implementation:

* ⭐ Star the repository
* Follow me on GitHub
* Connect with me on LinkedIn

Thanks for checking out the project.
