lte-me3630.c是4G模块的驱动程序，主要负责模块上电初始化。
“i”开头的5个文件都是4G模块拨号（默认使用的是dhcp拨号，而不是ppp拨号）上网的脚本文件，有比较详细的注释。
ME3630移植最重要的文件就是动态库文件libreference-ril.so