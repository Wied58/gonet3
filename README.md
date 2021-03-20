# gonet3.py



### gonet3_1_second.py and gonet4.py
```
I realize adding these to the gonet3 repo is poor GitHub form, but I just wanted to get these out too the group without taking on a git/GitHub science project.

gonet3_1_second.py takes a single one second image for the calibration team

gonet4.py uses picamera instead of raspistill

```
incorporated changes of lines 72, and 604 to manage thumbnails
added WB settings to exif and tag
change date format to YYMMDD
parametarized white balance gains
manually set white balance
```

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
