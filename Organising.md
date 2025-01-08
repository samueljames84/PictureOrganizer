# Organising Mobile Pictures

### Copy photos from mobile to computer

Export all the files using `Picture Organiser` app to temp folder
make sure to backup the `PO_Log file` to future restoration and also for finding picture types example resolution, aspect ratio, also for getting absolute static file name.

### Grouping Photos

Put all photos into `_Main Trunk` folder which is easy to navigate and see all files.
Move required files to `_4K+Orginal` folder which you want to keep the orginal. Finally moved to Library Archive
Move the protrait photos to `_Portrait` folder
Move the files which are not part of the google photos to `_Others` folder. eg. bills, information etc.
All the files inside `_2K` folder will be sent to google photos. (Explained in Resizing Photos section)

### Apply Tags

Apply relavent tags using `EXIF File Operations\API\ui add or modify exif data.vi`

### Resizing photos

Crop all the photos in `_Main Trunk` to 16:9 ratio pictures
Batch rezise `_Main Trunk` using irfanview for 4K Photos use the Long side to `3840px` destination `_4K+Orginal`
Batch rezise `_Portrait` using irfanview set short side to `2160px` destination `_4K+Orginal`
Batch rezise `_4K+Orginal` using irfanview set short side to `1440px` destination `_2K`
