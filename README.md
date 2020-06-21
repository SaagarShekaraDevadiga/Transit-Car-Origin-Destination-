# Transit & Car Origin Destination (OD) 
Data Manipulation for visualizing Transit and Car Origin Destination (OD) Data at a statistical zone 3 level for Greater Brisbane

Aim 1:
Change a M x M matrix to a dataframe of three columns having values for Origin, Destination and Observations
  1.  Make a temporaray Dataframe for trapping insdie the loop for split and combine operation
  2.  Split the data to the selected directory and save each file as its respective zone number
  3.  Combine operation to stich all the split data into one file
 
 
Aim 2:
Map the lattitude and longitude to each origin destination pair for visualization
  .
  Mapping rules
  1.  Make a dictinory having a key-value pair of the data needed to be mapped
  2.  Create a column for which the data must be mapped in the original dataset
  3.  Use the Map function and feed the dictinoray as an input
