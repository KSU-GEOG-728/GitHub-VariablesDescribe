# GitHub-VariablesDescribe
*Exercise for GEOG 728 Programming for Geographic Analysis at Kansas State University*

### Instructions:

Accept the GitHub Classroom assignment <code>GitHub-VariablesDescribe</code> and clone the new repository as a local personal repository.  Uncompress the provided ZIP file to access the ArcGIS Pro project file in your local repository workspace.  The only file which needs to be pushed to origin at the conclusion of the exercise is a single Python script.  Should you encounter difficulties during the week, seek assistance by posting an issue in GitHub.

### Task:

Edit the provided stand-alone Python script called <code>GitHub-VariablesDescribe.py</code> so that it accomplishes the following objectives and/or includes these specific features:

1. Incorporates any needed revisions to successfully meet last week's exercise requirements.
2. Uses variable names for tool parameters - inputs and final output - rather than "hard coding" filenames.  You may hard code any intermediate results and save them in your current workspace.
3. Reprojects final feature output (clipped rivers) to a new file using geographic coordinates based upon the WGS-84 datum.
4. Prints (to console) the new base name of the reprojected file, the original spatial reference name of the clipped rivers feature class, and the new spatial reference name of the final re-projected output.
   
Double-check that your script includes a complete header section, uses good commenting, reads input and writes output to current workspace, and is able to overwrite existing output files.  Surprisingly, one of the big challenges for you this week is the reprojection step included above.  To do this properly in a script, I *STRONGLY* encourage you to review the ArcPy documentation for the <code>SpatialReference</code> class.  The <code>SpatialReference</code> class should not be confused with the similarly named property of the <code>Describe</code> function!

## Rubric:

Review the assignment rubric available on Canvas for additional details on how your work will be assessed. 

## Submission:

Commit your code changes for <code>GitHub-VariablesDescribe</code> to your assignment repository on GitHub.
