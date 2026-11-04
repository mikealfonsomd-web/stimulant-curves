# Stimulant curve comparator

Modelled plasma curves, dose equivalence and patient modifiers for long-acting
stimulants. Curves are built from label Tmax and half-lives: they show shape,
not measured plasma levels.

## Publish on GitHub Pages

1. Create a new repository, public, no README.
2. Upload every file in this folder to the root of the repository.
3. Settings > Pages > Source: Deploy from a branch > main > / (root) > Save.
4. Wait a minute or two. The URL appears on that same page.

Open that URL in Chrome on the phone and choose "Install app". The icon and
offline mode come from manifest.json and sw.js, which need a real domain:
they do not work when the file is opened from local storage.
