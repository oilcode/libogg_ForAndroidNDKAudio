# libogg_ForAndroidNDKAudio

这是一个AndroidStudio工程，用来把 libogg-1.3.3 和 libvorbis-1.3.6 两个库编译成一个 libogg.a 库。
生成的 libogg.a 库，可以用在其他的安卓项目中，提供对ogg音频文件解码的功能。

本工程是由源码中的三个工程合并得来，
libogg
libvorbis
libvorbisfile
在源码中，这三个工程各自生成一个库文件。合并成本工程后，只生成一个库文件。

ogg/src 目录内有3个c文件不需要编译，这3个c文件的后缀被修改成了 cNoBuild 。
barkmel.c
psytune.c
tone.c

根据实际的目录结构，修改了个别文件中的#include语句。



