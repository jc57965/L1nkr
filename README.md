# L1nkr

Please follow the instructions below to finish the setup of your new L1nkr site.

## Installation

1) Add a LICENSE to your repo.
2) Clone your version of the template to your local computer:
```shell
git clone https://github.com/jc57965/L1nkr
```
3) Modify `config/_default/hugo.yaml` and `config/_default/params.yaml` according to your needs. Find more info on the theme [wiki](https://github.com/chrede88/L1nkr/wiki/Configuration).
4) Build a local version of your site by executing `hugo server` at the root of the repository. You can see the site by navigating to `http://localhost:1313/L1nkr/` (actual URL will be outputted in the CLI) in a browser.

---

## Configuration

See the [wiki](https://github.com/chrede88/L1nkr/wiki) for all info about configuration.

---

## Update the Theme Version

The theme version used to build the site is defined in `go.mod` file.

The best practice is to update to released and tested versions. To update to a specific version execute the following command in a terminal/commandline (at the root path of your site repo):

```shell
  hugo mod get github.com/chrede88/L1nkr@vX.Y.Z
```
Replace X,Y & Z with the corresponding version numbers. You can find the releases [here](https://github.com/chrede88/L1nkr/releases). Please check if any breaking changes are listed under the release you want to update to, before proceeding.

