This is a *personal* repository of fedora buildscripts that allow me to use Fedora
to my specific preferences and needs on my Lenovo Legion Slim 5 14" AMD 7840hs with Nvidia RTX 4060 GPU laptop. It is not intended to be used by anyone else. If you wish to use an image, you can rebase with the following.

### Fedora Silverblue 41 or Nvidia Variant
```bash
rpm-ostree rebase ostree-unverified-registry:ghcr.io/funkemunky/fedora-images/fedora-silverblue:41
rpm-ostree rebase ostree-unverified-registry:ghcr.io/funkemunky/fedora-images/fedora-silverblue:41-nvidia
```

### Fedora Kinoite 41 or Nvidia Variant
```bash
rpm-ostree rebase ostree-unverified-registry:ghcr.io/funkemunky/fedora-images/fedora-kinoite:41
rpm-ostree rebase ostree-unverified-registry:ghcr.io/funkemunky/fedora-images/fedora-kinoite:41-nvidia
```

### Credits and Attributions
This repository uses akmods from https://github.com/ublue-os/akmods to enable certain functionalities.
