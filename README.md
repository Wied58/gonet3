# gonet3.py

### Version 15.6
```
incorporated changes of lines 72, and 604 to manage thumbnails
added WB settings to exif and tag
change date format to YYMMDD
parametarized white balance gains
manually set white balance
```
### Version 15.5
```
parameterized white balance gains
manually set white balance
added scratch directory cleanup to gonet.log
creates images, scratch, and thumbs dirs if they do not exist
added readable (non unix)  start time to log
remove 0 length files from scratch, and move remaining jpg files to image
added remove gonet from crontab if disk is full
moved clean scratch directory to beginning
```
