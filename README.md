# pyFoam
Thermal test data post-processing analysis and visualization tool

### Libraries
Pandas, Matplotlib

### Background
As a laboratory manager, one of the more time-intensive portions of my job is to deal with post-test data processing.  I created pyFoam after discovering multiple issues with our legacy VBA-based tool.  Namely, for large datasets, the tool would cause my computer to lock up any Office programs and render me usesless for up to 20 minutes while it chugged on the data.

### Approach
pyFoam takes the test data that has been collected from the data acquisition system in the form of a excel sheet and parses the information into a Pandas DataFrame.  From there, pyFoam will graph and analyze each sample tested.

### Example Case
The breaking point came for me on a large dataset that included 6 test samples with 7 thermocouples per sample over a 5 day period (data recorded every 10 minutes).  Using the legacy VBA-based processing tool, processing the data took between 15-30 minutes.  Using pyFoam, it takes under 16 seconds!
