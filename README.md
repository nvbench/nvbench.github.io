# NV-Bench Demo Page

Demo page for **NV-Bench**: Benchmarking Nonverbal Vocalization Synthesis in Expressive Text-to-Speech Models.

## Links

- **Demo**: [https://nvbench.github.io](https://nvbench.github.io)
- **Code**: [https://github.com/nvbench/NV-Bench](https://github.com/nvbench/NV-Bench)
- **Dataset**: [https://huggingface.co/datasets/AnonyData/NV-Bench](https://huggingface.co/datasets/AnonyData/NV-Bench)
- **NVASR Model**: [https://huggingface.co/AnonyData/Multilingual-NVASR](https://huggingface.co/AnonyData/Multilingual-NVASR)

## Local Preview

```bash
# Any static file server works, e.g.
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Structure

```
├── index.html          # Main page
├── style.css           # Styles
└── static/
    ├── overview.png    # Pipeline figure
    └── example*/       # Audio samples (prompt, GT, model outputs)
```
