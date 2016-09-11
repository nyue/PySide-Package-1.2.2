# PySide-Package-1.2.2
Super build of all three (3) packages to form a deployable PySide 1.2.2 archive package

## External archives

+ Tools-0.2.15.tar.gz
+ pyside-qt4.8+1.2.2.tar.bz2
+ shiboken-1.2.2.tar.bz2

were taken from http://wiki.qt.io/PySide

## Customization

+ PSP_CMAKE_INSTALL_PREFIX Installation location
+ PSP_PYTHON_EXECUTABLE Python executable
+ PSP_PYTHON_INCLUDE_DIR Python include directory
+ PSP_PYTHON_LIBRARY Python link library
+ PSP_QT_QMAKE_EXECUTABLE Qt's qmake executable

## Notes :
No plans to make this build on Windows until Python is easily buildable from source for different Windows compiler via CMake
