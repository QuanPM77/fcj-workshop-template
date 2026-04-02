# Internship Report - Hugo Template

This repository contains the source code for my Internship Report website, built using [Hugo](https://gohugo.io/) and the [Hugo Theme Learn](https://learn.netlify.app/en/).

## Live Website

The compiled website is automatically deployed to GitHub Pages and can be accessed at:
[https://quanpm77.github.io/fcj-workshop-template/](https://quanpm77.github.io/fcj-workshop-template/)

## Prerequisites

To run this site locally, you need to install Hugo Extended:

- [Install Hugo Extended](https://gohugo.io/installation/)
- Git

## Setup and Run Locally

1. **Clone the repository:**
   ```bash
   git clone --recursive https://github.com/QuanPM77/fcj-workshop-template.git
   ```
   *(Note: The `--recursive` flag is used to pull the Hugo theme as a submodule)*

2. **Navigate to the directory:**
   ```bash
   cd fcj-workshop-template
   ```

3. **Start the local development server:**
   ```bash
   hugo server -D
   ```
   The `-D` flag renders articles marked as draft.

4. **View the site:**
   Open your web browser and go to `http://localhost:1313/`

## Production Build

To generate the static HTML files for deployment:

```bash
hugo --minify
```

The generated files will be placed in the `public/` directory.

## Automatic Deployment

This project uses GitHub Pages for hosting. When you push changes to the `main` branch, an automated GitHub Action (or Pages configuration) should build and deploy the application.
