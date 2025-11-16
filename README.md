# 3D Visualization of White & Gray Matter from MRI Data

**Tags:** `MATLAB`, `Medical Imaging`, `Data Visualization`, `Image Processing`

> A MATLAB-based project to process raw MRI (NIfTI) brain scan data, segment the white and gray matter, and render a 3D visualization.

---
<img width="786" height="246" alt="Image" src="https://github.com/user-attachments/assets/9baa7e72-84bc-4f8f-ab37-6d81b8d2432d" />

## 1. The Problem

Raw MRI brain scans are just a series of 2D slices. For surgeons and researchers, it is incredibly difficult to visualize the complex 3D structures of the brain, such as the distinct regions of white and gray matter, from these slices alone.

## 2. Our Solution

For our "Teknologi Pencitraan Medis" (Medical Imaging Technology) project, our team (Kelompok 7) built a complete data processing and visualization pipeline in **MATLAB**.

The program:
1.  **Loads** raw MRI data (from a `.nii` NIfTI file).
2.  **Segments** the brain from the skull using thresholding and morphological operations.
3.  **Partitions** the brain mass into White Matter and Gray Matter based on intensity values.
4.  **Renders** a fully interactive 3D model of the segmented brain matter, allowing the user to rotate and inspect the structures.

## 3. My Role & Key Contributions

I was a **Co-developer and Researcher** on this team project.

* Wrote and debugged the MATLAB code for segmenting the brain mass (`imadjust`, `bwareaopen`, etc.).
* Implemented the logic to partition the brain into white and gray matter (`mriBrainPartition`).
* Helped implement the 3D rendering functions (`patch`, `isosurface`) to display the final model.
* Co-authored the final project report, which includes the full, commented MATLAB code in the appendix.

## 4. Technology Stack

* **Programming Language:** `MATLAB`
* **Software & Toolboxes:** `MATLAB Image Processing Toolbox`
* **Concepts:** `Medical Imaging (MRI)`, `Image Segmentation`, `3D Data Visualization`

## 5. Proof & Key Results

* **[Report & Code]:** The complete 39-page project report, which includes the **full MATLAB source code** in the appendix, is located in this repository.
    * **[Laporan Proyek Pencitraan Medis_Kelompok 7.pdf]**

## 6. Project Status

**Status: [Complete]**
*This project was successfully completed for the Teknologi Pencitraan Medis course.*
