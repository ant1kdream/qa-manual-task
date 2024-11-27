# qa-manual-task


The objective is to test an application that simulates multiple file to server uploads without actual server interaction. You need to intuitively find bugs and create test cases for the functionality.  

Choose the installer that matches your platform - there are 2 .dmg installers for Mac depending on the architecture, or a Windows .exe installer available.
The application is not digitally signed, therefore:

For Mac users: After installation, you'll need to either forcefully launch it through Security Settings or execute the command:

```
xattr -c /Applications/QA\ Uploader.app
```
After that, the application will become accessible.  
For Windows users: Use the "Run anyway" option during installation.


## Requirements
- Windows 10/11 or macOS 10.15+
- For Mac users: Intel or Apple Silicon processor
- Minimum 4GB RAM
- 200MB free disk space

## How to start
1. Download the appropriate installer 
2. Install the application following the platform-specific instructions above
3. Launch the application and proceed with testing

## Deliverables
Please provide:
- Test cases covering the main functionality
- Bug reports for any issues found
- Suggestions for improvements (optional)