# cp-colocalization
## Colocalization with CellProfiler

Su_Cell_ColocalizationSingle.cpproj is a CellProfiler project for quantifying object-based colocalization in whole-slide images of tumors.

It is modified from the Human Cells and Colocalization examples at http://cellprofiler.org/examples/.

## Usage

In CellProfiler, *File > Open Project...*.

In the middle of the CellProfiler window, under **File List**, right-click and *Clear File List*.

Drag a folder of input images onto the indicated area in the CellProfiler window.

### Selecting images

1. Click **Apply filters to the file list**. This removes non-image files.
2. In the upper left corner of the CellProfiler window, click **Metadata**, then **Update**. 
    - You'll see a table of filenames. 
    - In the **Sample** column, next to each DAPI image name, you should see the name of the sample. 
    - Non-DAPI images should say "None."
3.  In the upper left corner of the CellProfiler window, click **Names And Types**, then **Update**. 
    - For each sample, under the columns "OrigBlue", "OrigGreen," and "OrigRed," you should see the filenames for the blue (DAPI), green (GPF), and red (Y-2E-C) channels respectively.

### Setting the output location

In the lower left corner of the CellProfiler window, click **View output settings** and then set the output folder.

### Analyzing images

In the lower left corner of the CellProfiler window, click **Analyze Images**. 

The analysis will take a few minutes per large image. 

The following will be saved to the output folder:
1. A CSV file containing counts and area of all red cells, all green cells, and colocalized (positive for both red and green) cells.
2. PNG images showing outlines of detected red cells, detected green cells, and colocalized cells respectively.

## Credits

The project was created by Theresa Swayne for the lab of Gloria Su at Columbia University.
Funding was provided by the National Cancer Institute of the NIH, grant P30CA13696.
