# Clubria/homebrew-tap

The Homebrew tap for [riabuild](https://github.com/Clubria/riabuild), Clubria's
developer provisioner.

```sh
brew install clubria/tap/riabuild
```

There is no `brew tap` step. Homebrew derives a repository name from the tap
name `clubria/tap`, the name it derives is `Clubria/homebrew-tap`, and this
repository is it — so the tap is cloned on first install without being asked
for.

## Nothing here is written by hand

`Formula/riabuild.rb` is rendered from `packaging/homebrew/riabuild.rb` in
[Clubria/riabuild](https://github.com/Clubria/riabuild) and pushed here by that
repository's release workflow, once per release. **An edit made directly to
this repository is overwritten by the next release** — change the template
over there instead.

riabuild is also published for Debian, Ubuntu, Fedora and RHEL. Those
instructions are in the [riabuild
README](https://github.com/Clubria/riabuild#readme).
