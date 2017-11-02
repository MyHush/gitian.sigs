This repository contains Gitian signatures for [Hush](https://github.com/MyHush/hush).

It should be updated on each release.

If you have 2FA on your github account, you'll need an auth token to push your sigs from within the vagrant VM.
Another way is to copy them into a clone of this repo on your local computer before pushing:

`vagrant scp :/home/vagrant/gitian.sigs/v1.0.12 ~/MyHush/gitian.sigs/`