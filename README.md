### iSSVD - Intergrative Biclustering for Multi-view data


_Inputs_:

 **X**: A list contains multi-view data.

 **standr**: If True each view will to be standardized.
 
 **pointwise**: If True a fast pointwise control method will be performed for stability selection.
 
 **steps**: Number of subsmaples used to perform stability selection.
 
 **size**: Size of the subsamples used to perform stability selection.
 
 **ssthr**: Range of the threshold for stability selection.
 
 **nbicluster**: A user specified number of biclusters to be detected.
 
 **rows_nc**: If True allows for negative correlation of rows over columns.
 
 **cols_nc**: If True allows for negative correlation of columns over rows.
 
 **col_overlap**: If Ture allows for columns overlaps among biclusters.
 
 **row_overlap**: If Ture allows for rows overlaps among biclusters.
 
 **pceru**: Per-comparrison wise error rate to control the number of falsely selected coefficients in the left singular vectors.
 
 **pcerv**: Per-comparrison wise error rate to control the number of falsely selected coefficients in the right singular vector.
 
 **merr**: Convergence threshold.
 
 **iters**: Maximal iteration for detecting each bicluster.
 
 
_Outputs_:

 iSSVD returns the stable solutions of left singular vectors for each bicluster, and right singular vectors from each view for each bicluster. 
 
 **N**: Number of biclusters detected.
 
 **Info**: Stability selection results of left and right singular vectors.
 
 **Sample_index**: The indices of bicluster samples.
 
 **Variable_index**: The indices of bicluster variables. 
 
 **Iterations:** The interations run for each bicluster.
