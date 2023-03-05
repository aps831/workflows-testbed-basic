# Basic Template

## Usage

To use this repository as a template run
`gh repo create <repo_name> --clone --private -p aps831/basic-template`.

Replace `--private` with `--public` as necessary.

Once cloned:

-   delete `.github` directory
-   rename `github-private` directory to `.github`
-   merge `github-public` directory into `.github` if a public repo, otherwise delete
-   update `username` and `repositoryname` in `.github/workflows/bitbucket-mirror.yaml`
-   update `.github/dependabot.yml`
-   run the init script `init.sh`
-   delete the init script `init.sh`
-   update `README.md`
-   update `LICENCE.md` if a public repo
