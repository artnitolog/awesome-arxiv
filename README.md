# Awesome arXiv

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Project Status](https://img.shields.io/badge/status-active-brightgreen) ![Last Commit](https://img.shields.io/github/last-commit/repo/repo)

This is a list of useful tools, libraries and resources for working with [arXiv](https://arxiv.org/) — online repository for scientific research papers.

<p align="center">
  <img src="assets/awesome-arxiv.png" width="70%" alt="My Image" />
</p>

## Search & Discovery

* **[Papers With Code](https://paperswithcode.com/)** — an open-access platform that bridges the gap between machine learning research papers and their corresponding code implementations. Attaches code repos, benchmarks and SOTA leaderboards.
* **[ResearchRabbit](https://www.researchrabbit.ai/)** — an AI-powered research tool "Spotify for papers" designed to build collections, get algorithmic digests, and explore interactive citation/author graphs.
* **[Emergent Mind](https://www.emergentmind.com/)** — an AI-powered research assistant that helps researchers to explore and stay updated on cutting-edge computer science and AI research, primarily sourced from arXiv. It provides concise summaries, trending paper highlights, and interactive exploration tools like follow-up questions and topic links.
* **[searchthearxiv](https://github.com/augustwester/searchthearxiv)** — a semantic search engine designed to help users explore over 300k machine learning papers from arXiv using natural language queries or by inputting an arXiv link to find similar papers.
* **[ArxivXplorer](https://arxivxplorer.com/)** — a semantic search engine that enhances exploration of the arXiv. The platform also offers a ChatGPT plugin, enabling users to search, read, and reference arXiv papers directly within the chat interface.
* **[paperscape](https://paperscape.org/)** — an open-source project that visualizes the arXiv preprint repository as an interactive map. Each paper is represented as a node, with its size indicating the number of citations and its position determined by citation relationships to other papers.
* **[connectedpapers](https://www.connectedpapers.com/)** — a visual tool designed to help researchers and applied scientists discover and explore academic papers relevant to their field of work.
* **[Semantic Scholar](https://www.semanticscholar.org/)** — a free, AI-powered research tool for navigating in scientific literature. It alows to search and analyze over 200 million scholarly papers across various disciplines, including computer science, neuroscience, and biomedicine.
* **[Litmaps](https://www.litmaps.com/)** — an online research tool designed to enhance the literature review process by visualizing the relationships between academic papers. It allows to monitor scholarly articles through interactive citation maps, known as "litmaps".
* **[Paper Digest](https://www.paperdigest.org/)** — an AI-powered academic research platform designed to assist researchers. It offers tools for generating literature reviews, summarizing research papers, and providing academic writing assistance, all while emphasizing accuracy and minimizing AI-generated inaccuracies.

## Notifications & Recommenders
* **[huggingface Daily Papers](https://huggingface.co/papers)** — a community-curated platform that showcases trending and impactful machine learning research, updated daily by contributors like AK and the broader AI community. Each paper entry includes metadata, links to related models or datasets, and a discussion section where users can engage with authors and peers.
* **[Scholar Inbox](https://www.scholar-inbox.com/)** — a personal paper recommender for researchers, that helps stay up-to-date with the most relevant progress based on personal research interests. Daily indexes all of arXiv, bioRxiv, medRxiv and ChemRxiv and other open access proceedings.
* **[ML Papers of The Week](https://github.com/dair-ai/ML-Papers-of-the-Week)** — a GitHub repository curated that highlights top machine learning research papers on a weekly basis. Each entry includes links to selected papers, often accompanied by brief summaries or annotations.
* **[arXiv_recbot](https://github.com/yuandong-tian/arXiv_recbot)** — a Telegram bot to recommend arXiv papers daily, obtain preference ratings and update the recommender models given the preference ratings.


## SDKs & CLI Tools
* **[arxiv.py](https://github.com/lukasschwab/arxiv.py)** — a popular lightweight Python wrapper for the arXiv API. Allows search and retrieval of paper metadata and downloading PDFs.
* **[ArXiv MCP Server](https://github.com/blazickjp/arxiv-mcp-server)** — a Model Context Protocol server for searching and analyzing arXiv papers, providing a bridge between AI assistants and arXiv articles. Enables access to search, download and analyze papers. Supports integration with various AI assistants.
* **[cli-arxiv](https://github.com/knguyenanhoa/cli-arxiv)** — a CLI tool for for exploring arXiv, allowing to search, download, and manage research papers directly from the terminal. Texts from PDFs are auto-converted and are used to recommend future articles.
* **[arXivScraper](https://github.com/Mahdisadjadi/arxivscraper)** — a Python scraper designed to retrieve metadata from arXiv based on specified categories and date ranges. Supports custom filtering by subcategories, authors, titles, and abstracts.
* **[arxiv-dl](https://github.com/MarkHershey/arxiv-dl)** — a highly-opinionated CLI tool for downloading papers. Priorities ease of use for researchers.
* **[Docling](https://github.com/docling-project/docling)** - a Python toolkit for advanced document conversion and analysis, particularly suited for processing arXiv papers and other scholarly documents. Efficiently parses pdfs into richly structured formats like Markdown, JSON, or HTML.

## Reading & Browser Enhancers
* **[arxiv-utils](https://github.com/j3soon/arxiv-utils)** — a browser extension that enhances the reading experience on arXiv. Introduces a set of features: renames the title of PDF page to the paper's title, adds navigation hotkeys, fixes pdf name on download, open papers in extra services, compatible with other tab plugins.
* **[PaperMemory](https://github.com/vict0rsch/PaperMemory)** — a powerful minimalist browser extension that automatically tracks and organizes the research papers. As an automated reference manager, it automatically detects and records papers you open, finds associated code repositories, adds convenient on-page tools.
* **[Explainpaper](https://www.explainpaper.com/)** — an AI-powered tool that simplifies academic research papers. Allows to upload PDFs, highlight complex sections, and receive a clear explanation.
* **[SciSpace Copilot](https://scispace.com/)** — an AI-powered research assistant (web tool and browser extension) that helps to read and understand papers faster. Provides a chat workflow with any arXiv paper.
* **[arxiv2notion](https://github.com/denkiwakame/arxiv2notion)** — a Chrome extension that allows to save arXiv papers directly into Notion databases. Captures metadata such as title, authors, abstract, publication date, and comments. Supports integration with Notion templates and offers Notion AI autofill and formula-based enhancements.
* **[Elicit](https://elicit.com)** — an AI research assistant that helps automate tasks like literature reviews, data extraction, and summarization using over 125M academic papers. It enables users to ask research questions, extract data from PDFs (including tables), and generates summaries with source citations.


## Datasets
* **[Arxiver Dataset](https://huggingface.co/datasets/neuralwork/arxiver)** — more than 63k papers converted to multi-markdown format, published between January 2023 and October 2023. The dataset includes original metadata such as IDs, titles, abstracts, authors, publication dates. Available under a CC BY-NC-SA 4.0 license.
* **[MINT-1T (arXiv)](https://huggingface.co/datasets/mlfoundations/MINT-1T-ArXiv)** — a multimodel dataset comprising approximately 600,000 papers, designed to support large-scale multimodal pre-training tasks. This is a subset of the [MINT-1T collection](https://github.com/mlfoundations/MINT-1T), released under CC-BY-4.0 license.
* **[Cornell University arXiv Dataset](https://www.kaggle.com/datasets/Cornell-University/arxiv/data)** — over 1.7M scholarly articles across STEM fields. Includes title, authors, abstract, categories, and links to the full-text PDFs (the dataset doesn't contain parsed papers directly). CC0 1.0 license.
* **[arXiv Paper Abstracts](https://www.kaggle.com/datasets/spsayakpaul/arxiv-paper-abstracts)** — dataset introduced for multi-label text classification. Contains paper titles, abstracts, and subject categories. Released under CC0 1.0 license.
* **[S2ORC](https://github.com/allenai/s2orc)** — a comprehensive dataset comprising over 81.1M academic papers, including arXiv. Provides rich metadata, paper abstracts, resolved bibliographic references, and full text for 8.1M open access papers. Available under ODC-By 1.0.
* **[unarXive](https://github.com/IllDepence/unarXive)** — a structured dataset of 1.9M arXiv LaTeX papers including full text, references, captions, mathematical notation preserved as LaTeX. It supports tasks like citation recommendation and IMRaD classification, with an open subset and full version available upon request. MIT license.
* **[SciEvo](https://github.com/Ahren09/SciEvo)** — a large-scale dataset designed to support scientometric research and the study of scientific knowledge evolution. Provides a collection of over 2M publications,  including detailed metadata and citation graphs. Available under the Apache 2.0 license.
* **[arxiv-summarisation](https://huggingface.co/datasets/ccdv/arxiv-summarization)** —  a large-scale dataset designed for training and evaluating abstractive summarization models on scientific papers, comprising over 431k articles with corresponding abstracts.
* **[Multimodal ArXiv](https://mm-arxiv.github.io/)** — a dataset designed for large vision-language models. It comprises two subsets: ArXivCap, a figure-caption dataset containing 6.4M images and 3.9M captions, and ArXivQA, a QA dataset generated by prompting GPT-4V based on scientific figures with 100k questions. CC BY-NC-SA 4.0 license.
* **[ArxivFormula](https://github.com/microsoft/ArxivFormula)** — a dataset for mathematical formula detection as a combined task of formula entity detection and relation extraction. It includes 600k document images sourced from arXiv papers. Available under the MIT license.

## Not working anymore

* * **[labml papers](https://papers.labml.ai/)** — lightweight arXiv feed focused on trending ML papers. Adds two-line summaries, social-media, similar-paper links.
* * **[arxiv-sanity-live](https://github.com/karpathy/arxiv-sanity-lite)** — a user-friendly interface for exploring arXiv papers, offering features such as tagging and personal recommendations.

## Unsorted
* https://alphasignal.ai/
* https://magazine.sebastianraschka.com/
* https://github.com/TideDra/zotero-arxiv-daily
* https://github.com/Vincentqyw/cv-arxiv-daily
* https://github.com/liutaocode/TTS-arxiv-daily
* https://koaning.github.io/arxiv-frontpage/

## License

This list is dedicated to the public domain under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.