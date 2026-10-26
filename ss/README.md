# Saudian Sanomat (SS)

Static news site. Public pages (`index.html`, `article.html`) only *read* `news.json`.

## Adding news
1. Open `admin.html` on the site.
2. Log in with a GitHub fine-grained token that has access to only this repo and
   **Contents: Read and write** permission.
3. Fill in the form and press **Julkaise**. The article (and its photo) are committed
   to the repo and show up on the site in about a minute.

Visitors can't change anything, because publishing requires write access to the GitHub repo.
