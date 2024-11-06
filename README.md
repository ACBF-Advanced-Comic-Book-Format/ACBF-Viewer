# ACBF-Viewer
ACBF Viewer is a Viewer for comic book files in ACBF format written using GTK toolkit.
* It is capable of displaying comic books in 3 viewing modes (one page, zoom to page width and zoom on a certain frame/comic book panel)
* It displays various comic book metadata, table of contents
* It can easily switch between different text-layers (translations). Text-layers are drawn automatically to fit into defined text-areas (bubbles), different fonts can be defined for semantic tags used on text-layers.
* Comic book library can be filled with comic books which than can be sorted and filtered by different kinds of available metadata.

# Dependencies
ACBF Viewer uses/depends on following libraries:
* GTK (pygtk) to draw user interface
* lxml (python-lxml) to work with XML files
* Python Imaging Library (PIL) to work with images 
* matplotlib for drawing charts in library info dialog 

# Installation

* Windows
No installation is needed for Windows version. Just download the windows ACBF Viewer package 
(e.g. ACBFViewer-1.03_win32.zip), extract it and run acbfv.exe.

# Linux
You will need to install required libraries first:

sudo apt-get install python-lxml python-imaging python-matplotlib

Download and extract linux installation package (for example ACBFViewer-1.03_linux.tar.gz). 
Then navigate to the directory where you extracted it and run:

sudo ./install.py install

After install finishes properly you should be able to find ACBF Viewer in Applications Launcher.

To uninstall run:

sudo ./install.py uninstall
