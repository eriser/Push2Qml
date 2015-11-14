Build instructions (32-bit):
1. Microsoft Visual Studio Express 2013 for Windows Desktop with Update 4
2. Install Qt 5.5.0 from http://download.qt.io/archive/qt/5.5/5.5.0/qt-opensource-windows-x86-msvc2013-5.5.0.exe
3. Download libusb-1.0.20.7z from http://libusb.info/
4. Extract include\libusb-1.0\libusb.h, MS32\dll\libusb-1.0.dll and MS32\dll\libusb-1.0.lib into this directory
5. Open Push2Qml.pro using Qt Creator
6. Change the build configuration from Debug to Release
7. Click Build

Build instructions (64-bit):
1. Microsoft Visual Studio Express 2013 for Windows Desktop with Update 4
2. Install Qt 5.5.0 from http://download.qt.io/archive/qt/5.5/5.5.0/qt-opensource-windows-x86-msvc2013_64-5.5.0.exe
3. Download libusb-1.0.20.7z from http://libusb.info/
4. Extract include\libusb-1.0\libusb.h, MS64\dll\libusb-1.0.dll and MS64\dll\libusb-1.0.lib into this directory
5. Open Push2Qml.pro using Qt Creator
6. Change the build configuration from Debug to Release
7. Click Build

Install instructions:
1. Copy Push2Qml.exe executable to C:\ProgramData\Ableton\Live 9 Suite\Program
2. Drag ColorAnimationTest.qml onto Push2Qml.exe. Alternatively, you can use any QML file.