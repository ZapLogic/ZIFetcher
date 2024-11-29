# <span style="color:#1E90FF;">ZIFetcher</span>

**ZIFetcher** is a Python-based tool designed to efficiently scrape and download files from web directories. It supports recursive downloading, multi-threaded file retrieval, and offers easy control for pausing, resuming, or quitting the download process.

![ZIFetcher Logo](https://via.placeholder.com/150)  <!-- Replace with your logo image URL -->

---

## <span style="color:#2E8B57;">Features</span>

- **Download Files from Web Directories**  
  Automatically scrape and download all files linked on a webpage or directory.

- **Recursive Downloading**  
  Download files from nested subdirectories by recursively exploring folder structures.

- **Pause, Resume, and Quit Controls**  
  Manage the download process using keyboard controls:  
  - `Ctrl + P` to Pause  
  - `Ctrl + R` to Resume  
  - `Ctrl + Q` to Quit

- **Logging and Error Handling**  
  All download activities and errors are logged in a log file for tracking purposes.

- **File Organization**  
  Files are saved into a local folder structure, maintaining the organization of the web directory.

- **Multithreaded Downloads**  
  Speeds up the download process by downloading multiple files concurrently using threads.

- **Sanitize File and Folder Names**  
  Automatically sanitizes file and folder names to avoid invalid characters in the file system.

---

## <span style="color:#2E8B57;">Supported File Types</span>

ZIFetcher can download a variety of file types, including but not limited to:

### 1. **Documents:**
   - PDF (`.pdf`)
   - Word files (`.doc`, `.docx`)
   - Excel files (`.xls`, `.xlsx`)
   - Text files (`.txt`)
   - PowerPoint files (`.ppt`, `.pptx`)
   - CSV files (`.csv`)
   - Markdown files (`.md`)

### 2. **Media Files:**
   - Images (`.jpg`, `.png`, `.gif`, `.svg`)
   - Audio files (`.mp3`, `.wav`, `.aac`)
   - Video files (`.mp4`, `.avi`, `.mkv`, `.webm`)

### 3. **Compressed Files:**
   - ZIP files (`.zip`)
   - RAR files (`.rar`)
   - Tarballs (`.tar`, `.tar.gz`, `.tgz`)
   - 7z files (`.7z`)

### 4. **Software & Executables:**
   - Executable files (`.exe`, `.msi`, `.sh`)
   - Installation packages (`.dmg`, `.iso`)
   - Libraries (`.dll`, `.so`, `.jar`)

### 5. **Web Files:**
   - HTML files (`.html`)
   - JavaScript files (`.js`)
   - CSS files (`.css`)

### 6. **Other File Types:**
   - Fonts (`.ttf`, `.otf`)
   - 3D models (`.obj`, `.stl`)
   - Database files (`.sql`, `.db`, `.sqlite`)
   - Data files (`.json`, `.xml`, `.yaml`)

---

## <span style="color:#2E8B57;">Usage</span>

1. **Just Download the file and run it:**
   
