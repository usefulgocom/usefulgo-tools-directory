<div align="center">

# UsefulGo (`usefulgo.com`)

### ⚡ 240+ Free Online In-Browser Web Utilities & Productivity Tools
**No Sign-ups Required • No Monthly Paywalls • No Watermarks • 100% Private**

[![Website](https://img.shields.io/badge/Official-usefulgo.com-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://usefulgo.com?utm_source=github&utm_medium=readme)
[![Tools Count](https://img.shields.io/badge/Tools-240%2B%20Available-brightgreen?style=for-the-badge)](#-explore-tools-by-category)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Docker Ready](https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#-self-hosting--docker)
[![Next.js 16](https://img.shields.io/badge/Next.js-16%20App%20Router-black?style=for-the-badge&logo=next.js)](https://nextjs.org)

[**Visit UsefulGo**](https://usefulgo.com?utm_source=github&utm_medium=readme) • [**Browse All Tools**](https://usefulgo.com?utm_source=github&utm_medium=readme#tools) • [**Play Browser Games**](https://usefulgo.com/games?utm_source=github&utm_medium=readme) • [**Report an Issue**](https://github.com/phuc-huy/usefulgo.com/issues)

</div>

---

## 💡 What is UsefulGo?

**[UsefulGo.com](https://usefulgo.com)** is an open-access, all-in-one web utility platform engineered for developers, students, content creators, and remote teams. 

Most online tools today trap users behind restrictive paywalls, forced email registrations, file limits, or intrusive watermarks. **UsefulGo eliminates the friction**:
- 🚫 **Zero Sign-Up Required:** Use every utility instantly in your browser.
- 🔒 **High Privacy & In-Browser First:** Client-side processing where possible; uploaded files are securely purged immediately after processing.
- ⚡ **Lightning Fast:** Built with Next.js 16, Go, FastAPI, and Sharp microservices for high-throughput image and document processing.

---

## 🗂️ Explore Tools by Category

Below is a curated index of popular utilities available on [usefulgo.com](https://usefulgo.com):

### 📄 Document & PDF Tools
| Tool | Description | Direct Link |
|:---|:---|:---:|
| **Background Remover** | AI-powered automatic photo cutout and background eraser | [Launch Tool](https://usefulgo.com/tools/background-remover) |
| **Compress PDF** | Reduce PDF file size while retaining crystal-clear quality | [Launch Tool](https://usefulgo.com/tools/compress-pdf) |
| **Merge PDF** | Combine multiple PDF files into one clean document | [Launch Tool](https://usefulgo.com/tools/merge-pdf) |
| **Extract Text from PDF** | Instant text extraction from non-scanned PDF files | [Launch Tool](https://usefulgo.com/tools/extract-text-from-pdf) |
| **Document Scanner** | Digital document scanner directly using your device camera | [Launch Tool](https://usefulgo.com/tools/document-scanner) |
| **Excel to PDF** | Fast spreadsheet to PDF format conversion | [Launch Tool](https://usefulgo.com/tools/excel-to-pdf) |
| **Images to PDF** | Convert JPG, PNG, WebP into a single multi-page PDF | [Launch Tool](https://usefulgo.com/tools/images-to-pdf) |

### 🖼️ Media & Image Utilities
| Tool | Description | Direct Link |
|:---|:---|:---:|
| **AI Photo Restorer** | Restore old, blurry, or noisy photos automatically | [Launch Tool](https://usefulgo.com/tools/ai-photo-restorer) |
| **AI Object Remover** | Erase unwanted objects, text, and watermarks cleanly | [Launch Tool](https://usefulgo.com/tools/ai-object-remover) |
| **Blur Image** | Apply blur, tilt-shift, or privacy blurs to photos | [Launch Tool](https://usefulgo.com/tools/blur-image) |
| **Audio Recorder & Trimmer** | In-browser audio recording, trimming, and export | [Launch Tool](https://usefulgo.com/tools/audio-recorder-and-trimmer) |
| **Add Text to Image** | Add captions, watermark badges, and typography to pictures | [Launch Tool](https://usefulgo.com/tools/add-text-to-image) |
| **Add Music to Video** | Combine custom background tracks with video clips | [Launch Tool](https://usefulgo.com/tools/add-music-to-video) |

### ✍️ Text & OCR Tools
| Tool | Description | Direct Link |
|:---|:---|:---:|
| **Image to Text (OCR)** | Extract text from scanned documents, receipts, and photos | [Launch Tool](https://usefulgo.com/tools/document-scanner) |
| **Grammar & Spell Checker** | In-depth grammar, clarity, and spelling analysis | [Explore Office Tools](https://usefulgo.com) |
| **Word & Character Counter**| Real-time reading time, word count, and density checker | [Explore Office Tools](https://usefulgo.com) |

### 💻 Developer Utilities
| Tool | Description | Direct Link |
|:---|:---|:---:|
| **JSON Formatter & Validator** | Beautify, minify, and inspect JSON payloads | [Launch Tool](https://usefulgo.com/categories/developer-tools) |
| **URL Encoder & Decoder** | Percent-encode / decode URIs and query parameters | [Launch Tool](https://usefulgo.com/categories/developer-tools) |
| **Base64 Encoder / Decoder** | Encode binary and text to Base64 format instantly | [Launch Tool](https://usefulgo.com/categories/developer-tools) |
| **Hash Generator (MD5, SHA)** | Generate cryptographic checksums in-browser | [Launch Tool](https://usefulgo.com/categories/developer-tools) |

### 🔢 Calculators, Health & Converters
- **Finance Calculators:** Loan repayment, compound interest, currency converter.
- **Health & Fitness:** BMI calculators, calorie intake, water tracker.
- **Unit Converters:** Length, weight, data storage, speed, and temperature.
- 👉 [Browse full calculator collection](https://usefulgo.com)

### 🎮 Free In-Browser Games
- Casual games, memory challenges, puzzles, and arcade minigames running 100% in your browser without downloads.
- 👉 [Play Games on UsefulGo](https://usefulgo.com/games)

---

## 🏗️ Architecture & Technology Stack

UsefulGo runs on an enterprise-grade microservice architecture designed for speed and scalability:

- **Frontend:** Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS 4
- **Backend API Gateway:** Express 4, TypeScript, TypeORM, Redis 7, PostgreSQL 16
- **Doc Converter Service:** Go 1.23 + LibreOffice Headless + Ghostscript
- **OCR Service:** Python 3.11+ + FastAPI + Tesseract OCR
- **Image Processing Service:** Node.js + Sharp
- **Background Remover Service:** Python FastAPI + `rembg` (ONNX Runtime)
- **Grammar Service:** Java OpenJDK 17 + LanguageTool OSS
- **Deployment:** Docker & Docker Compose

---

## 🚀 Self-Hosting / Local Development

UsefulGo is containerized with Docker Compose for local development:

```bash
# Clone the repository
git clone https://github.com/phuc-huy/usefulgo.com.git
cd usefulgo.com

# Start all microservices
cd projects/usefulgo
docker compose up -d
```

### Individual Service Dev Commands:
- **Webapp:** `cd projects/usefulgo/webapp && npm run dev` (Port 3000)
- **API Gateway:** `cd projects/usefulgo/backend && npm run dev` (Port 4001)
- **Admin Portal:** `cd projects/usefulgo/admin && npm run dev` (Port 3001)

---

## 🤝 Contributing

We welcome community contributions, bug reports, and new tool suggestions!
- Submit a bug or suggest a tool: [GitHub Issues](https://github.com/phuc-huy/usefulgo.com/issues)
- Read our contributing guidelines before submitting a pull request.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for details.

---

<div align="center">
  <sub>UsefulGo.com — Free Online Tools for Everyone. Bookmark and share! ⭐️</sub>
</div>
