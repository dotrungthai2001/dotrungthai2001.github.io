# Personal Academic Website of Trung-Thai DO

Welcome to the repository for my personal academic website. This site is built using the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template for Jekyll and is hosted on GitHub Pages. It serves as a central hub for my publications, research projects, and academic activities.

**Live site:** [https://dotrungthai2001.github.io](https://dotrungthai2001.github.io)

---

## How to Manage This Website

This project is managed by updating the files in this repository. Here is a guide to the key files and how to modify them.

### 1. Main Configuration (`_config.yml`)

This is the most important file for personalizing the website. It contains all the site-wide settings and personal information that populates the sidebar and other sections.

To update your information:
-   Open `_config.yml`.
-   Edit fields such as `name`, `description`, `email`, `avatar` (your profile picture), and links to your social and academic profiles (Google Scholar, ORCID, GitHub, LinkedIn, etc.).

### 2. Front Page Content (`_pages/about.md`)

The main landing page of the website is the "About Me" page. To edit its content:
-   Navigate to the `_pages/` directory.
-   Open and edit `about.md` using Markdown syntax.
-   This is where you can write your biography, research interests, and any other introductory information.

### 3. Adding Publications

To add a new publication:
1.  Go to the `_publications/` directory.
2.  Create a new file with the naming convention `YYYY-MM-DD-short-title.md`.
3.  Fill in the file with the necessary YAML front matter, including `title`, `collection`, `date`, `venue`, `paperurl`, and `citation`.

**Example:**
```yaml
---
title: "My New Paper Title"
collection: publications
permalink: /publication/2025-09-01-paper-title
date: 2025-09-01
venue: 'Journal of Awesome Research'
paperurl: 'http://link-to-your-paper.pdf'
citation: 'Your Name, et al. (2025). "My New Paper Title." <i>Journal of Awesome Research</i>.'
---
```

### 4. Adding a CV

1.  Place your CV file (e.g., `cv.pdf`) in the `files/` directory.
2.  Update the link to your CV in the `_pages/about.md` file and/or the `_data/navigation.yml` file to point to `/files/cv.pdf`.

---

## Running the Website Locally

To preview changes on your local machine before pushing them to GitHub, you will need to have Ruby and Jekyll installed.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/dotrungthai2001/dotrungthai2001.github.io.git
    ```

2.  **Install dependencies:**
    ```bash
    cd dotrungthai2001.github.io
    bundle install
    ```

3.  **Serve the website:**
    ```bash
    bundle exec jekyll serve
    ```

4.  Open your web browser and go to `http://localhost:4000` to see your site. The site will automatically update as you save changes to the files.

---

## Acknowledgements

This website is built upon the excellent [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, which was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/).