# Image Defense Tool (English Version)
> Please make sure this tool provides the features you need. It can be a bit tedious to use.

## 🔗 Table of Contents
- [Introduction](#introduction)
- [Purpose and Features](#purpose-and-features)
- [Usage Steps (GUI Version)](#usage-steps-gui-version)
- [Output Structure](#output-structure)
- [Deployment](#deployment)
- [License](#license)
- [Contact / Issues](#contact--issues)

---

## Introduction


---

Image Defense Tool is a **tool for image display and protection**, helping creators prevent unauthorized use or AI training of their images, while quickly generating deployable static showcase pages.  

GUI (EXE) interface allows usage without programming knowledge.

---

## Purpose and Features

### Main Purpose
- Prevent images from being directly used for AI model training
- Protect original works of creators
- Provide safe image display
- Quickly generate deployable image showcase pages

### Main Features
- Automatically generate display images
- Automatically generate cropable thumbnails
- Generate single-page static image showcase website
- Directly deployable on GitHub Pages / Cloudflare Pages

---

## Usage Steps (GUI Version)

### 1️⃣ Launch the program
Run:

Image Defense Tool.exe


---

### 2️⃣ Select Image Folder
- Click **Browse**
- Select a folder containing images (JPG / PNG)

---

### 3️⃣ Thumbnail Settings
- **Aspect Ratio**
  - `original` – keep original ratio
  - `1:1` / `16:9` / `4:3` – auto crop
- **Max Size**
  - Set the maximum side length (pixels) for the thumbnail

---

### 4️⃣ Website Settings
- **Site Title**: title of the showcase page
- **Base URL**: deployment URL (for Open Graph / sharing)

---

### 5️⃣ Notice Settings
- Optionally display usage notice
- Customizable:
  - Title
  - Body
  - Extra

---

### 6️⃣ Build Showcase Page
- Click **Build Website**
- The program outputs a static website folder

---

## Output Structure
Final output folder structure:

IMG/  
├─ index.html # Main showcase page  
├─ image.bat # Local image viewing  
├─ og_preview.jpg # Social media preview  
├─ viewer.js # Image viewing & interaction logic  
└─ style.css # Website styling  

📌 **Notes**
- `index.html`: main page
- `og_preview.jpg`: preview image for sharing
- `viewer.js`: controls image display and interactions
- `style.css`: layout and style

---

## Deployment

### GitHub Pages
1. Create a GitHub repository
2. Upload the files in `IMG/`
3. Enable Pages (Root or `/docs`)

### Cloudflare Pages
1. Create a Pages project
2. Upload `IMG/` as the output directory
3. No extra build command required

---

## License
This software uses an **EXE-specific license**:

- Personal, non-commercial use only
- No reverse engineering, redistribution, or resale
- Not for AI model training
- Output from this tool is also covered by this license

📄 See `LICENSE.txt` for details

---

## Contact / Issues
- X (Twitter): https://x.com/Hyu996
