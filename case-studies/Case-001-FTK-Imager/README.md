# Case Study 001: Evidence Acquisition with FTK Imager

## Objective

The objective of this lab was to create a forensic image of a virtual machine's disk while preserving the integrity of the original evidence.

---

## Environment

**Host**
- Windows 10

**Virtual Machines**
- Windows 11

**Tools**
- FTK Imager
- VirtualBox

---

## Procedure

1. Installed FTK Imager.
2. Selected the source disk.
3. Chose the RAW image format.
4. Selected a destination separate from the source disk.
5. Started the imaging process.
6. Verified the image after completion.

---

## Challenges

During this lab I encountered several issues:

- Choosing the correct image format.
- Understanding why the destination could notbe the same disk being imaged.
- Imaging required significant time because the entire virtual disk was copied.

  Each issue was researched and resolved before continuing.

  ---

  ## Results

  Successfully created a forensic disk image that could be analyzed using Autopsy.

  ---

  ## Skills Demonstrated

  - Evidence acquisition
  - Forensic imaging
  - Evidence preservation
  - Digital forensics workflow
 
  ---

  ## Lessons Learned

  Creating a forensic image is the first step in a digital investigation. Investigators work from the forensic copy rather than the original evidence to preserve integrity.
