# Nelsen Apps website

This is the public GitHub Pages site for **Nelsen Apps**, including information about Hanami Sudoku and future mobile games.

## Publish

In repository **Settings > Pages** choose **Deploy from a branch**, **main**, **/(root)** and Save.

URLs after Pages is live:

- https://nelsenapps.github.io/
- https://nelsenapps.github.io/privacy/
- https://nelsenapps.github.io/support/
- https://nelsenapps.github.io/app-ads.txt

The static site uses HTML/CSS, with no custom workflow or analytics scripts.

## Privacy policy approach

Use **one company-wide Nelsen Apps Privacy Policy** at `/privacy/` for common practices, with an **App-specific information** section identifying the actual data practices of every released Nelsen Apps game.

Currently listed: **Hanami Sudoku** (device-local progress/stats, Google Mobile Ads/UMP, no accounts or Nelsen Apps cloud sync).

For each new game before store submission:

1. Review actual production app and third-party SDK data collection, use and sharing, retention and deletion, target audience, permissions, and consent controls.
2. Add an app-specific section (or link a separate supplement for material differences).
3. Confirm its Google Play Data safety and Apple App Privacy declarations are consistent with this policy.
4. Verify the policy URL is accessible in the app and in the applicable store listing. Do not assume a generic policy alone covers new behavior.

## Release checklist

- [ ] Enable GitHub Pages on main / root; verify all public links.
- [ ] Obtain an approved public support/privacy email address and replace the temporary public GitHub Issues-only contact mechanism.
- [ ] Verify policy coverage with final Android/iOS SDK configuration and any child-directed audience choices.
- [ ] Link the privacy policy from Hanami Sudoku Settings and Google Play Console.
- [ ] Confirm the exact `app-ads.txt` line from AdMob, rather than relying solely on the initial entry.
- [ ] Update the homepage's coming-soon label after launch.
