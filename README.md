# 🔍 Text Search & Compare Checker GUI  

**GUI Tool for Text Search and PROC COMPARE Validation in Clinical Programming**  

The **Text Search & Compare Checker** is a Python + PyQt5 based tool that allows programmers to:  
- Search any string across **SAS, LOG, and TXT** files with line previews.  
- Review results from **PROC COMPARE** in **PDF, LST, or TXT** files with automatic **Pass/Fail classification**.  
- Open results directly in **Notepad++** for quick review.  

This tool helps streamline **QC and validation workflows** by providing a modern, vibrant GUI with intuitive navigation.  

---

## ✨ Key Features
- 🔍 **Text Search**  
  - Case-insensitive search across `.sas`, `.log`, and `.txt` files  
  - Preview matching lines with file + line reference  
  - Click to open results directly in **Notepad++**  

- 📑 **PROC COMPARE Checker**  
  - Scans `.pdf`, `.lst`, and `.txt` files for compare outputs  
  - Detects “Number of Observations with Some Compared Variables Unequal”  
  - Classifies each file as **Passed** or **Failed**  
  - Filter results by **All / Passed / Failed**  

- 📊 **Summary Dashboard**  
  - Total files scanned  
  - Match counts for text search  
  - Status counts (✅ Passed / ❌ Failed)  

- 🖥️ **Professional GUI**  
  - Built with **PyQt5**  
  - Modern, vibrant UI  
  - Easy navigation between Text Search and Compare Checker modes  

---

## 🚀 Getting Started

### 1. Clone the Repository
<pre>
git clone https://github.com/&lt;your-username&gt;/TextSearch_CompareChecker_GUI.git
cd TextSearch_CompareChecker_GUI
</pre>

### 2. Install Requirements
Install dependencies manually (script will also auto-install if missing):  
<pre>
pip install PyQt5 PyMuPDF
</pre>

### 3. Run the Application
<pre>
python TextSearch_CompareChecker.py
</pre>

---

## 📂 Example Workflow

1. Launch the GUI.  
2. Choose **Text Search** or **Compare Checker** from the main menu.  
3. For text search:  
   - Select a folder  
   - Enter a search string  
   - Choose file type filter (`.sas`, `.log`, `.txt`, or All)  
   - View matches and open in Notepad++  
4. For compare check:  
   - Select a folder  
   - Choose file type (`.pdf`, `.lst`, `.txt`, or All)  
   - Apply status filter (**All / Passed / Failed**)  
   - Review results with color-coded status  

---

## ⚙️ Dependencies
- **Python 3.x**  
- [PyQt5](https://pypi.org/project/PyQt5/)  
- [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/)  
- [Notepad++](https://notepad-plus-plus.org/) (required for opening results; path configurable in script)  

---


## 🛠 Development Notes
- Designed for **clinical programming QC workflows**.  
- Auto-refresh not required – user triggers searches manually.  
- Supports **Windows environment** with Notepad++ integration.  
- Can be extended for more output file types if needed.  

---

## 📧 Contact
Developed by **Manivannan Mathialagan**  
📩 manivannan.mathiazhagan@gmail.com  

For issues or feature requests, please open a [GitHub Issue](../../issues).  

---

## 📜 License
This project is released under the MIT License. See [LICENSE](LICENSE) for details.
