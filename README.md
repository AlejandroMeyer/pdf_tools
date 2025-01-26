# PDF Tools 🛠️  

**PDF Tools** is a simple Python project that allows you to **split** and **merge** PDF files locally, ensuring your sensitive content stays offline. This project includes the following tools:  

## Features  

### 1. `merge.py` – Combine Multiple PDFs  
- Merges multiple PDF files into a single document.  
- To merge, simply provide the file names (without the `.pdf` extension) separated by commas.  
- Example:  
  ```shell
  python merge.py file1,file2
  ```
  If you have `file1.pdf` and `file2.pdf`, they will be combined into a new file.  
- The merged PDF will be created without modifying the original files.  

### 2. `separate.py` – Split PDF Pages  
- Splits a PDF file by extracting specific page ranges.  
- Specify the page range(s) you need (e.g., `2-3` to extract pages 2 and 3).  
- Example usage:  
  ```shell
  python separate.py inputfile 2-3
  ```
  This will create a new PDF with the selected pages without deleting the original file.  

### 3. `requirements.txt` – Dependencies  
- Contains the necessary dependencies to run the scripts.  
- Install dependencies using:  
  ```shell
  pip install -r requirements.txt
  ```

## Usage Instructions  
- Place all PDF files in the **same folder** as the Python scripts before running the commands.  
- No internet connection is required, ensuring your files remain private and secure.  

## Why Use PDF Tools?  
- **Privacy-focused**: Avoid uploading sensitive documents to online services.  
- **Lightweight and easy to use**: No complex installations required.  
- **Fast processing**: Works efficiently with local files.  

---

Feel free to contribute or report any issues!
