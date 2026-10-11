# Akarsh K Nair — academic website

A build-free, responsive website for https://akarshkongassery.github.io.

## Publish

1. Extract this ZIP and upload its contents to the root of the repository `akarshkongassery/akarshkongassery.github.io`.
2. In Settings → Pages choose Deploy from a branch → main → /(root), then save.
3. Open index.html locally to review the site. GitHub Pages will provide the live deployment status.

No build, package installation, or API keys are required. Inter loads from Google Fonts; a system sans-serif fallback works offline.

## Add your photographs

All current images are deliberately labelled placeholders.

1. Put your photo in `assets/photos/`, e.g. `sutd.jpg`.
2. Find `src="assets/photos/sutd.svg"` in index.html and activities.html. Change it to `src="assets/photos/sutd.jpg"`.
3. Replace the alt text with a description of the actual photo, and edit the caption with the date, host, event title, and topic as appropriate.
4. Repeat for the other photos. Use lowercase filenames without spaces and match their extensions exactly.

| Placeholder | Replace on these pages |
| --- | --- |
| portrait.svg | index.html, research.html, publications.html |
| sutd.svg | index.html, activities.html |
| agder.svg | index.html, activities.html |
| lboro.svg | index.html, activities.html |
| cambridge.svg | activities.html |
| invited-01.svg | index.html, activities.html |
| invited-02.svg | index.html, activities.html |
| invited-03.svg | activities.html |

Photo cards crop using object-fit: cover. Adjust object-position in styles.css if the subject is not centered. Suggested sizes: portrait at least 700 × 880; activity photos at least 900 × 600. Compress JPEGs to around 150–400 KB when practical.

## Add visits or invited sessions

In activities.html copy an entire `<article class="activity-card">…</article>` inside the relevant activity-grid. Change the image src, alt text, category, heading, and caption. Add the photo file in assets/photos. The grid automatically wraps. Feature only your favourite few activities on index.html; the Activities page can contain the full collection.

## Add achievements

Edit the achievement-template card in index.html and activities.html. Replace its badge, heading, and description with your actual achievement and remove the achievement-template class to give it the regular styling. Copy an achievement article to add more. Delete the template card if you do not need it.

## Content

Current role, publications, appointments, and fellowship outcomes follow the supplied CV. SUTD and Cambridge entries are visit placeholders, with dates and details to be added by you. Invited sessions are templates with no invented event details. Fellowship selection and shortlisting are explicitly distinguished. No citation metrics or unconfirmed awards have been added.

The Scholar link in the CV was incomplete; this version links to DBLP and ORCID. Publication links use only DOI identifiers provided in the CV. The supplied CV is included unchanged in assets/akarsh-cv.pdf.

## Files

- index.html: profile, selected activities, achievements, publications, appointments.
- research.html: research themes, patent applications, service.
- publications.html: selected papers.
- activities.html: visit gallery, invited sessions, achievements.
- styles.css: typography, colour, responsive layout.
- assets/photos/: replaceable photo placeholders.
