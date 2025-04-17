# Notepad Application

## Overview
This is a simple Notepad application built using Java Swing. It provides basic text editing functionality along with some additional features like text-to-speech, font customization, and color settings.

## Features

### File Operations
- **New**: Create a new document (Ctrl+N)
- **New Window**: Open a new Notepad window (Ctrl+Shift+N)
- **Open**: Open an existing text file (Ctrl+O)
- **Save**: Save the current document (Ctrl+S)
- **Print**: Print the current document (Ctrl+P)
- **Exit**: Close the application (Ctrl+W)

### Formatting Options
- **Font Selection**: Choose from various font faces, styles (plain, bold, italic), and sizes
- **Color Customization**:
  - Change background color
  - Change font color

### Additional Features
- **Text-to-Speech**: Reads the text content aloud using FreeTTS
- **Basic Text Editing**: Standard text area for writing and editing

## Requirements
- Java Runtime Environment (JRE) 8 or later
- FreeTTS library (included in the project)

## How to Use
1. **File Operations**:
   - Use the File menu to create, open, save, or print documents
   - The application supports .txt file format

2. **Formatting**:
   - Access font settings through Format → Font
   - Change colors through Format → Color

3. **Text-to-Speech**:
   - Click "Read Text" → "Read" to have the application read the current text
   - The reading can be stopped by closing the application or waiting for completion

## Known Issues
- The text-to-speech feature may have limited voice options depending on system configuration
- Some font faces might not be available on all systems

## Future Improvements
- Add find/replace functionality
- Implement undo/redo features
- Add support for additional file formats
- Improve text-to-speech controls (pause, stop, speed adjustment)

## License
This project is open-source and available for educational purposes. Feel free to modify and distribute it as needed.
