# GitHub Profile Setup — Anurag Verma

1. Create or open the public GitHub repository `anuragverma16/anuragverma16`.
2. Upload the **contents** of this ZIP into the repository root (not the enclosing folder). Keep `.github/workflows/snake.yml` and `assets/` paths intact.
3. The banner and a decorative animated snake preview work immediately because both SVG files are included locally. The preview is **not** your actual contribution history.
4. In repository Settings → Actions → General → Workflow permissions, enable **Read and write permissions** for GITHUB_TOKEN (if the setting is available), then Save. Repository rulesets or branch protection may also block workflow pushes.
5. Open Actions → **Update GitHub Contribution Snake** → Run workflow. The action generates a real contribution snake from `anuragverma16` and commits it to `assets/github-contribution-grid-snake.svg` on the default branch.
6. Refresh your GitHub profile after the workflow completes. It runs daily after that. If the action fails, inspect the Actions run log and check permissions and branch protection.
7. Update featured project links to their actual repositories. Other third-party stats images can occasionally fail independently of this setup.

Note: the banner is an original SVG replacement for the missing `github_PJ_McDonnell_shutterstock.jpg`; if you own that original image, you can upload it and change the README path back.
