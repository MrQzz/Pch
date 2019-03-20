# Pch
常用的一些引用

创建pch的步骤

1. 在build setting 里面 
PRECOMPILE_PREFIX_HEADER = YES
2. prefix header 写法
  $(SRCROOT)/BOBOHeader.pch   在根目录下的pch 文件
