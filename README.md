# Anandhu P S – Portfolio

A static, single-file portfolio (HTML and CSS, no build step, no dependencies).

## Run locally

Open `index.html` in a browser. Or serve it:

```bash
cd portfolio
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Customize

Everything is in `index.html`.

- **Text and projects:** edit the content inside each `<section>`. Copy an `<article class="proj">` block to add a project.
- **Resume:** replace `Anandhu_PS_Resume.pdf` with a newer PDF of the same name to update the download button.
- **Project links:** add `<a href="https://github.com/Anandhu114/REPO">View code</a>` inside a project once you have repository URLs.
- **Colors and fonts:** change the variables at the top of the `<style>` block (`:root`). A dark theme is defined right below it.
- **Pipeline strip in the hero:** edit the five `<div>` items inside `.pipe`.

## Deploy

1. Create a GitHub repository and upload the contents of this folder.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Framework preset: **Other**. Leave build command and output directory empty. Deploy.
4. Add the live link to your resume, LinkedIn and GitHub profile.
