# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
# Name : Moenish Baalan G
# Reg No : 212223220057
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

![Screenshot 2025-04-26 201404](https://github.com/user-attachments/assets/1bacc201-db29-4f08-b754-649f8a7d4516)


![436055808-eb43876f-a202-461a-9265-89e4ea36b4ca](https://github.com/user-attachments/assets/372c4381-c89b-4fc4-b9c1-10bdb937376b)


![435672929-1fc8e81f-12c1-4927-92ca-a4a0a500950e](https://github.com/user-attachments/assets/ad556156-f7c9-4e97-8d5a-0631d16aa757)


![436055941-92658b19-6e77-4be4-b84b-767fae44c7aa](https://github.com/user-attachments/assets/ac4732bd-26a7-4efb-a0b9-c716e9f352c2)


![435676562-4aff8fc4-e59c-475e-bdb2-658f15c67c50](https://github.com/user-attachments/assets/56a15307-4679-4bfa-815e-7b1488c6bbc0)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
