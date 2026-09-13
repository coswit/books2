# 第6章　深入理解ActivityManagerService


中各种计量工具及统计对象的理解。

本章主要内容：

详细分析ActivityM anagerService。

本章所涉及的源代码文件名及位置：

```
System Server. java
(fram ew orks/base/services/java/com /a
ndroid/server/System Server.java)
ActivityM anagerService. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /ActivityM anagerServi
ce.java)
ContextIm pl. java
(fram ew orks/base/core/java/android/a
pp/ContextIm pl.java)
ActivityThread. java
(fram ew orks/base/core/java/android/a
pp/ActivityThread.java)
ActivityStack. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /ActivityStack.java)
Am . java
(fram eworks/base/cm ds/am /src/com /
android/com m ands/am /Am .java)
ProcessRecord. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /ProcessRecord.java)
ProcessList. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /ProcessList.java)
Runtim eInit. java
(fram eworks/base/core/java/com /andr
oid/internal/os/Runtim eInit.java)
```
