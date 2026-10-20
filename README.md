# Resume Studio — GitHub Pages deployment

Deployment-ready export of the resume builder, version 3.0. No build or API key is needed. All JavaScript and the PDF engine are bundled in site/index.html. Default sample identity is generic for public distribution.

## Publish after connecting GitHub
1. Create or select the intended repository. Public repository contents are visible to everyone. GitHub Free supports Pages in public repositories; private-repository availability depends on the plan.
2. Commit the contents of this package, including .github/workflows/pages.yml, to the main branch.
3. In repository Settings > Pages, set the source to GitHub Actions.
4. Run the included workflow (or push another commit). The completed deployment reports the live URL.

A repository named USERNAME.github.io normally uses https://USERNAME.github.io/. Other repositories normally use https://USERNAME.github.io/REPOSITORY/. Replace USERNAME and REPOSITORY with the real account and repository names; these are examples, not an existing live site.

## Existing profiles
Browser storage belongs to each website origin. Before moving from the previous site or desktop edition, use My resumes > Backup all resumes, then restore the JSON on the GitHub Pages site. No profile data is automatically transferred.

## Included behavior
Six single-column resume formats; editable Word, text and direct PDF export; job keyword matching; multiple profiles; cover-letter drafting; local backup and restore. Direct PDF supports English/WinAnsi text. For other scripts, use browser printing with headers and footers disabled. Tailoring is rule based. This package does not contain a server, shared accounts, cloud profile storage or a paid AI integration.

## Third-party notice
The MIT-licensed pdf-lib library is included. Its original license is retained in site/PDF-LIB-LICENSE.md. The app source is provided without assigning a new open-source license to the user's application code.

Workflow reference: https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages
