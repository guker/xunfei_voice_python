## xunfei_voice_python

1.doc目录下存放开发文档等；

2.lib目录下存放SDK需要调用的静态库（静态库版本才会提供）；

3.include目录下存放SDK需要引用的头文件；

4.Example目录下存放我们提供的几个例子，每个例子下都有Makefile文件，在当前目录make即可；

5.bin目录下存放SDK需要调用的动态库（动态库版本才会提供）、命令词列表样例、abnf语法样例、符合标准的语音文件样例、配置文件等，make之后的example可执行程序也会拷贝至此，请在此目录下运行，否则会运行失败；

6.prj目录下提供makeall和cleanall两个脚本，可以快速的编译和清除所有的例子。
7.在64位的Linux 系统中，请使用bin\x64的libmsc.so替换原bin下的so文件。
8.若16k音频aue=speex-wb，8k音频识别aue=speex，