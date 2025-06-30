# ExplorerIO Documentation

Welcome to the central documentation hub for **ExplorerIO**, an open‑source tool to navigate and manage files across multiple cloud storage services.

ExplorerIO offers a unified interface for AWS S3 (initial release) and will soon support Google Drive, Dropbox, OneDrive, and Azure Blob.

---

*This README serves as a placeholder. Detailed, navigable guides and flowcharts will be added to <https://exploreriodocs.gelonezi.com/>.*

---

## Prerequisites

* `Python 3.13.5` and `pip` (for MkDocs)

### Development Setup

1. Install MkDocs, Material theme, and plugins:

   ```bash
   pip install -r ./src/requirements.txt
   ```

2. From the project root, start a local preview:

   ```bash
   mkdocs serve -f ./src/mkdocs.yml
   ```

---

This repository uses [MkDocs](https://www.mkdocs.org/) (configuration defined in `src/mkdocs.yml`) to generate a static site with a navigable sidebar.
