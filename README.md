# AgeDB

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FAgeDB-181717?logo=github)](https://github.com/biometric-community/AgeDB)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://ibug.doc.ic.ac.uk/resources/agedb/)

**AgeDB** — tbiom catalog packaging for `agedb` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/AgeDB
- **Upstream source**: https://ibug.doc.ic.ac.uk/resources/agedb/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `agedb` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | https://ibug.doc.ic.ac.uk/resources/agedb/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Request / Google Drive link from authors (AgeDB-30 protocol common).

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/AgeDB.git
cd AgeDB
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_agedb.sh
```

Place licensed archives under `projects/datasets/agedb/` (gitignored).

## Dataset structure

```text
AgeDB/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://ibug.doc.ic.ac.uk/resources/agedb/
- Packaging: https://github.com/biometric-community/AgeDB/issues
