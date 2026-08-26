# Drift Versus — privacy policy and credits

The published privacy policy **and credits** for the mobile game **Drift
Versus**, served by GitHub Pages at
<https://mhazki.github.io/drift-versus-privacy/>.

The credits are not an extra: `Sfx/tire_scrub.wav` is derived from a CC BY 3.0
recording, and this page is where that attribution is discharged. The game has
no credits screen; it has a settings row (**ABOUT & PRIVACY**) that opens this
page for every player in every region, which is what makes the attribution
reachable. Removing the Credits section breaks a licence, not a nicety.

This repository exists only to host that one page. It is public because
GitHub Pages requires it on a free plan, and because a privacy policy is
meant to be readable by anyone.

## Do not break the URL

This address is referenced from three places that are expensive to change
once live:

- the App Store listing,
- the Google Play listing,
- the AdMob consent message (Privacy & messaging → European regulations).

So: **do not rename this repository**, and do not make it private — either
one takes the page down and leaves three dead links pointing at it.

Adding a custom domain later is safe: GitHub Pages redirects the
`github.io` address to the custom domain, so existing links keep working.

## The look

There is no Jekyll theme. `_layouts/default.html` and `assets/css/style.css`
are the whole thing: one scrolling column, no sidebar at any width, in the
game's own palette and type (Barlow Semi Condensed, the tokens copied out of
the shell's `Shell.uss`). The page is opened from inside a portrait phone
game, so it is laid out for that and merely gets wider margins on a desktop.
What it does *not* borrow is the game's sheared panel — a wall of legal text
inside leaning boxes reads as a joke. If the game's palette moves, move the
tokens at the top of the stylesheet with it.

## Editing

`index.md` is the page. The authoritative source is `PRIVACY_POLICY.md` in
the game repository, which additionally carries the notes recording what
each clause depends on — the policy was written against the code, and those
notes are what stop it going quietly out of date. **Edit it there first,
then copy the body here**, so the claims and the code stay reviewable
together.
