# 📄 PDF Mo Ito

**PDF Mo Ito** is a modern, responsive, and privacy-focused client-side web application designed to handle everyday document manipulation tasks directly in your browser. No server uploads, no data tracking, and lightning-fast execution.

🌐 **Live Demo:** [View Live Site](https://kyle-intia.github.io/pdf-mo-ito/)

---

## ✨ Features

### 1. Combine & Reorder PDFs
* **Multi-Format Merging:** Combine multiple PDF files and images (JPG, PNG, WEBP, BMP) into a single unified PDF document.
* **Interactive Page Canvas:** Drag and drop pages to rearrange their sequence easily using **SortableJS**.
* **Page-Level Controls:** Rotate individual pages (or all at once), duplicate specific pages, or remove unwanted ones.
* **Custom Customization:** Optionally add professional touch-ups such as custom page numbering, header text, and diagonal watermark text.

### 2. PDF to Image Converter
* **Page Extraction:** Extract any PDF page into image formats (**JPEG**, **PNG**, or **WEBP**).
* **DPI & Quality Presets:** Choose from standard web viewing up to print-scale resolutions (72 DPI, 150 DPI, 200 DPI, 300 DPI) with custom quality compression sliders.
* **Batch Downloading:** Download individual converted pages or bundle an entire document's pages into a clean **ZIP archive** instantly via **JSZip**.

### 3. Images to PDF
* **Flexible Layouts:** Convert a batch of image files into a PDF document.
* **Page Customization:** Choose target page sizes (A4, US Letter, or auto-fit image dimensions), orientation modes (Portrait, Landscape, Auto), and margin paddings.

---

## 🔒 100% Privacy & Offline-First
All file processing happens **locally inside your web browser** using client-side JavaScript libraries. Your sensitive documents, contracts, and personal photos are **never** uploaded to any external server.

---

## 🛠️ Built With

* **Tailwind CSS** (via CDN) – Modern utility-first styling with automatic Dark Mode support.
* **PDF.js** – Mozilla's robust library for parsing and rendering PDF files in the browser.
* **pdf-lib** – Powerful client-side JavaScript library for creating and modifying PDF documents.
* **JSZip** – For packaging extracted images into ZIP archives.
* **SortableJS** – For smooth drag-and-drop page reordering interfaces.
* **Lucide Icons** – Clean, lightweight SVG icon toolkit.

---

## 🚀 Running Locally

Because this project is built using vanilla HTML, CSS, and JavaScript with CDN dependencies, you don't need complex build steps or Node.js to run it locally:

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/kyle-intia/pdf-mo-ito.git](https://github.com/kyle-intia/pdf-mo-ito.git)
