# cp-colocalization
#Colocalization with CellProfiler

Su_Cell_ColocalizationSingle.cpproj is a CellProfiler project for quantifying object-based colocalization in whole-slide images of tumors.

It is modified from the Human Cells and Colocalization examples at http://cellprofiler.org/examples/.

##Usage

In CellProfiler, *File > Open Project...*.
Drag a folder of input images onto the indicated area in the CellProfiler window.

###Selecting images

1. Click **Apply filters to the file list**. This removes non-image files.
2. In the upper left corner of the CellProfiler window, click **Metadata**, then **Update**. Next to each DAPI image name, you should see the name of the sample.
3.  In the upper left corner of the CellProfiler window, click **Names And Types**, then **Update**. For each sample, you should see the filenames for the blue (DAPI), green (GPF), and red (Y-2E-C) channels.

##Credits

The project was created by Theresa Swayne for the lab of Gloria Su at Columbia University.
Funding was provided by the National Cancer Institute of the NIH, grant P30CA13696.
