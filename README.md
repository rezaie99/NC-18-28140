# NC-18-28140

 
Atlas and Source Codes for image analysis and connectivty calculation for calcium imaging in Zebrafish. This is the supplementary repository for the following paper in Nature Communcation:

Engineering brain activity patterns by neuromodulator polytherapy for treatment of disorders

Mostafa Ghannad-Rezaie, Peter M. Eimon, Yuelong Wu, and Mehmet Fatih Yanik

## Downloading the Atlas
Notice the atlas file is in Git Large File Storage (LFS) repository. You cannot get the file by just downloading the repository. You need a local distribution of Git. To mount the large atlas file please follow this instrctuctions:
### MacOs
Using Brew brew:

```
install git-lfs
```

Using Port 

```
port install git-lfs
```

Altervatively you can download and install the app form:

https://github.com/git-lfs/git-lfs/releases/download/v2.7.1/git-lfs-darwin-amd64-v2.7.1.tar.gz

### Other Operating Systems
#### Downloading

You can install the Git LFS client in several different ways, depending on your
setup and preferences.

* **Linux users**. Debian and RPM packages are available from
  [PackageCloud](https://packagecloud.io/github/git-lfs/install).
* **macOS users**. [Homebrew](https://brew.sh) bottles are distributed, and can
  be installed via `brew install git-lfs`.
* **Windows users**. Git LFS is included in the distribution of
  [Git for Windows](https://gitforwindows.org/). Alternatively, you can
  install a recent version of Git LFS from the [Chocolatey](https://chocolatey.org/) package manager.
* **Binary packages**. In addition, [binary packages](https://github.com/git-lfs/git-lfs/releases) are
available for Linux, macOS, Windows, and FreeBSD.
* **Building from source**. [This repository](https://github.com/git-lfs/git-lfs.git) can also be
built from source using the latest version of [Go](https://golang.org), and the
available instructions in our
[Wiki](https://github.com/git-lfs/git-lfs/wiki/Installation#source).

#### Installing

##### From binary

The [binary packages](https://github.com/git-lfs/git-lfs/releases) include a script which will:

- Install Git LFS binaries onto the system `$PATH`
- Run `git lfs install` to
perform required global configuration changes.

```ShellSession
$ ./install.sh
```

##### From source

- Place the `git-lfs` binary on your system’s executable `$PATH` or equivalent.
- Git LFS requires global configuration changes once per-machine. This can be done by
running:

```ShellSession
$ git lfs install
```
See LFS website for more details:

https://github.com/git-lfs/git-lfs
