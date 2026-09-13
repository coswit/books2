# 第5章　深入理解PowerManagerService


本章主要内容：

深入分析Pow erM anagerService。

深入分析Ba eryService和Ba eryStatsService。

本章所涉及的源代码文件名及位置：

```
Pow erM anagerService. java
(fram ew orks/base/services/java/com /a
ndroid/server/Pow er-
M anagerService.java)
com _android_server_PowerM anagerSer
vice. cpp
(fram ew orks/base/services/jni/com _an
droid_server_PowerM anagerService.cpp
)
Pow erM anager. java
(fram eworks/base/core/java/android/o
s/Pow erM anager.java)
W orkSoure. java
(fram eworks/base/core/java/android/o
s/W orkSoure.java)
Pow er. java
(fram eworks/base/core/java/android/o
s/Pow er.java)
android_os_Power. cpp
(fram eworks/base/core/jni/android_os
_Pow er.cpp)
com _android_server_InputM anager.cpp
(fram ew orks/base/services/jni/com _an
droid_server_InputM anager.cpp)
LightService. java
(fram ew orks/base/services/java/com /a
ndroid/server/LightService.java)
com _android_server_LightService. cpp
(fram ew orks/base/services/jni/com _an
droid_server_LightService.cpp)
Ba eryService. java
(fram ew orks/base/services/java/com /a
ndroid/server/Ba eryService.java)
com _android_server_Ba eryService.cpp
(fram ew orks/base/services/jni/com _an
droid_server_Ba eryService.cpp)
ActivityM anagerService. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /Activity-
M anagerService.java)
Ba eryStatsService. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /Ba ery-
StatsService.java)
Ba eryStatsIm pl. java
(fram eworks/base/core/java/com /andr
oid/internal/os/Ba eryStatsIm pl.java)
LocalPowerM anager. java
(fram eworks/base/core/java/android/o
s/LocalPowerM anager.java)
```
