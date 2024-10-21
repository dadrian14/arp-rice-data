# arp-rice-data
Dataset referenced in article: (include reference below) "Rice-distributed autoregressive time series modeling of magnitude functional MRI data"

The 14 ".RData" files provide the MR images acquired with TR = 1.0 s during a block design experiment. The design included 
an initial 16 s rest period followed by 19 epochs of 16 s of right-hand tapping alternating with 16 s of rest -- 624 time points in all. The data were acquired with the 
body coil. 

Each file consists an array of either real- or the imaginary-valued data, where the number in the file name corresponds to the axial slice (ordered from superior 
to inferior). Each of the seven slices has a thickness of 2.5 mm. 
Thus, each file consists of a temporal sequence of 624 slices of dimension 128 x 128 with a 24.0 cm FOV.
