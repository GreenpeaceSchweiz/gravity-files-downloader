# gravity-files-downloader
Batch download files attached to form entries.

Takes a Gravity Forms CSV export that contains links to uploaded files. Then puts all the files into a zip archive for download. Supports multiple uploaded files per form entry.

Make sure:
* The server you run this script on has decent disc space and a long timeout. Depending on the number of files, the process might take a while.
* The column in the CSV file containing the files needs to be named "uploads".


