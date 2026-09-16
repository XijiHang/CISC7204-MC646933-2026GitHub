# CISC7204 Assignment 01 — Xiji Hang

**Submitted by:** Xiji Hang (MC646933).  
**Laboratory collaborators:** Xiji Hang (MC646933) and Xiaoyu Guo (MC648131). All laboratory work is joint.  
**Deadline:** 20 September 2026, 23:00, Macao time (UTC+8).

## Start here

For detailed Chinese reading and submission instructions, open [中文文件说明与提交指南](00_中文文件说明与提交指南_MC646933.html). It is a local reference document and is not an assignment attachment.

Open `submission_text/README.md`, review your twelve executed notebooks and individual proposal, then follow `submission_text/Submission_Checklist.md`. Each student must use their own Moodle account and [Class C SUPPORT Moodle](https://ummoodle.um.edu.mo/course/view.php?id=46674). This package contains prepared materials; it is not a record of an online submission.

## Package contents

| Folder or file | Contents |
|---|---|
| `00_中文文件说明与提交指南_MC646933.md` / `.html` | Personal Chinese explanation of files and submission steps; local reference only |
| `notebooks/` | Twelve executed notebooks named for Xiji Hang and MC646933 |
| `notebook_previews/` | HTML exports generated from these personalized notebooks |
| `proposals/` | Your individual English Word proposal |
| `datasets/raw/` | Eight unchanged source CSV snapshots |
| `datasets/provenance.json` | Source URLs, access dates and SHA-256 hashes |
| `datasets/processed/` | Derived CSVs from the import and cleaning exercises |
| `results/` | Insurance and housing extension metric CSVs |
| `screenshots/` | 93 genuine screenshots organized by module |
| `submission_text/` | Final screenshot posts, notebook-upload posts, formal submission text and checklist |
| `submission_text/Requirement_Coverage.md` | Question, subquestion and guided-task links to exact images |
| `screenshots/index.csv` | Page-by-page image, notebook, requirement and discussion-title index |
| `build/m04_m05/exports/` | The guided Module 05 CSV output only; no build scripts |
| `environment_requirements.txt` | Recorded Python-library versions |
| `package_manifest.json` | Validation counts and artifact inventory |
| `SHA256SUMS.txt` | SHA-256 checksums for every other packaged file |

## Reproduce the analysis locally

The notebooks were executed with **Python 3.14.6 in Anaconda**. Exact library versions are recorded in `environment_requirements.txt`; this documents the working environment rather than silently installing packages inside the notebooks.

1. Extract the complete ZIP and retain the folder structure.
2. Open the package folder in Anaconda/JupyterLab. Select a Python kernel with the listed libraries.
3. Open a notebook in `notebooks/`, restart its kernel and run all cells in order.
4. The dataset locator accepts the bundle root, the `notebooks/` folder, or a flat folder containing a notebook and its required raw CSV. The provided bundle already contains all eight inputs.
5. Rerunning import/cleaning work writes to `datasets/processed/`. Module 06 writes its metric CSVs to `results/`; Module 05 Lab01 writes a guided copy to `build/m04_m05/exports/`. The raw CSVs are not overwritten.

For a separate environment, install the recorded requirements before opening JupyterLab:

```sh
python -m pip install -r environment_requirements.txt
python -m jupyter lab
```

The HTML previews show the saved results without executing code. Notebook code, outputs and execution counts were retained during personalization. The notebooks report which scores are in-sample, held out, or development diagnostics; do not compare different evaluation protocols as if they were the same test.

## Submission essentials

- Post all **93 screenshot pages** covering **71 requirement groups**, one forum discussion per image, using `submission_text/Screenshot_Posts.md`.
- Upload each module’s two personal notebooks in the corresponding Class C forum. Optionally add the two matching HTML previews and two raw CSV inputs (six attachments total; forum limit: 10 files, 200 MB per file).
- Submit the Module 06 practice notebook with `medical_insurance_dataset.csv` and the final notebook with `kc_house_data_NaN.csv` to their separate formal assignments.
- Submit the individual Word proposal to the proposal assignment. The three formal assignments allow 20 files and 200 MB per file; use the exact 2, 2 and 1 required files. Complete these formal submissions before working through the screenshot discussions.
- Review all content personally and retain the source credits, joint-work statement and AI-use acknowledgement.

The two tourism studies are proposed future research, not completed tourism analyses. This package includes only your individual proposal.
