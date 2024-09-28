android-support-v7-appcompat
--------
Library Project including compatibility ActionBar.

This can be used by an Android project to provide
access to ActionBar on applications running on API 7+.

There is technically no source, but the src folder is necessary
to ensure that the build system works.  The content is actually
located in libs/android-support-v7-appcompat.jar.
The accompanying resources must also be included in the application.

core-lambda-stubs.jar
--------
this lib need java 1.8 target compilance
and maybe leaks memory, if you make applications for android wearable objects
be sur to have a correct toolchain and an os compilant with this functions 
see informations about this subject (since c++11)
https://en.cppreference.com/w/cpp/language/auto
https://en.cppreference.com/w/cpp/language/lambda
