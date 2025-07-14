# SimpleConverter - The Ultimate File Converter

<p align="center">
  <img src="IconFormat.png" alt="SimpleConverter Logo" width="200">
</p>

Tired of online converters that are slow, covered in ads, and make you jump through hoops just to download your own file? So were we.

SimpleConverter is a powerful, privacy-focused, and user-friendly file conversion tool that runs entirely in your web browser. It's built on the principle that converting your files should be a simple, secure, and unrestricted process. No uploads, no queues, no nonsense.

## The Philosophy

This project was born out of frustration with the state of online file converters. Many services impose confusing limitations, bombard users with advertisements, and require you to upload your personal files to their servers, creating privacy concerns.

SimpleConverter is different. It leverages the power of modern web technologies like WebAssembly to perform all conversions directly on your computer and hosted via Github Pages. Your files never leave your machine, guaranteeing your privacy and providing a much faster experience.

## Key Features

*   **100% Client-Side**: All file processing happens in your browser. Your data stays private and secure.
*   **Multi-Format Support**:
    *   **Images**: PNG, JPEG, WEBP, BMP, GIF
    *   **Videos**: MP4, WEBM, MOV, AVI, MKV
    *   **Audio**: MP3, WAV, OGG, FLAC
    *   **Text**: TXT, CSV, JSON
*   **Powerful Editing Tools**:
    *   **Image**: Resize, Rotate, Flip, and AI-Powered Background Removal.
    *   **Video/Audio**: Trim your media files to the exact length you need.
    *   **Video**: Extract the audio track from a video file.
*   **Batch Conversion**: Upload multiple files and convert them all to a single format in one go.
*   **Flexible Input**: Upload files from your computer, drag-and-drop, paste images from your clipboard, or import directly from a URL.
*   **Unrestricted Downloads**: Download your converted files individually or as a convenient .zip archive instantly. No wait times, no download limits.
*   **Dual-Theme "Frutiger Aero" UI**: Enjoy a beautiful, nostalgic interface inspired by the early 2010s aesthetic, available in both light and dark modes.

## Tech Stack

*   **Core**: HTML, CSS, and modern JavaScript (ESM)
*   **Conversion Engine**: FFmpeg.wasm for robust audio and video processing.
*   **Background Removal**: `@imgly/background-removal` for the AI-powered image tool.
*   **Archiving**: JSZip for creating .zip files for batch downloads.
*   **Icons**: Lucide Icons for a clean and modern icon set.
*   **Font**: Tahoma

## How to Use

1.  Simply open the `index.html` file or use [this page](https://molokrakein.github.io/SimpleConverter/) in a modern web browser like Chrome, Firefox, or Edge.
2.  Use the top navigation to select a conversion category (Image, Video, etc.).
3.  Upload your file(s) using the upload area, or import from a URL.
4.  Select your desired output format.
5.  (Optional) Use the available tools to edit your file before conversion.
6.  Click the "Convert" button.
7.  Your converted file will appear in the "Download Queue," where you can download it directly.

## What In Progress ??
*   PDF Converter Tool sets
*   Conventional Office file format converter


## Credits

*   Dark Mode Background Photo by [Vincent Botta on Unsplash](https://unsplash.com/photos/a-close-up-of-a-green-leaf-with-water-droplets-on-it-3_i2a01m2-M).
*   Application icon and UI design inspired by the Frutiger Aero aesthetic.