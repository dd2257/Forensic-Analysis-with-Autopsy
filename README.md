# Forensic Analysis with Autopsy

This project involves conducting a forensic analysis of disk image files using the Autopsy tool. The analysis focuses on understanding file signatures, data carving techniques, and the practical application of these concepts to recover and examine files from disk images.

## Project Tasks:

### Preparation

1. **Download Sample Image Files**:
   - L0_Graphic.dd.bz2: [Download Link](https://cfreds-archive.nist.gov/FileCarving/Images/L0_Graphic.dd.bz2)
   - L2_Graphic.dd.bz2: [Download Link](https://cfreds-archive.nist.gov/FileCarving/Images/L2_Graphic.dd.bz2)
2. **Install Autopsy**:
   - Download and install the Autopsy tool from [Autopsy Download](https://www.autopsy.com/download/).

### Assignment Part 1: Research-Based

1. **File Signature and File Header**:
   - **File Signature**: A unique series of bytes at the beginning of a file that helps in identifying the file format. It's crucial for determining the file type independent of the extension.
   - **File Header**: Contains metadata about the file, including size, timestamps, and permissions. It is used in digital forensics to confirm data integrity and understand the file structure.
2. **Data Carving**:
   - **Header-Footer Carving**: Extracts files based on known header and footer bytes.
   - **File Structure-Based Carving**: Utilizes the internal structure of files, such as headers, footers, and size information.
   - **Content-Based Carving**: Analyzes the structure and content of files, including language recognition and statistical analysis.

### Assignment Part 2: Practice-Based

1. **Import Disk Images to Autopsy**:
   - Import the L0_Graphic.dd and L2_Graphic.dd images as 'unallocated space disk images' in Autopsy.
2. **Run Ingest Module with PhotoRec Carver**:
   - Enable the ‘PhotoRec Carver’ module to recover files.
3. **Analysis**:
   - **List Carved Files**: Document the files recovered from each disk image.
   - **Compare Files**: Choose a carved file with the same extension and size from both images.
   - **Analyze Header Values**: Display the header value indicating file size in hexadecimal and convert it to decimal.
   - **File Comparison**: Determine whether the two files are originally the same by comparing their hash values and content.

## Conclusion

This project highlights the importance of file signature analysis, data carving, and the use of forensic tools like Autopsy in recovering and examining digital evidence. Through practical application, it provides insight into how these techniques are applied in real-world forensic investigations.
