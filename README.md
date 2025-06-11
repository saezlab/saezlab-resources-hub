# Saez-Rodriguez Group - Resource Hub

A centralized resource hub tailored for researchers at the Saez-Rodriguez Lab and the wider Heidelberg University bioinformatics community — providing structured guidelines, code templates, and best practices to support the development of reproducible, sustainable, and high-quality computational tools for systems biology and biomedical research.


## Run this locally
1. Clone the repository 
```bash
git clone https://github.com/saezlab/saezlab-resources-hub.git
```

2. Retrieve all GitHub submodules
```bash
git submodule update --init --recursive
```

3. Create and activate a virtual environment with uv
```bash
uv venv
source .venv/bin/activate
```

4. Install dependencies
```bash
uv pip install ."[docs,dev]"
```

5. Run the MkDocs website locally
```bash
mkdocs serve
```

## License

[**MIT License**](./LICENSE)