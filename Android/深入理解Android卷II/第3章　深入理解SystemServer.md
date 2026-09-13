# 第3章　深入理解SystemServer


类”对Android 2.2中的M essageQueue和L本o章op主er要有内详容细：介绍，读者不妨下载电子版阅读一下。

分析System Server。

分析EntropyService、DropBoxM anagerService、DiskStatsService。

分析DeviceStorageM onitorService、Sam plingProfil erService以及ClipboardService。

本章所涉及的源代码文件名及位置：

```
System Server. java
(fram ew orks/base/services/java/com /a
ndroid/server/System Server.java)
com _android_server_System Server. cpp
(fram ew orks/base/services/jni/com _an
droid_server_System Server.cpp)
System _init. cpp
(fram ew orks/base/cm ds/system _serve
r/library/System _init.cpp)
EntropyService. java
(fram ew orks/base/services/java/com /a
ndroid/server/EntropyService.java)
DropBoxM anagerService. java
(fram ew orks/base/services/java/com /a
ndroid/server/DropBox-
M anagerService.java)
ActivityM anagerService. java
(fram ew orks/base/services/java/com /a
ndroid/server/am /ActivityM anagerServi
ce.java)
DiskStatsService. java
(fram ew orks/base/services/java/com /a
ndroid/server/DiskStatsService.java)
dum psys. cpp
(fram eworks/base/cm ds/dum psys/du
m psys.cpp)
DeviceStorageM onitorService. java
(fram ew orks/base/services/java/com /a
ndroid/server/Device-
StorageM onitorService.java)
Sam plingProfil erService. java
(fram ew orks/base/services/java/com /a
ndroid/server/Sam pling-
Profil erService.java)
Sam plingProfil erIntegration. java
(fram eworks/base/core/java/com /andr
oid/internal/os/Sam pling-
Profil erIntegration.java)
Sam plingProfil er. java
(libcore/dalvik/src/m ain/java/dalvik/sy
stem /profler/Sam plingProfler.java)
ClipboardService. java
(fram ew orks/base/services/java/com /a
ndroid/server/ClipboardService.java)
ClipboardM anagerService. java
(android.content.ClipboardM anager
)(fram eworks/base/core/java/android
/content/Clipboard-M anager.java)
ClipboardM anagerService. java
(android.text.ClipboardM anager)(fra
m eworks/base/core/java/android/text/C
lipboard-M anager.java)
ClipData. java
(fram eworks/base/core/java/android/c
ontent/ClipData.java)
```
