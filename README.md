# Cytoskeleton-BBBC018-17673

**Student ID:** 202303426

**Phenotype:** Long projections

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

<img width="900" height="650" alt="actin_intensity" src="https://github.com/user-attachments/assets/43ab27ed-3985-4118-a505-5efa7ff33531" />

*Figure 8. Actin fluorescence intensity of five selected cells (17673). The bar graph shows the mean actin fluorescence intensity of five selected cells. Cell 2 has the highest intensity, followed by Cell 1 and Cell 5, while Cell 4 has the lowest intensity. These differences indicate variation in actin signal among the selected cells.*


<img width="900" height="650" alt="area_vs_circularity" src="https://github.com/user-attachments/assets/441a3588-b944-4da9-8503-ddc57ab6587f" />

*Figure 9. Cell area versus circularity of five selected cells with the long-projections phenotype (17673). The scatter plot shows the relationship between cell area and circularity. Cells 3 and 4 have larger areas but lower circularity, indicating more elongated or irregular shapes. In contrast, Cells 2 and 5 have higher circularity and smaller areas, suggesting more compact shapes. These measurements show morphological variation among the five selected cells.*

## Explanation for the results

**1. Which specific phenotype did you choose, and what visible features support that choice?**

I chose long projections because some cells have elongated shapes with visible extensions. These features make the cells look longer and less round.

**2. Were your five cells mostly round or elongated? Refer to your circularity and aspect-ratio results.**

My five cells showed a mix of round and elongated shapes. Cells 3 and 4 had lower circularity, while Cells 2 and 5 were rounder based on their higher circularity values.

**3. What role does actin play in maintaining cell shape and in cell movement (Karp Chapter 9)?**

Actin helps maintain the shape of the cell and supports its outer part. It also helps cells move by forming extensions and producing the force needed for movement.

**4. Why can a single fixed fluorescence image NOT show how fast a cell moves?**

A single fixed image only shows the cell at one point in time. To measure how fast a cell moves, we need to observe its position over time using live-cell imaging.

