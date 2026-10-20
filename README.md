# Cytoskeleton-BBBC018-17673

**Student ID:** 202303426

**Phenotype:** Prophase

**Image-field ID:** 17673

**Actin filename:** 17673-actin.DIB

**DNA filename:** 17673-DNA.DIB

## Dataset

This activity uses the BBBC018 fluorescence image dataset of HT29 human colon-cancer cells. The images were used to observe cell shape and F-actin staining patterns.

 **BBBC018 download link:** https://bbbc.broadinstitute.org/BBBC018

 ## Fiji steps

 <img width="1365" height="686" alt="image" src="https://github.com/user-attachments/assets/e9cfe95b-211e-4295-8733-7cfaac55abb3" />

*Figure 1. The Fiji download page shows the available versions for different operating systems. The Windows x86-64 version was selected for installation on a Windows computer.*


<img width="313" height="158" alt="image" src="https://github.com/user-attachments/assets/461e7bea-b61d-465c-be4d-58736ad35107" />
<img width="613" height="454" alt="image" src="https://github.com/user-attachments/assets/fa1afb74-3849-4c18-9abd-a74d3296dff4" />

*Figure 2. Open the Fiji application. The Extract All option was selected to continue the installation. The extraction window allows the user to choose where the Fiji files will be saved. The Extract button was used to extract the files into the selected folder.*


<img width="1364" height="721" alt="image" src="https://github.com/user-attachments/assets/cc985bd3-03a4-4ee9-975d-a9fe1a04d7cf" />

*Figure 3. Selecting File → Import → Bio-Formats in Fiji to import microscopy images for further analysis.


<img width="664" height="479" alt="image" src="https://github.com/user-attachments/assets/1a066543-6bf3-4bbe-a619-1fcb7f629377" />

*Figure 4. The file selection window in Fiji, where the 17673-actin file is selected from the BBBC018_v1_images folder for further image analysis.*


<img width="736" height="729" alt="image" src="https://github.com/user-attachments/assets/dd6a0cd0-7d6a-4a2a-a99b-41d09161d9c0" />
<img width="296" height="454" alt="image" src="https://github.com/user-attachments/assets/02f1936a-bb0c-4854-b2f3-376300e7cb12" />

*Figure 5.  Select analyze and set measurements. Check Area, Mean gray value, Shape descriptors, and Display label.*


<img width="1365" height="718" alt="image" src="https://github.com/user-attachments/assets/e7b03830-a882-4770-bee1-8e0fa71da40e" />

*Figure 6. Using the Freehand Selection tool to trace the outer edge of the first cell on the actin image. Use the DNA image as a visual.*


<img width="1364" height="724" alt="Screenshot 2026-10-20 162436" src="https://github.com/user-attachments/assets/d724252b-75ba-4525-ab70-779eeff834c9" />

*Figure 7. Open Analyze then go to tools and click ROI Manager. Press T to add the region to ROI Manager, then choose analyze then measure (or press M). Repeat for all five cells. The Results window should contain five rows. Save the measurements in csv.*

## Plot

<img width="900" height="650" alt="actin_intensity" src="https://github.com/user-attachments/assets/ec0f2307-15e6-4a80-987d-070cb73e8019" />

*Figure 8. Actin Signal Intensity of Prophase Cells. The graph shows the actin intensity of five cells. Cell 2 has the highest intensity, while Cell 4 has the lowest. This shows that the actin intensity varies among the cells.*


<img width="900" height="650" alt="area_vs_circularity" src="https://github.com/user-attachments/assets/d6145579-3b68-48ba-9532-69cd6c97b8a7" />

*Figure 9. Relationship Between Cell Area and Circularity During Prophase. The graph shows the relationship between cell area and circularity in five cells. Cells 2 and 5 have smaller areas and higher circularity, while Cells 3 and 4 have larger areas and lower circularity. This suggests that larger cells tend to have lower circularity in the observed data.*

## Explanation for the results

**1. Which specific phenotype did you choose, and what visible features support that choice?**

I chose the prophase phenotype because the cells showed differences in shape, size, and actin fluorescence intensity.

**2. Were your five cells mostly round or elongated? Refer to your circularity and aspect-ratio results.**

The five cells showed differences in shape. Cells 2 and 5 were more round because they had higher circularity values, while Cells 1, 3, and 4 were less round. The aspect-ratio results can also help determine whether the cells were elongated.

**3. What role does actin play in maintaining cell shape and in cell movement (Karp Chapter 9)?**

Actin helps maintain cell shape by forming part of the cytoskeleton. It also supports cell movement by allowing the cell membrane to change shape and form extensions. Actin works with other proteins to help cells move.

**4. Why can a single fixed fluorescence image NOT show how fast a cell moves?**

A single fixed fluorescence image shows the cell at only one point in time. It cannot show changes in the cell's position or movement. To measure cell speed, images must be taken at different time points so that changes in position can be compared.
