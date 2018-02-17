### modify_annotation_path ###
A script for modifying annotation .xml file's path label to a new path.
Useful for when image annotations are created on one machine and then uploaded for use on another.
Obviously the path will no longer be correct and prevents people from manually entering new paths for every file.

# Commands: 
           1. You can provide no arguments, where you will be prompted to
              select the .xml file's directory and the new path string for the files
           2. You can provide a single command line argument for the new path string
              and you will be prompted to select the .xml file's directory
           3. You may provide two arguments where you provide the .xml file's directory
              and the newly desired path string

### modify_images ###
A script with a few different commands for modifying images
## Note: make sure to install PIL after your regular python package is installed
# Program: A set of image modification commands
# Command set:
  1)   file command, use -f as the secnd cli argument
       rotate a named image n times at x degrees
       <program name> -f <file name> <(int)number of rotations> <(int)degrees per rotation>
  
  2)   select command, use -sel as second cli argument, selects file from file explorer box
       <program name> -sel <(int)number of rotations> <(int)degrees per rotation>
         
  3)   directory command, use -d as the secnd cli argument
       similar to command 1 except it looks through a directory of and
       modifies any with a .jpg, .bmp, .png, or .gif file extension
       <program name> -d <directory of images> <(int)number of rotations> <(int)degrees per rotation>
         
  4)   pixel command, use -pix as the secnd cli argument
       modifies some pixels in a named image at the x and y coordinates
       <program name> -pix <-x/-y/-f> <x val/y val/file name> <-x/-y/-f> <x val/y val/file name> <-x/-y/-f> <x val/y val/file name>
         
  5)   contrast command, use -cont as second cli argument, creates copies of file with
       a few different sets of color contrasts applied to it.
       <program name> -cont
