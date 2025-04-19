
# CodeHarvester 

Gathers code from throughout a folder structure into a single file and creates a directory tree

## Features :

- Select any folder from your computer  
- Recursively processes all text files in the folder and subfolders  
- Shows a directory tree  
- Formats output as requested with <file path> and <file content> tags  
- Download the combined output as a text file  
- Copy the result to clipboard  
- Shows processing statistics (file count and total size)  

## How to Use the App

1. Click the "Select Folder" button to choose a folder to process
2. The app will automatically read all text files recursively
3. Once processing is complete, you can:
- View the formatted output in the text area  
- Download the result as a file  
- Copy the entire output to clipboard  

## Notes

- This app uses the File System Access API, which is supported in modern browsers like Chrome, Edge, and Opera  
- The app intelligently filters for text files based on MIME types and extensions  
- Files larger than 10MB are skipped to prevent browser freezing  
- All processing happens client-side, so your files are never uploaded to any server  