STATISTICS LAB — MOBILE + CRITICAL VALUES UPDATE

This package updates four existing tools and the homepage.

Recommended individual file replacements in your repository:
  index.html
  normal-curve/index.html
  t-distribution/index.html
  confidence-interval/index.html

The unchanged normal-distribution/index.html is included only for a full-site bundle; if the latest rainbow calculator is already working, do not replace it.

Existing URLs remain exactly the same, so MyOpenMath embeds should not break.

Changes:
 - Renamed the two CI critical-value explorers on the homepage and within their titles.
 - Added one-tap 80/90/95/98/99% confidence presets and readable z*/t*, area, tail values.
 - Improved mobile handle hit areas and keyboard-adjustable behavior; t sample-size field is phone-friendly.
 - Confidence Interval Calculator uses larger inputs, two-column mobile sample output, accessible interval-endpoint summaries, and scrolls to output after Compute on phones.
 - Light, Dark, and Auto themes preserved.
 - No hypothesis-testing mode activated yet. Future mode should provide one-/two-sided significance levels and rejection regions; this version remains CI-focused.
