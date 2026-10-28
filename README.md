# ARABSAT email images

## Purpose

This repository is the public host for images used in ARABSAT emails. Mail programs
(Outlook, Gmail, mobile apps) download the images from the web addresses (URLs) below.

## URL formats

- GitHub Pages: `https://ghazalman.github.io/arabsat-img/images/email/v1/<file>`
- jsDelivr (pinned to a release tag): `https://cdn.jsdelivr.net/gh/ghazalman/arabsat-img@<tag>/images/email/v1/<file>`

The catalogue page at https://ghazalman.github.io/arabsat-img/ lists every image with its URLs.

## How to add an image

1. Prepare the image for email:
   - PNG with a transparent background.
   - Made at 2x the display size (for example 300x113 px for a logo shown at 150x56).
   - As small as possible (aim for under 50 KB; the hard limit is 100 KB).
   - File name with only lowercase letters, digits and hyphens, for example `arabsat-logo-white-email.png`.
2. Upload it to the current version folder (`images/email/v1/`), or to a new folder such as `images/email/v2/`.
3. Open a pull request, wait for the checks to pass, then merge.
4. Open the catalogue page and copy the URL from there.

## The golden rule

**Never rename, replace, move or delete a published image, and never make the repository
private.** Emails already in customers' inboxes load images from these URLs, so any of these
actions makes the images disappear from old emails. To change an image, add a new file name
or a new version folder, then update the URL in the sending system. The automatic checks
reject changes to existing files.

## Caching

Gmail and Outlook cache images, so a change is only seen reliably under a new URL.

## Rights notice

The images are trademarks and brand assets of the Arab Satellite Communications Organization
(ARABSAT). They are published only so ARABSAT emails can display them, and may not be reused.
