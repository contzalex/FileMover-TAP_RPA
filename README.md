# FileMover

**FileMover** is an automation tool built using the **TAP Talent framework** for RPA (Robotic Process Automation) and **C# scripting**. It helps you organize your files and documents by automatically sorting and placing scrambled files into neatly arranged folders. Designed to integrate seamlessly with other TAP RPA programs, FileMover streamlines workflows, increases productivity, and keeps your workspace tidy.  

---

## Features

- **Custom Folder Selection:** Choose which folders to sort, with optional inclusion of subfolders.  
- **File Type Sorting:** Automatically sorts files by type (e.g., documents, images, spreadsheets) into designated folders.  
- **Destination Folder Selection:** Select where the sorted files will be placed.  
- **Failsafe Mechanisms:** Built-in checks ensure no files are lost or misplaced during the process.  
- **Win32 API Integration:** Uses Windows API calls for precise file and folder handling.  
- **TAP RPA GUI Modals:** Provides a user-friendly interface for easy interaction.  
- **Automation Ready:** Can be scheduled to run on intervals or triggered on-demand by users.  
- **Workflow Integration:** Designed to work alongside other TAP RPA programs to automate complex document and file management workflows.  

---

## How It Works

1. **Select Folders:** Choose one or more folders to scan and sort.  
2. **Include Subfolders (Optional):** Decide whether to process files in nested folders.  
3. **Select Sorting Options:** Choose to sort by file type or other criteria.  
4. **Choose Destination:** Pick the folder(s) where sorted files will be moved.  
5. **Automation:** Run the program manually or schedule it to run automatically, keeping your workspace organized without any extra effort.  

FileMover uses **TAP RPA modals** for the GUI interface and **C# scripting with Win32 API calls** under the hood for file operations, ensuring efficient and reliable execution.

---

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/FileMover.git
2. Open the project in **TAP Talent Studio**.  
3. Ensure **C# scripting support** is enabled in TAP.  
4. Build and run the project.  

---

## Usage

- Launch the **FileMover** interface in TAP Talent.  
- Select the source folder(s) you want to organize.  
- Enable the option to include subfolders if needed.  
- Choose whether to sort files by type or apply custom rules.  
- Select the destination folder(s) where sorted files will be moved.  
- Click **Run** to execute the workflow.  

The program will automatically move files into organized folders and log any errors or conflicts encountered during the process.

---

## Features

- **Custom Folder Selection:** Pick specific folders to sort.  
- **Include Subfolders:** Optionally process nested folders.  
- **Sort by File Type:** Automatically categorize files (documents, images, spreadsheets, etc.).  
- **Destination Folder Selection:** Choose where files should be organized.  
- **Failsafe Mechanisms:** Built-in checks to prevent data loss.  
- **Win32 API Calls:** Precise file operations using Windows API.  
- **TAP RPA GUI Modals:** User-friendly interface for easy interaction.  
- **Automation Ready:** Run manually or schedule for automatic execution.  
- **Seamless Workflow Integration:** Works alongside other TAP RPA programs for full automation.

---

## Contributing

Contributions are welcome! To contribute:  

1. Fork the repository.  
2. Create a new branch for your changes (`feature-name` or `bugfix-name`).  
3. Make your modifications and commit them with clear messages.  
4. Submit a pull request describing your changes and improvements.  

Ensure your code is compatible with **TAP Talent RPA** and follows the existing C# scripting conventions.

---

## Future Improvements

- Advanced sorting rules (by date, size, or custom tags).  
- Cloud storage integration (OneDrive, Google Drive, etc.).  
- File preview before moving.  
- Multi-threaded processing for faster execution on large file sets.

---

## License

This project is licensed under the GNU General Public License. See the [LICENSE](LICENSE.MD) file for details.  

---

## Contact

Created by **[Alexandru-Ioan Contz](https://github.com/alexcontz)**.  
For questions, suggestions, or support, open an issue in this repository.
