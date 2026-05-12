# GitHub Pages Publishing

The participant website used by GitHub Pages lives in the repository-root `docs/` folder.

The workshop source copy also exists at `arabic-studies-nlp-workshop/docs/`. When publishing through GitHub Pages from a branch, GitHub can serve only `/docs` at the repository root, so the deployable copy must be kept at root-level `docs/`.

## What the Website Includes

- workshop overview;
- setup instructions;
- six-hour schedule;
- participant materials overview;
- glossary and readings;
- instructor profile.

The site is intentionally participant-facing. Instructor notes, timing notes, teaching backup plans, and solution outlines remain outside `docs/`.

## Publish With GitHub Pages

1. Push this repository to GitHub.
2. Open the repository on GitHub.
3. Go to `Settings > Pages`.
4. Under `Build and deployment`, choose `Deploy from a branch`.
5. Select the branch, usually `main`.
6. Select `/docs` as the publishing folder.
7. Save.

GitHub will publish the participant website from the repository-root `docs/`.
