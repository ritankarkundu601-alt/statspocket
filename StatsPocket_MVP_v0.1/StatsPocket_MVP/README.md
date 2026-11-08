# StatsPocket MVP

A zero-dependency, mobile-friendly statistics toolkit.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in Chrome, or use VS Code's Live Server extension (optional).

## Included in v0.1
- Descriptive statistics: count, mean, median, mode, variance, standard deviation, quartiles, range, IQR.
- Binomial and Poisson point probabilities.
- Normal cumulative probability P(X ≤ x).
- Pearson correlation and simple least-squares linear regression.
- A frequency chart for the descriptive-statistics dataset.

## Publish free with GitHub Pages
1. Create a new public GitHub repository named `statspocket`.
2. Upload `index.html` to the repository root.
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL will be shown in Settings → Pages.

No API keys, backend, paid hosting, or Vercel account are required for this MVP.

## Notes
This is an initial MVP, not a validated statistical package. Quartiles use linear interpolation at `(n−1)p`; document this convention when presenting results. Verify calculations against trusted references before relying on them for assessed or professional work.
