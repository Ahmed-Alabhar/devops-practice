# DevOps Training - Web Application Development (Linux Toolkit)

## Objective
The primary objective of this DevOps training project is to provide participants with practical skills in GIT, Linux, and Python, emphasizing the development of a Flask-based web application. This application will leverage Linux environment capabilities, utilizing system credentials, including the root user, to perform various operations related to File and Directory Management, Process Management, Package Management, System Configuration, and Additional Features.

## File and Directory Management

### 1. Browse Uploads Folder
- Develop a web interface to navigate and display the contents of the uploads folder.

### 2. Upload Allowed Extensions
- Implement a file upload feature with restrictions based on allowed extensions.

### 3. Search Uploaded Files
- Enable search functionality using keywords, regular expressions, and file type filters.

### 4. Create/Extract Archives
- Implement the ability to create ZIP and tar.gz archives from selected files/directories.
- Allow extraction to specified locations with a preview of archive contents.

**Hints:** Utilize Flask for web development and Python libraries such as os, zipfile, and tarfile for file manipulation.

## Process Management

### 1. View/Start/Stop/Restart/Kill Processes
- Develop functionalities to manage processes through the web interface.

### 2. Monitor Processes
- Implement a process monitoring system displaying CPU, memory, and network usage.
- Include sorting and filtering options based on various criteria.

**Hints:** Leverage Python's subprocess module for process management.

## Package Management

### 1. Install/Uninstall Packages
- Allow users to install and uninstall packages, including dependency resolution.

### 2. Update Packages
- Implement package update functionality for specific packages or all installed packages.

### 3. Search/Report Packages
- Develop a package search feature and generate reports on installed packages.

**Hints:** Utilize Linux package managers like apt or yum, and subprocess module in Python.

## System Configuration

### 1. Manage Services
- Provide features to view, start, stop, restart, enable, and disable services.

### 2. Configure Settings
- Allow users to edit firewall rules, network settings, DNS configuration, and manage resource limits.

### 3. Automate Tasks
- Implement automation for tasks such as scheduled backups, log monitoring, and script execution.

**Hints:** Use systemctl for service management, and Python libraries like shutil for file operations.

## Additional Features

### 1. Help and Documentation
- Incorporate context-sensitive help for each command in the web interface.

### 2. Config File
- Develop a configuration file to store user preferences and settings for persistent use.

**Hints:** Consider using Flask documentation features, and configparser in Python for configuration file handling.

*Note: Throughout the project, ensure a user-friendly interface and provide clear error messages for a better user experience. Encourage participants to explore and integrate additional Python libraries as needed for enhanced functionality.*


## Contributing

If you want to contribute to this project, please read the [Contribution Guidelines](CONTRIBUTING.md).


## Challenges
- [Capstone Project](#)


