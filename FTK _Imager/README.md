 # Experiment 01: Evidence Acquisition Using AccessData FTK Imager
 
 ## Objective
To acquire and analyze forensic evidence (volatile and non-volatile memory) using FTK Imager.

## Tools Used
- FTK Imager (Portable / Installed)
- USB Pen Drive / HDD (for portable version)
- Write Blocker

## Procedure

### Acquiring Volatile Memory
1. Open **FTK Imager** → Click **Capture Memory**.
   
<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/cfe8dde3-39c7-4d10-8c2a-8ffcc9e63363" />
<img width="1919" height="1074" alt="Image" src="https://github.com/user-attachments/assets/c3d24203-b782-4787-94f1-b571ac0d54cb" />

3. Options:
   - **Include Pagefile (pagefile.sys):** Stores additional volatile data.
   - **AD1 file option:** Creates an FTK-specific image.
   - 
4. Click **Capture Memory** → A `.mem` file is generated.

---

### Acquiring Non-Volatile Memory (Disk Image)
1. Open **FTK Imager** → Select **Create Disk Image**.
2.  <img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/77f97bbe-3ae0-4056-9157-b91936244581" />
3. Choose source (Physical drive, Logical drive, Image file, Folder/CD).
4. Use **Write Blocker** for integrity.

<img width="1910" height="1075" alt="Image" src="https://github.com/user-attachments/assets/33cd60fd-056e-416c-9ed3-56d2bf19dde7" />
<img width="1904" height="1023" alt="Image" src="https://github.com/user-attachments/assets/cdb79f15-3167-475e-904e-710e0cb4e220" />

6. Select image format:
   - Raw (dd)
   - SMART
   - E01
   - AFF/AFF4
7. Enter **Case Details** and set **Destination**.
8. Enable **Verify Image** for hash validation.
   
 <img width="1904" height="1023" alt="Image" src="https://github.com/user-attachments/assets/cdb79f15-3167-475e-904e-710e0cb4e220" />

<img width="1916" height="1064" alt="Image" src="https://github.com/user-attachments/assets/2249e588-5828-4850-9583-860635ac2150" />

<img width="1440" height="1079" alt="Image" src="https://github.com/user-attachments/assets/fc8494ad-c3ff-4955-a312-912ef3f5de4e" />

<img width="1919" height="1079" alt="Image" src="https://github.com/user-attachments/assets/f148534c-3f39-4c20-9a26-4a645879294d" />

10. Click **Start** → Acquisition begins.

---

## Result
- Captured volatile memory in `.mem` format.
- Acquired non-volatile disk image (Raw/E01/SMART/AFF).
- Verified hash values and generated log.

## Conclusion
FTK Imager allows secure acquisition of volatile and non-volatile memory with integrity maintained.
