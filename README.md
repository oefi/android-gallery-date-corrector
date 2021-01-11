# android-gallery-date-corrector
PROBLEM:
After copying images to Android devices from external storage,
the sorting of images is messed up. That is because a lot of gallerys
sort images by date-touched and the restoring process touches everything
at moment of restoration.

SOLUTION:
To correct this, files will be touched according to their date-created,
which is stored in the file name.
