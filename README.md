# GEO-Risk Demo Project Page

This is a static anonymous project page for the paper:

**Who Defines the AI's Answer? Assessing the Vulnerability of LLMs to Malicious Generative Engine Optimization**

The package contains a webpage, demo figures, a paper PDF placeholder, and a JSON file with demo result data.

## Folder Structure

```text
.
├── index.html
├── styles.css
├── .nojekyll
├── assets/
│   ├── paper.pdf
│   ├── workflow_geo_base_clean.png
│   └── figures/
│       ├── workflow_geo.png
│       ├── controlled_case_comparison_ctrip_en.png
│       ├── model_method_success_bar.png
│       └── realworld_chat_collage_v3_en.png
└── data/
    ├── demo_results.json
    ├── a6000_case_sample.json
    └── a6000_case_outputs.txt
```

## Local Preview

Open `index.html` directly in a browser, or run:

```powershell
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Upload to GitHub

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. Commit the files.
4. Optional: enable GitHub Pages in `Settings -> Pages`.

If GitHub Pages is enabled, select:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/root`

## Use with anonymous.4open.science

1. Upload this folder to a GitHub repository.
2. Open `https://anonymous.4open.science/`.
3. Paste the GitHub repository URL.
4. Add anonymization terms if needed.
5. Use the generated anonymous link in the submission.

## Notes for Anonymous Review

- The current page does not include author names, institutions, emails, or personal links.
- Check `assets/paper.pdf` before submission and replace it with the correct anonymized manuscript if needed.
- If additional code or data is added later, remove file paths, usernames, commit metadata, and comments that may reveal identity.
- `data/a6000_case_outputs.txt` contains a raw paired output sample, and `data/a6000_case_sample.json` contains the same sample in a structured form for webpage display and later processing.
