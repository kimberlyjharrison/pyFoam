# pyFoam
Thermal test data post-processing analysis and visualization tool

### Libraries
Pandas, Matplotlib

### Background
As a laboratory manager, one of the more time-intensive portions of my job is to deal with post-test data processing.  I created pyFoam after discovering multiple issues with our legacy VBA-based tool.  Namely, for large datasets, the tool would cause my computer to lock up any Office programs and render me usesless for up to 20 minutes while it chugged on the data to make a few graphs and tables.

### Approach
pyFoam takes the test data that has been collected from the data acquisition system in the form of a excel sheet and parses the information into a Pandas DataFrame.  From there, pyFoam will graph and analyze each sample tested using Matplotlib.

### Example Case
Provided as an example, a non-proprietary dataset is analyzed to demonstrate pyFoam's analytics capabilities. (Note: input data not included).  The legacy tool took 8 minutes to graph whereas pyFoam took 11 seconds.

### Note
I am continuously tweaking a private version of pyFoam to meet specific business needs, and will push updates to the public version as appropriate.