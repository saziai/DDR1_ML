# Contributing

- Keep all project paths centralized in `ddr1_config.py`.
- Run notebooks in numerical order and record software versions, input provenance, random seeds, and relevant file hashes.
- Do not commit raw licensed datasets, API credentials, private data, or large generated docking outputs.
- Treat ML and docking results as prioritization evidence until supported by experimental validation.
- If modifying atom mapping or RMSD logic, include a test or diagnostic demonstrating that atom correspondence is chemically valid and that coordinates are not superposed for pose reproducibility.
