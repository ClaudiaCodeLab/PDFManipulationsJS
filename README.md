# PDF Tools for Manipulation (Offline and Online)

## Introduction

This project was developed to provide tools for manipulating PDF files directly in the browser without needing to upload files to a server. It offers functionalities such as merging and cutting PDFs, with the option to work entirely offline if the necessary JavaScript libraries are downloaded and placed in a local `/js` directory.

The main goal is to give users control over their PDF files locally, ensuring privacy and eliminating the need to rely on external servers for PDF manipulation. This project is intended for academic purposes, and the licenses of any external libraries used in the project should be respected.

## Features

- **PDF Cutter (Online and Offline)**: Allows users to select specific pages from a PDF and create a new PDF with just those pages.
- **PDF Merge (Online and Offline)**: Allows users to merge multiple PDFs into a single document. The order of files can be adjusted using a drag-and-drop interface.

## Getting Started

### Online Version
The online versions of the tools require an active internet connection to load external libraries such as `pdf-lib`, `downloadjs`, or `Sortable`. These versions are easy to use without any additional setup.

### Offline Version
The offline versions of the tools work without an internet connection. To use them, you need to download the required JavaScript libraries and place them in a `/js` directory located in the same folder as the HTML files.

#### Steps for Offline Use:
1. Download the necessary JavaScript libraries and place them in a `/js` directory.
2. Ensure the `/js` directory is in the same location as the HTML files (`PDFCutterOffline.html` and `PDFMergeOffline.html`).
3. Open the HTML files in your browser, and the tools will function without an internet connection.

### Repository Structure

- `/js`: Directory where the required JavaScript libraries (e.g., `pdf-lib.min.js`, `download.js`, `Sortable.min.js`) should be placed for offline use.
- `PDFCutter.html`: Online version of the PDF Cutter tool.
- `PDFCutterOffline.html`: Offline version of the PDF Cutter tool.
- `PDFMerge.html`: Online version of the PDF Merge tool.
- `PDFMergeOffline.html`: Offline version of the PDF Merge tool.
- `index.html`: Overview page that links to each of the tools, explaining their functionalities.

## External Libraries

This project uses external libraries for handling PDF manipulation and UI interactions. The following libraries are utilized:
- [pdf-lib](https://pdf-lib.js.org/) (for PDF manipulation)
- [downloadjs](https://github.com/rndme/download) (for downloading files)
- [Sortable](https://github.com/SortableJS/Sortable) (for drag-and-drop functionality)

These libraries are licensed under their respective licenses, and their use should comply with those terms.

## Contributions

Contributions to this project are welcome! Whether you're improving the existing functionality, fixing bugs, or adding new features, feel free to submit a pull request.

### How to Contribute:
1. Fork this repository.
2. Create a new branch with your feature or fix.
3. Submit a pull request explaining your changes.

## License

This project is for academic purposes, and all external libraries included should be used in accordance with their respective licenses. Please ensure compliance with the license terms of any libraries you use.
