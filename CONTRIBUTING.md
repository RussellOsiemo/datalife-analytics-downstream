# Contributing to DataLife Analytics Downstream

The organization-wide
[contribution rules](https://github.com/datalife-ehealth/.github/blob/main/CONTRIBUTING.md)
apply here. Analytics contributions must also be reproducible and honest about data,
uncertainty, and intended use.

## Before implementation

Open a focused issue or RFC describing the research question, data contract, legal or
consent basis, expected output, evaluation design, and non-use cases. Use synthetic or
explicitly licensed de-identified data only. Never commit a private dataset merely
because it has had obvious identifiers removed.

## Reproducibility checklist

- Compare with a meaningful simple baseline.
- Prevent subject and temporal leakage.
- Pin dependencies and random seeds where relevant.
- Report uncertainty, calibration, subgroup results, and negative results.
- Move reusable notebook logic into tested modules.
- Clear notebook outputs and local paths before committing.
- Add a model card or study report for material results.

## Pull requests

Keep one experiment or infrastructure concern per pull request. Link its issue or
RFC and provide exact reproduction commands. Generated artifacts and large files do
not belong in Git. Approval from the repository steward is required.
