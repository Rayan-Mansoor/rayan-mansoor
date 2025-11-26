---
title: "Image Manipulation App"
summary: "An offline-first Android image tools app to crop, resize, compress, convert, and share images, saving results straight to the gallery."
dateString: 2023
draft: false
tags: ["Kotlin", "Android", "ViewBinding", "XML", "Image Processing", "Glide", "MediaStore"]
showToc: false
weight: 203
cover:
    image: "projects/Image-Manipulation.jpg"
--- 

### 🔗 [GitHub Repo – Image Manipulation App](https://github.com/Rayan-Mansoor/Android-Image-Manipulation-App)

## Description

An **Android image tools app** focused on quick, offline-friendly manipulation of photos.

The app lets users:

- Crop images
- Resize by pixels or percentage
- Compress to smaller file sizes
- Convert between common formats
- Save results directly to the gallery and share them

It’s designed as a compact, utility-style app: no server, no accounts, just local processing and clean outputs.

---

## Key Features

- **Crop & Reframe**  
  Freeform or 1:1 cropping to adjust framing before export.

- **Flexible Resize Options**  
  Resize by **exact pixels** or by **percentage**, with optional aspect-ratio preservation for cleaner results.

- **Smart Compression**  
  Reduce file size without destroying quality, with options for automatic “target size” compression or manual quality selection.

- **Format Conversion**  
  Convert between **JPEG, PNG, and WEBP**, with safeguards for very large images so the app stays stable.

- **Saves to Gallery**  
  Processed images are written to **MediaStore** with a clear naming pattern, and appear immediately in gallery apps.

- **Recent Files & Sharing**  
  Built-in **Recent** view for outputs created by the app, with quick actions to **share** (e.g. to WhatsApp) or delete.

- **Offline-First**  
  All operations run entirely on-device — no network, no external services required.

---

## Tech Stack

- **Language:** Kotlin  
- **UI:** Android Views with ViewBinding + XML layouts  
- **Image Handling:** Glide for decoding/resizing, EXIF-aware dimension handling  
- **Cropping:** CanHub Android-Image-Cropper  
- **Lists & UI Components:** RecyclerView, Material Components  
- **Storage:** Storage Access Framework + MediaStore for saving outputs to the gallery  