---
layout: "default"
title: "🎉 KoValPlus - Evaluate Cultural Alignment Effortlessly"
description: "🌍 Evaluate cultural and value alignment in LLMs with our persona-based comparison to real Korean responses using statistical similarity metrics."
---
# 🎉 KoValPlus - Evaluate Cultural Alignment Effortlessly

## 📦 Download Now!
[![Download KoValPlus](https://img.shields.io/badge/download-KoValPlus-blue.svg)](https://github.com/YousfiNahed/KoValPlus/releases)

## 🚀 Getting Started
KoValPlus helps you evaluate how well Large Language Models (LLMs) align with real human values in Korea. This guide will walk you through downloading and running the application smoothly.

### 🛠️ Requirements
Before you begin, ensure you have the following:

- A computer with Windows, Mac, or Linux.
- Basic internet access to download the application.
- Sufficient disk space (at least 100 MB) for installation.
- An unzipping tool like WinRAR or unzip if the files are compressed.

### 📥 Download & Install
1. Visit this page to download: [KoValPlus Releases](https://github.com/YousfiNahed/KoValPlus/releases).
   
2. Look for the latest version listed and click on it. You will find a list of assets available for download.

3. Download the KoValPlus package. The file will usually have a name like `KoValPlus-v1.0.zip` or a similar format.

4. Once the download is complete, locate the file on your computer. 

5. Right-click the downloaded file and choose “Extract All” to unzip the contents.

6. Open the extracted folder, where you will see several files and folders.

7. Familiarize yourself with the structure:
   ```bash
   KoValPlus/
   ├── code/
   │ ├── survey.py
   │ └── eval.py
   ├── dataset/
   │ └── KoValPlus.json
   ├── outputs/
   │ └── gpt-4o-mini/
   │ ├── kovalplus_responses_.json
   │ └── kovalplus_similarity_.csv
   ├── main.sh
   └── README.md
   ```

### ⚙️ Running KoValPlus
1. Navigate to the folder containing the extracted files.

2. If you are using Windows, double-click `main.sh`. If the script does not run automatically, open a terminal and navigate to the folder. Type the following command and press Enter:
   ```bash
   bash main.sh
   ```

3. For Mac or Linux users, open a terminal window and go to the KoValPlus folder. Then, run:
   ```bash
   chmod +x main.sh
   ./main.sh
   ```

4. The application will start running. It may take a few moments to gather the necessary data and perform the evaluation.

### 📊 Understanding the Outputs
Once KoValPlus completes its process, the results will be saved in the `outputs/` folder. You will find:

- `kovalplus_responses_.json`: This file contains the LLM-generated responses.
- `kovalplus_similarity_.csv`: This file presents the quantitative measures of alignment with real Korean responses.

You can open these files with a text editor or a spreadsheet application for easy review.

### 📂 Exploring the Dataset
KoValPlus uses data derived from the World Values Survey (WVS) Wave 7. It focuses on cultural values relevant to Korea. Understanding this dataset enhances the evaluation process and provides better insights.

### 📖 Troubleshooting Tips
- **Error Running Script**: Ensure that your system allows running scripts. Check your security settings.
- **Missing Files**: If any files are missing after extraction, try re-downloading the package.
- **Slow Performance**: Close unnecessary applications to free up resources on your computer.

### ✉️ Support
If you encounter issues not covered in this guide, please visit the Issues section on our GitHub page. You can report problems or ask for help there.

### 🔄 Update Notification
Periodically check our Releases page for updates. We enhance KoValPlus regularly based on user feedback and new research.

---

Now you can begin evaluating cultural alignment effortlessly with KoValPlus! Remember to always refer back to this guide if you need help in the future.