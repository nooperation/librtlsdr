Instructions for obtaining the libusb library.

1. Download the latest precompiled libusb build for windows from http://sourceforge.net/projects/libusb/files/libusb-1.0/
      Or http://sourceforge.net/projects/libusb/files/libusb-1.0/libusb-1.0.18/libusb-1.0.18-win.7z/download
   
2. Extract contents of libusb-x.x.x-win.7z to this directory so the following directory structure can be observed:
	  msvc\libraries\libusb\include\libusb-1.0\
	  msvc\libraries\libusb\MS32\
	  msvc\libraries\libusb\MS64\

3. Copy msvc\libraries\libusb\MS32\libusb-1.0.dll to:
      msvc\20xx\Release
	  msvc\20xx\Debug
	  
4. Copy msvc\libraries\libusb\MS64\libusb-1.0.dll to:
      msvc\20xx\x64\Release
	  msvc\20xx\x64\Debug
