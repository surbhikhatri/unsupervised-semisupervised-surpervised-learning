# Monte-Carlo Simulation
: Repeat the following procedures for supervised, un-
supervised, and semi-supervised learning
M
= 30 times, and use randomly se-
lected train and test data (make sure you use 20% of both the positve and nega-
tive classes as the test set). Then compare the
average
scores (accuracy, precision,
recall,
F
1
-score, and AUC) that you obtain from each algorithm


Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image. A few of the images can be found at http://www.cs.wisc.edu/~street/images/

Additional Variable Information
1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

	a) radius (mean of distances from center to points on the perimeter)
	b) texture (standard deviation of gray-scale values)
	c) perimeter
	d) area
	e) smoothness (local variation in radius lengths)
	f) compactness (perimeter^2 / area - 1.0)
	g) concavity (severity of concave portions of the contour)
	h) concave points (number of concave portions of the contour)
	i) symmetry 
	j) fractal dimension ("coastline approximation" - 1)