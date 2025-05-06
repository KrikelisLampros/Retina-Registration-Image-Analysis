# Based on the FIRE dataset

Below you can find the documentation of the Dataset https://projects.ics.forth.gr/cvrl/fire/  

1. Reads two .jpg images and their corresponding homologous points from the Ground Truth folder.
2. Computes an affine transformation using the point pairs to align Image 1 onto Image 2.
3. Projects edges from Image 1 onto Image 2 for visual verification.
4. Evaluates the match before and after transformation using:   
   * Correlation coefficient   
   * Mutual information  
