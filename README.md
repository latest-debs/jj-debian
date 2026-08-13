![jj for Debian](.github/readme-header.png)

# jj for Debian

[jj-vcs/jj](https://github.com/jj-vcs/jj) — A Git-compatible VCS, powered by Jujutsu —
packaged for Debian as part of [latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install jj
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/jj-debian/releases) page:

```sh
sudo dpkg -i jj_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64, armhf, i386, ppc64el, riscv64, s390x — whichever
  architectures jj-vcs/jj actually publishes a Linux binary for

## Disclaimer

Unofficial packaging only. For issues with jj itself, see
[jj-vcs/jj](https://github.com/jj-vcs/jj).
