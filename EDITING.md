# Your personal website

Plain HTML + CSS with no build tools. Three files matter:
- `index.html`: all your text. Search it for `EDIT`.
- `style.css`: the look. You can ignore it.
- `cv.pdf`: your CV. Replace it with the final PDF from Overleaf, keeping the same name.

## Put it online (10 minutes, no command line)
1. On github.com, make an account if needed and pick your username carefully. It becomes your URL:
   `https://sibuilds.github.io`.
2. Click **+ → New repository**. Name it **exactly** `sibuilds.github.io`, make it **Public**, and click **Create**.
3. On the new repo page, click **"uploading an existing file"**. Drag in everything from this folder:
   `index.html`, `style.css`, `cv.pdf`, and the `images` folder. (`.nojekyll` is optional.) Click **Commit changes**.
4. Wait about a minute, then open `https://sibuilds.github.io`.
   - If it isn't live yet: repo **Settings → Pages → Build and deployment**, then set Source = *Deploy from a branch*,
     Branch = `main`, folder `/ (root)`, and click **Save**.
5. Replace `sibuilds` / `YOURNAME` in `index.html` with your GitHub and LinkedIn handles,
   and replace "Firstname Lastname" (3 places) with your name.

## Edit it later
Open the file on github.com, click the **pencil icon**, edit the text between the tags, and click **Commit changes**.
The site updates in about a minute.

| I want to... | Do this |
|---|---|
| Add a project | Copy one `<article class="project">…</article>` block and change the text and links |
| Add news | Copy one `<li>…</li>` line in the News list (newest first) |
| Add my photo | Upload a square photo as `images/profile.jpg`, then change `profile.svg` → `profile.jpg` in `index.html` |
| Add a paper | Uncomment the Research section (delete the `<!--` and `-->` around it) and fill in the template |
| Update my CV | Upload the new PDF as `cv.pdf` (replace the old one) |

## Nice extras (later)
- **Custom domain** (around $12 a year, e.g. `yourname.com`): buy one, then add it under Settings → Pages → Custom domain.
- **Google Scholar**: once you have a paper or preprint, make a profile and uncomment the Scholar link.
- **Let Claude push for you**: connect GitHub at claude.ai/connect-github, then start a session with this repo selected.
