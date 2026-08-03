# Koinexus Info Pages

Static pages for GitHub Pages.

## Published URLs

After GitHub Pages is enabled for this repository, these pages will be available at:

- Privacy Policy: https://alexnwanganga.github.io/koinexus-info/privacy-policy/
- Email Verification: https://alexnwanganga.github.io/koinexus-info/email-verification/

The existing root URL also still serves the privacy policy:

- https://alexnwanganga.github.io/koinexus-info/

## GitHub Pages Setup

1. Push these files to the repository's default branch.
2. Open the repository on GitHub.
3. Go to Settings > Pages.
4. Under "Build and deployment", set "Source" to "Deploy from a branch".
5. Select the default branch and the root folder, then save.
6. Wait for the Pages deployment to finish.

GitHub Pages serves each folder's `index.html` as a clean URL, so `privacy-policy/index.html` becomes `/privacy-policy/` and `email-verification/index.html` becomes `/email-verification/`.

## Custom Domain Target

To make the email verification page available at:

- https://www.koinexus.app/koinexus-info/email-verification/

configure `www.koinexus.app` as the custom domain for the GitHub user site repository, usually `alexnwanganga.github.io`, and keep this `koinexus-info` repository published as a project site without its own custom domain.

If `www.koinexus.app` is configured directly on this `koinexus-info` repository instead, GitHub Pages will serve this repository at the domain root and the page will usually be:

- https://www.koinexus.app/email-verification/
