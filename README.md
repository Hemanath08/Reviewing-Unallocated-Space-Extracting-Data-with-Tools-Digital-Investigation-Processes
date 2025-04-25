# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes

## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```

```bash
mmls ~/disk.img
```
```bash
sudo ls -lh disk.img
```
```bash
strings disk.img | less

```

## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![image](https://github.com/user-attachments/assets/a5e14c5d-e384-467a-b2bc-bf0034489bf7)

![image](https://github.com/user-attachments/assets/472ce5a2-21b9-4fd9-90f6-776479044b3b)

![image](https://github.com/user-attachments/assets/0af09ce4-b388-4c84-a372-ae3bdb22f1f2)

![image](https://github.com/user-attachments/assets/99a31a0f-3d38-4174-b16f-891812985214)

![image](https://github.com/user-attachments/assets/eff607c7-f3f2-439c-a339-f35ccece48dc)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

