I cloned this from raveeshbhalla, and made some minor modifications so that it would work on Windows.

This script helps encode multiple .jpeg, .png and .tiff files to .webp in one go, instead of individual lines of script for each image.

Steps: 
1. Download the Precompiled WebP utilities and library from the following link - https://developers.google.com/speed/webp/download
2. Extract the downloaded file from Step 1.
3. Add cwebp as a System Environment Variable (pointing to your util: cwebp.exe); you can also add the utilities and library folder to your Path
4. Place the contents of this library (i.e. ScriptBuilder.java, the convertscript.bat file and the input and output folders) in the root of the extracted folder.
5. Open up Terminal and go to the root of the folder extracted in Step 2.
6. Create two folders in the root of the folder extracted in Step 2. Name them "input" and "output".
7. Place all the images you want to be converted to .webp in the input folder.
8. To run the script, simply enter "convertscript.bat"
9. The process can take a while, depending on the number of images. After entering the required parameters in the beginning (3 of them) you can let it run in the background.

Thanks to:
raveeshbhalla for the original source
https://github.com/raveeshbhalla/Multiple-Webp-Encoder