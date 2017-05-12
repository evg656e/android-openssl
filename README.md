android-openssl
===============

Android NDK openssl build script for original repository(https://www.openssl.org/)

modified version of setenv-android.sh and build script support all architectures in the android NDK

see details : http://wiki.openssl.org/index.php/Android

Windows instructions
===============

 * install msys2, follow instructions on site: http://www.msys2.org/
 * run msys and install additional packages needed by scripts: pacman -S perl tar make
 * chande dir to folder with scripts, e.g.: cd /c/path/to/android-openssl
 * set path to Android NDK, e.g.: ANDROID_NDK_ROOT=/c/path/to/android-ndk; export ANDROID_NDK_ROOT
 * run scripts: ./build-all-arch.sh
