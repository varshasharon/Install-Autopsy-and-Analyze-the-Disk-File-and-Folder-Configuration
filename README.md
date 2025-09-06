# Install Autopsy and Analyze the Disk File and Folder Configuration
```
Name: E Varsha Sharon
Reg no.: 212222100058
```
## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="988" height="586" alt="Screenshot 2025-08-28 131849" src="https://github.com/user-attachments/assets/f88c83be-cb1e-4f93-83df-5f9439435898" />
<img width="1919" height="702" alt="Screenshot 2025-08-28 131542" src="https://github.com/user-attachments/assets/80784a02-2301-458c-9a58-0146f5d65fd7" />
<img width="1258" height="839" alt="Screenshot 2025-08-28 132003" src="https://github.com/user-attachments/assets/6f56414c-3b04-485a-aff9-ed9f5a70f498" />
<img width="1919" height="985" alt="Screenshot 2025-08-28 145152" src="https://github.com/user-attachments/assets/317b6dd1-f4f7-4490-b948-72e9bdc0ec5c" />
<img width="1426" height="860" alt="Screenshot 2025-08-28 145120" src="https://github.com/user-attachments/assets/c25fb208-8eaf-4eac-9150-6a1925b0807d" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
