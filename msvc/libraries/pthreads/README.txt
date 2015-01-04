Instructions for obtaining Sourceware's POSIX Threads library. 
This is only required to build the following projects: rtl_adsb, rtl_fm, rtl_power, rtl_tcp

1. Download the latest precompiled pthreads build for windows from https://sourceware.org/pthreads-win32/ 
      Or ftp://sourceware.org/pub/pthreads-win32/pthreads-w32-2-9-1-release.zip
   
2. Extract contents of threads-w32-x-x-x-release.zip to this directory so the following directory structure can be observed:
      msvc\libraries\pthreads\Pre-built.2\include
      msvc\libraries\pthreads\Pre-built.2\lib

3. Copy msvc\libraries\pthreads\Pre-built.2\dll\x86\pthreadVC2.dll to Release and Debug Directories of msvc\20XX\

4. Copy msvc\libraries\pthreads\Pre-built.2\dll\x64\pthreadVC2.dll to Release and Debug Directories of msvc\20XX\
