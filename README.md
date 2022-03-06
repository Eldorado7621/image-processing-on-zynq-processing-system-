# image-processing-on-zynq-processing-system-

Performed average filtering operation on a 512 X 512 px image on a Zybo board. The image is stored in the DDR from where it is fecthed to the Image processing IP core . Since all the pixels can not be fetched at the same time, 3 line buffers are used to hold the data in batches.

CREDIT- Thanks to Vipin for the tutorials 
