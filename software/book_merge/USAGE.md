# Book Merge Software - Detailed Usage Guide

This document provides detailed instructions for using the Book Merge software that accompanies the Book Scanner Copy Stand project.

## Installation Process

1. Extract the downloaded zip file containing the Book Merge software
2. Run the installer application
3. If you receive a security warning (common in Windows 8 and newer versions):
   - Click on "More information" or similar option
   - Select "Run anyway" to proceed with installation
   - This warning appears because the software isn't digitally signed, not because it contains malware

## Setting Up Your Workflow

### Preparing Your Scanned Images

Before using the Book Merge software:

1. Organize your scanned pages into two separate folders:
   - One folder for all left-side pages
   - One folder for all right-side pages
2. Create a third empty folder where merged results will be saved
3. Make sure your images follow a consistent naming convention for best results

### Interface Overview

When you launch the Book Merge program, you'll see:
- Folder selection buttons for left pages, right pages, and merge destination
- Text field for naming your merged files
- Number field for setting the starting number in the sequence
- Buttons for different processing operations

## Step-by-Step Usage

1. **Select Folders**:
   - Click on "Left Pages Folder" button and browse to select the folder containing your left page scans
   - Click on "Merge Folder" button to select where you want the merged results to be saved
   - Click on "Right Folder" button to select the folder containing your right page scans

2. **Configure Naming Options**:
   - Enter a prefix name that will be used for all renamed files (e.g., "BookTitle")
   - Set the starting number for file numbering (recommended: 100 or higher)
   - The file naming will follow the pattern: [prefix]_[number]

3. **Processing Options**:
   - **Rename Left Pages Only**: Click this option if you only want to rename the files in your left pages folder
   - **Rename Right Pages Only**: Click this option if you only want to rename the files in your right pages folder
   - **Rename and Merge**: Click this button to process everything in one step - renaming both left and right pages and creating merged files

4. **Review Results**:
   - Once processing is complete, check your merge folder for the results
   - Verify that the pages are in the correct order and properly named

## File Naming Considerations

The creator notes that file numbering is important because:
- Older Windows file browsers list files in alphabetical order, not numerical order
- This means "Book_1", "Book_2", ... "Book_10" would be ordered as "Book_1", "Book_10", "Book_2"
- Starting with a higher number (100+) ensures proper ordering in all systems
- Newer Windows versions handle numerical ordering correctly, so this is less of an issue

## Additional Tips

- Always backup your original scanned images before processing
- Test the software with a few sample images before processing your entire book
- If you need to restart the process, make sure to use empty folders or clear previous results

## Troubleshooting

- If files aren't showing up in the selected folders, check file permissions
- If merging isn't working correctly, verify that your left and right page images correspond properly
- For any other issues, check that all folders are correctly specified and accessible