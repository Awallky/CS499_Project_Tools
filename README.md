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
