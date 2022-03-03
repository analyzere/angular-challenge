# Goal

Given a list of strings in a flat folder structure of: “root/directory/directory/file.ext” write a tree-style file picker component using the angular material library.

## Requirements

* Main page has an input dialog which will display the selected file name from the file browser
* The browse button will launch the file browser modal
* Files are represented as a tree
* Single selection on file leaf nodes
* Upload button is enabled after a file is selected
* On click of the upload button an indeterminate progress bar will appear and fade after 5 seconds
** No actual file upload needs to occur in this prototype
* After simulated progress is complete a message “Upload complete!” should appear
* Progress and message will reset to invisible when a new file is selected

## Assumptions

* Single select files
* Could have empty directories in file browser
* Disable upload button if file is not selected; disable ok button within file browser if file is not selected
* Your implementation can use the Sample file list below
** It should be easy to replace that list with another
* File input field is read only (cannot type)

## Bonus

* Responsiveness - when mobile device screen size is detected
  * Top nav should collapse into a side nav
* Routing – include routes for upload page and history page
* History page
  * History page keeps a log of previously uploaded files
  * Ability to clear history from clear button

## Submission guidelines:

You can submit the solution in anyway you are comfortable with (GitHub, Zipped file, Google drive, etc)

## Sample file list

    root/dir1/diry/file3.ext
    root/dir2/dirx/file.ext
    root/dir2/dirx/file1.ext
    root/dir2/file2.ext
    root/dir3/dirz/file4.ext
    root/dir4/dira/file5.ext
    root/dir5/dirb/file6.ext
    root/dir6/dir0/file7.ext
    root/dir6/dir0/file8.ext
    root/dir6/dir0/file9.ext
    root/dir7/dirc/dire/
    root/dir7/dirc/dirv/file11.ext
    root/dir7/dirc/file12.ext
    root/file10.ext

## Design spec

The images are for guidance.  You need not make write CSS to force your UI to match, and the appearance is up to you.

[Design images](Design-Spec.pdf)
