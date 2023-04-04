# Kifusion-Image
An actually usable version of Fedora Kinoite, applying all the relevant patches to make it great out of the box.

Goal is to build custom and up-to-date images that combine the stability and fast updates from Fedora, but without their restrictions and opinionated Decisions. This Image is of course opinionated too, so we try to keep changes relevant, but without needing to layer almost any packages. This brings stability and fast updates, as layering decreases performance intensely.

## Install it:

from your existing Kinoite install run

```
rpm-ostree rebase --custom-origin-url XXX
```

You may want to run `ostree admin pin 0` first, if you want to keep your existing image as a backup.
