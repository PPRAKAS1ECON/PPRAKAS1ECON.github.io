# Prabuddha Prakash – academic website

A plain HTML website. No build tools, no themes. Everything lives in `index.html`.

## Folder contents

| Path | What it is |
|---|---|
| `index.html` | The whole website (all five tabs) |
| `images/headshot.jpg` | Photo on the Home tab |
| `images/headshot_original.jpg` | Unretouched backup of the photo |
| `files/CV_Prakash.pdf` | CV shown on the CV tab |
| `files/Research_Statement_Prakash.pdf` | Research statement |
| `files/Teaching_Statement_Prakash.pdf` | Teaching statement |
| `files/Teaching_Evaluations_Spring2026_Rutgers.pdf` | Full Spring 2026 evaluation report |

## Publish on GitHub Pages (one time, about 15 minutes)

1. Create a free account at github.com. Your username becomes your web address,
   e.g. username `prabuddhaprakash` gives `https://prabuddhaprakash.github.io`.
2. Click **+** (top right) > **New repository**. Name it exactly
   `YOURUSERNAME.github.io`, set it to **Public**, and click **Create repository**.
3. On the next screen click **uploading an existing file**. Drag in everything
   from this folder (`index.html`, `README.md`, and the `images` and `files`
   folders). Click **Commit changes**.
4. Go to **Settings > Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, Branch to **main** and **/(root)**, then **Save**.
5. Wait one or two minutes and open `https://YOURUSERNAME.github.io`.

## Edit text (job market paper, papers, courses, anything)

1. In your repository, click `index.html`, then the **pencil icon** (Edit).
2. Press Ctrl+F (Cmd+F on Mac) and search for `EDIT:`. Each section is marked,
   e.g. `EDIT: JOB MARKET PAPER`, `EDIT: PUBLISHED PAPERS`, `EDIT: UNDER REVIEW`.
3. Change the text between the tags. To add a paper, copy an existing
   `<li class="paper"> ... </li>` block and change its contents.
4. Click **Commit changes**. The live site updates in about a minute.

## Update your CV

Your CV lives at `https://YOURUSERNAME.github.io/files/CV_Prakash.pdf`. Every CV
button on the site points there, and you can paste that link into applications:
it always opens the newest version.

**After you edit your CV in Overleaf (about 30 seconds):**
1. In Overleaf, click the **Download PDF** icon above the preview.
2. Rename the file to exactly `CV_Prakash.pdf`.
3. In your GitHub repository, open the `files` folder > **Add file** >
   **Upload files**, drop in the PDF, and click **Commit changes**. It replaces
   the old file, and the site updates within a minute or two.

**Why not link Overleaf directly?** A free Overleaf account has no permanent
link to the compiled PDF. Its read-only share link opens the Overleaf editor
rather than a clean PDF, and it cannot be shown inside the website. If you ever
want that anyway, paste the read-only link into `CV_URL` near the bottom of
`index.html`; the CV tab then shows an "Open CV" button instead of the viewer.
Fully automatic syncing needs Overleaf's paid GitHub integration.

**Google Drive alternative.** Paste a Drive share link ("Anyone with the link")
into `CV_URL`. Update it with right-click > **File information > Manage
versions > Upload new version** so the link never changes.

## Replace the photo or a PDF

Upload a file with exactly the same name into `images/` or `files/`.
`images/headshot_original.jpg` is your photo without retouching. To use it,
rename it to `headshot.jpg` and upload it.
