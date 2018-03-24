This fork of ZotFile changes the extraction code in PDFJS to retrieve the
subject field from annotations instead of the author field. The subject text
is accessible in ZotFile from the %(label) variable.

To build ZotFile:

$ git clone git@github.com:andyloveless/zotfile.git
$ cd zotfile/
$ make

The following is produced, which can be installed as a Zotero add-on.

zotfile-5.0.7-fx.xpi
