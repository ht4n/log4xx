DISCLAIMERS: all the source code belongs to the original authors per original Apache license. 
The minor syntactical modification to the source code is made only so that it can be built with VS2013.

A fully compile-able and working copy of Log4xx 0.10.0 (http://logging.apache.org/log4cxx/download.html) that can build with Visual Studio 2013.

Thanks to the guide posted in http://www.codeproject.com/Tips/492585/How-to-build-log-cxx-with-Visual-Studio.

Other helpful resources:
----------------------------------------------
http://apr.apache.org/compiling_win32.html

Dependencies:
-----------------------------------------------
-apr-1.5.1         http://apr.apache.org/download.cgi
-apr-util-1.5.3    http://apr.apache.org/download.cgi


NOTE: if apr-util cannot resolve some symbols on XML_ParserCreate - make sure to build apr-util\xml\expat\lib\xml.vcxproj
