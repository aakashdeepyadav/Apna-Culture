# Apna-Culture

Apna-Culture is a static website project created for the CBP26 Heritage and Culture theme.

## Project Structure

This repository now uses a flat structure at the project root:

Apna-Culture/

- index.html
- about.html
- contact.html
- gallery.html
- style.css
- gallery.css
- map.png
- diagram.png

The Git repository root is `Apna-Culture`, and all website source files live at the root.

## Local Preview

Open `index.html` in your browser.

## Static Site Deployment (GitHub Pages)

This project is configured to deploy from the repository root using GitHub Actions.

1. Push code to the `main` branch.
2. In GitHub repo settings, open Pages and set source to `GitHub Actions`.
3. The workflow will publish the static site automatically.

## Notes

- Navigation pages are plain HTML/CSS with no build step required.
- Gallery backgrounds use stable hosted image URLs so deployment works without missing local asset folders.
