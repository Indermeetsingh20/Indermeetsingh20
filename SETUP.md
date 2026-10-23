# Publish this GitHub profile

The profile repository already exists at `Indermeetsingh20/Indermeetsingh20`. Add the files from this folder to its default branch while preserving the same directory structure.

## Files to upload

- `README.md`
- `assets/header.svg`
- `assets/avatar.png`
- `.github/workflows/snake.yml`

## Activate the contribution animation

1. Open the repository's **Actions** tab.
2. Select **Generate contribution animation**.
3. Choose **Run workflow**.
4. Wait for the run to finish and create the `output` branch.
5. Refresh the public profile. The light/dark contribution animation will then appear.

The workflow runs daily and also whenever its workflow file is pushed to `main`.

## Optional personal links

The profile currently links only to GitHub because no email, portfolio, or LinkedIn URL was provided. Add verified contact links under the `Let's connect` section when ready.

## Notes

- Keep the repository public.
- Keep the repository name identical to the username: `Indermeetsingh20`.
- GitHub Actions must have permission to write repository contents. The workflow requests only `contents: write` so it can publish the generated SVG files to the `output` branch.
