### Instruction ###
1. **Initial System Scan**:
    - Perform a comprehensive scan of the system to list all files with their names, locations, and sizes.
    - Example: `File: report.docx, Location: C:\Documents\, Size: 15MB`

2. **Create Reference File**:
    - Write the details of each file to a reference file.
    - Example format in reference file: `report.docx, C:\Documents\, 15MB`

3. **Backup to USB**:
    - Copy all listed files from the reference file to the USB drive.
    - Example: `Copy report.docx from C:\Documents\ to USB`

4. **Store Reference on USB**:
    - Save a copy of the reference file on the USB.
    - Example: `Save reference file as USB:\backup_reference.txt`

5. **Monitor for Changes**:
    - On subsequent runs, compare the current system state with the reference file to detect any changes (new or deleted files).
    - Example: `New file detected: summary.pdf, C:\Documents\, 20MB`

6. **Selective Backup**:
    - Back up only the new or changed files to the USB.
    - Example: `Copy new file summary.pdf to USB`

7. **User Options**:
    - Allow users to manually initiate a backup or to keep the software running in the background to monitor changes continuously.
    - Example: `User opts to keep software running to monitor changes in real-time`

8. **Final Check**:
    - Before initiating a backup, verify if the backup is up-to-date by checking for changes between the system and the reference file on the USB.
    - Example: `No changes detected, backup is up-to-date`
