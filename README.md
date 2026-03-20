# merge-train sandbox
Sandbox repository for RMS-26 validation.

## Security hook bootstrap
Run `mise install` to install `lefthook` and `gitleaks`; postinstall runs `lefthook install` automatically.

## Sandbox workflow secret
The sandbox merge-train workflow uses the repository secret `MERGE_TRAIN_TOKEN` for action authentication.
