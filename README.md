# Light Trail Stack

This is a Photoshop UXP script for blending a sequence of time-lapse night photos together to create a very long exposure light trail effect (e.g. star trails) or making a light trail animation (see this [video at 00:20](https://vimeo.com/853928007#t=20&share=copy&muted=1) for an example). I used to do this using another program ([StarStax](https://markus-enzweiler.de/software/starstax/)). I created this script to do the same in Photoshop to simplify my workflow.

**Usage:**
* Download the script [LightTrailStack.psjs](https://github.com/lightcatcher1001/Light-Trail-Stack/blob/main/LightTrailStack.psjs) to your computer.
* In Photoshop, go to the File menu -> Scripts -> Browse, open the downloaded script to run it.
* When the dialog box appears:
    - Click the button to select the folder containing the source images. Note: stacking order will be same as the alphabetical order of the file names.
    - Optional: click the button to select an output folder if you want to output the intermediate state after each image is blended (used to create light trail animation timelapse).
    - Optional: click the button to select a Photoshop file containing a mask if you want mask out (exclude) a certain region of the source images during blending.
* Click OK to start the blending process.
