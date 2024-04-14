# Windors-GEDitCOM

This repository contains a <b>GEDitCOM II</b> file (and one that is also compatible with <b>GEDitCOM</b>) for descendants of Queen Elizabeth II. In the repository, the genealogy file looks like a folder, but when viewed on the Mac, the entire folder is a MacOS package that can be opened and viewed in <b>GEDitCOM II</b> or <b>GEDitCOM</b>. To learn about these applications, visit <a href="http://www.geditcom.com">geditcom.com</a>.

For those not working on a Mac or not using <b>GEDitCOM II</b> or <b>GEDitCOM</b>, this repository contains a complete GEDCOM file titled <code>Windsors.gedpkg/Windors.ged</code> along with linked image files in the <code>multimedia</code> folder. <b>GEDitCOM II</b> or <b>GEDitCOM</b> store links to those image files as relative to the location of the main package or relative to <code>Windows.gedpkg</code>. For example a link to <code>anne.jpg</code> in the <code>multimedia</code> folder will be stored in a GEDCOM multimedia record in <code>Windors.ged</code> as <code>multimedia/anne.jpg</code>. If you want to import this GEDCOM data to other software, you have rearrange the files to make such links be relative to <code>Windors.ged</code> instead of <code>Windows.gedpkg</code>. This change is easily done as follows:

1. Copy <code>Windsors.ged</code> to a different folder
2. Copy the entire <code>multimedia</code> folder to the same folder as the copied <code>Windsors.ged</code>
3. Import that GEDCOM file to any application that claims to import GEDCOM data

This file is 100% valid GEDCOM 5.5.1 data, but does use some custom tags. If the importing software has problems, that software may have limitations in their GEDCOM support. Most software will work, but many will fail to find the multimedia objects. The above process has all images linked by a valid method using relative path names to an image in the <code>multimedia</code> folder. If the software you use does not find any multimedia objects either that software simple does not support importing multimedia objects (which is common) or it does not understand the use of paths relative to the GEDCOM file.
