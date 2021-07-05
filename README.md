# png_to_jpd
BASH script to duplicate directory structure from source directory to destination directory, copying only files of type '.png'. These '.png' files are then convert to '.jpg'  files in the destination directory. The source directory is not changed. If the destination directory does not exist before execution, it will be created. If the destination directory already exist, new '.png' files will be copied in and any existing '.png' files with the same names will be replaced.