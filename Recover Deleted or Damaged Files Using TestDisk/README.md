# Experiment 02: Recover Deleted or Damaged Files Using TestDisk

## Objective
To recover deleted or corrupted partitions/files from storage devices using TestDisk.

## Tools Used
- TestDisk (CLI tool)
- Storage device with missing/corrupted partition
## Procedure
1. **Launch TestDisk** → Select target drive.
   
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3369300e-0468-444f-bb33-55cc72158e7a" />
   
3. **Partition Table Detection** → Auto-detects type.

<img width="601" height="927" alt="Image" src="https://github.com/user-attachments/assets/cc089680-2ab3-48ff-8fdd-0fd5443624de" />


4. **Analyze Current Structure** → Check for errors/missing partitions.

 <img width="1108" height="636" alt="Image" src="https://github.com/user-attachments/assets/b71fc9ea-aba4-4699-ba44-404d4b545685" />

7. **Quick Search** → Finds lost partitions.
8. **Deeper Search** → Scans cylinders for FAT/NTFS/ext backups.
9. **Partition Selection**:

 <img width="1101" height="630" alt="Image" src="https://github.com/user-attachments/assets/80e09d5e-146b-41bb-9c0d-0a7b01b1c94d" />
<img width="1111" height="639" alt="Image" src="https://github.com/user-attachments/assets/7c82705f-6fd3-4fc6-b80e-b3d6add2db23" />

   - Mark valid partition as Primary/Logical.
   - Mark damaged partitions as Deleted (D).
11. **Partition Table Recovery** → Save with **Write**.
12. **NTFS Boot Sector Recovery**:
   - Use **Backup BS** if primary boot sector is damaged.
   - Confirm copy of backup → Boot sector repaired.

---

## Result
- Successfully detected and recovered missing partitions.
- Restored NTFS boot sector from backup.
- Recovered files and verified integrity.

## Conclusion
TestDisk efficiently recovers lost partitions and repairs corrupted file systems, ensuring access to critical data.
