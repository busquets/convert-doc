# convert-doc

Convert-doc is a script which uses http://docspal.com to convert Microsoft Office files.
It can be useful for a Libreoffice user who deals often with these proprietary File Formates.

These conversations are implemented:

  * odt  --> docx
  * doc  --> odt
  * doc  --> pdf
  * docx --> pdf

The Debian Package is for Debian based Distributions (Debian, Ubuntu , LinuxMint...)
It can installed with: `sudo dpkg -i convert-doc.deb`
The tar.xz file is a Package for Arch Linux.
`pacman -U convert-doc-1.0-0-any.pkg.tar.xz`
Installed, there should a context menu for doc, docx and odt files appear, which allows converting them. (Also multiple files parallel)