# Image-Alignment-and-Stitching
### Input Images
![image_stitched](https://github.com/Dherya27/Image-Alignment-and-Stitching/blob/main/input_images.png)

### Detected Keypoints using SIFT(Scale Invariant Feature Transform)
![keypoints](https://github.com/Dherya27/Image-Alignment-and-Stitching/blob/main/keypoints.png)

### Feature matching using Brute-Force matcher with euclidean distance between keypoints and apply a 1NN/2NN ratio test according to Lowe's paper to identify good matches.
![faeture_matching_ref_img3](https://github.com/Dherya27/Image-Alignment-and-Stitching/blob/main/feature_matching_ref_img3.png)

### Using RANSAC to remove outliers to estimate the best homography, and image stitching using the OpenCV function(warpPerspective).
![faeture_matching_sttiched1_img1](https://github.com/Dherya27/Image-Alignment-and-Stitching/blob/main/feature_matching_imgstitched_img1.png)
![feature_matching_stitched2_img4](https://github.com/Dherya27/Image-Alignment-and-Stitching/blob/main/feature_matching_imgstitched2_img4.png)

### Final Stitched Image
![stitched_image](https://github.com/Dherya27/Image-Alignment-and-Stitching/blob/main/final_stitched_image.png)
