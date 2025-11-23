# SPDX AI Working Group

Welcome to the SPDX AI Working Group website repository. This technical working group focuses on developing and maintaining the AI and Dataset profiles of the SPDX specification.

## About

The SPDX AI Working Group is dedicated to creating standards for documenting artificial intelligence systems and datasets in a standardized format. Our work enables transparency, reproducibility, and compliance in AI development through standardized Bill of Materials (BOM) practices.

## Website

Visit our website at: https://spdx-ai.github.io/spdx-ai/

## Quick Links

- [Meeting Minutes](https://github.com/spdx/meetings/tree/main/ai) - Access our regular meeting notes and recordings
- [Examples](https://github.com/spdx/spdx-examples) - View practical examples of SPDX AI and Dataset profiles
- [Linux Foundation AI BOM Whitepaper](https://www.linuxfoundation.org/research/ai-bom) - Read our comprehensive whitepaper
- [arXiv Research Paper](https://arxiv.org/abs/2510.07070) - Academic publication on AI BOM

## Local Development

This website is built using [MkDocs](https://www.mkdocs.org/) with the [Material theme](https://squidfunk.github.io/mkdocs-material/).

### Prerequisites

- Python 3.8 or higher
- pip

### Setup

1. Clone the repository:
```bash
git clone https://github.com/spdx-ai/spdx-ai.git
cd spdx-ai
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the development server:
```bash
mkdocs serve
```

4. Open your browser and navigate to `http://127.0.0.1:8000/spdx-ai/`

### Building

To build the static site:
```bash
mkdocs build
```

The built site will be in the `site/` directory.

## Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the `main` branch via GitHub Actions.

## Contributing

We welcome contributions! If you'd like to improve the website or add content:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Submit a pull request

## License

See the [LICENSE](LICENSE) file for details.

## Contact

For questions or to get involved:

- Join our [meetings](https://github.com/spdx/meetings/tree/main/ai)
- Visit the main [SPDX website](https://spdx.dev/)
- Join SPDX mailing lists and community channels
