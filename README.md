# Prabuddha Prakash – academic website

Live at https://pprakas1econ.github.io

All files sit together on the main page of the repository. There are no folders.

| File | What it is |
|---|---|
| `index.html` | The whole website (all five tabs). Your photo is stored inside it. |
| `CV_2026_Prakash.pdf` | CV (CV tab and every CV button) |
| `Research_Statement_Prakash.pdf` | Research statement |
| `Teaching_Statement_Prakash.pdf` | Teaching statement |
| `TeachEvals_Spring2026_Prakash.pdf` | Spring 2026 teaching evaluations |

## Update a PDF (for example, a new CV from Overleaf)

1. Name the new file exactly as in the table above. Capital letters matter.
2. On the repository's main page, click **Add file > Upload files**, drop the
   file in, and click **Commit changes**. It replaces the old one.
3. Wait a minute, then hard-refresh the site (Ctrl+Shift+R, or Cmd+Shift+R on Mac).

Direct CV link for applications: https://pprakas1econ.github.io/CV_2026_Prakash.pdf

## Edit text

1. Click `index.html`, then the **pencil icon** (Edit).
2. Press Ctrl+F (Cmd+F on Mac) and search for `EDIT:`. Each section is marked,
   e.g. `EDIT: PUBLISHED PAPERS`, `EDIT: UNDER REVIEW`, `EDIT: COURSES TAUGHT`.
3. Change the text, then click **Commit changes**.

## Rename a PDF

If you ever give a PDF a different name, the website link must change too:
in `index.html`, search for the old name and replace it with the new one.

## Change the photo

Upload the new photo to the main page (e.g. `photo.jpg`). In `index.html`, find
the photo (search for `class="portrait"`) and replace the long
`src="data:image/jpeg;base64,..."` value with `src="photo.jpg"`.
