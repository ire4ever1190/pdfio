Changes in PDFio
================


v1.1.0 (Month DD, YYYY)
-----------------------

- Added `pdfioFileCreateTemporary` function (Issue #29)
- Added `pdfioDictIterateKeys` function (Issue #31)
- Added `pdfioContentPathEnd` function.
- Added protection against opening multiple streams in the same file at the
  same time.
- Fixed "install-shared" target (Issue #32)
- Fixed `pdfioContentMatrixRotate` function.


v1.0.1 (March 2, 2022)
----------------------

- Added missing `pdfioPageGetNumStreams` and `pdfioPageOpenStream` functions.
- Added demo pdfiototext utility.
- Fixed bug in `pdfioStreamGetToken`.


v1.0.0 (December 14, 2021)
--------------------------

- First stable release.


v1.0rc1 (November 30, 2021)
---------------------------

- Fixed a few stack/buffer overflow bugs discovered via fuzzing.


v1.0b2 (November 7, 2021)
-------------------------

- Added `pdfioFileCreateOutput` API to support streaming output of PDF
  (Issue #21)
- Fixed `all-shared` target (Issue #22)
- Fixed memory leaks (Issue #23)
- Updated `pdfioContentSetDashPattern` to accept `double` values (Issue #25)
- Added support for reading and writing encrypted PDFs (Issue #26)
- Fixed some issues identified by a Coverity scan.


v1.0b1 (August 30, 2021)
------------------------

- Initial release
