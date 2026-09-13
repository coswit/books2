# 第4章　深入理解PackageManagerService


本章主要内容：

分析PackageM anagerService。

本章所涉及的源代码文件名及位置：

```
System Server. java
(fram ew orks/base/services/java/com /a
ndroid/server/System Server.java)
IPackageM anager. aidl
(fram eworks/base/core/android/java/c
ontent/pm /IPackageM anager.aidl)
PackageM anagerService. java
(fram ew orks/base/services/java/com /a
ndroid/server/pm /PackageM anagerServ
ice.java)
Setti ngs. java
(fram ew orks/base/services/java/com /a
ndroid/server/pm /Setti ngs.java)
System UI的AndroidM anifest.xm l
(fram eworks/base/package/System UI/
AndroidM anifest.xm l)
PackageParser. java
(fram eworks/base/core/java/android/c
ontent/pm /PackageParser.java)
com m andline. c
(system /core/adb/com m andline.c)
insta d. c
(fram ew orks/base/cm ds/insta d/insta
d.c)
com m ands. c
(fram eworks/base/cm ds/insta d/com
m ands.c)
```

pm脚本文件

```
(fram eworks/base/cm ds/pm /pm)
Pm . java
(fram eworks/base/cm ds/pm /src/com /
android/com m ands/pm /Pm .java)
DefaultContainerService. java
(fram eworks/base/packages/defaultco
ntainerservice/src/com /android/default
containerservice/DefaultContainerServic
e.java)
UserM anager. java
(fram ew orks/base/services/java/com /a
ndroid/server/pm /UserM anager.java)
UserInfo. java
(fram eworks/base/core/android/java/c
ontent/pm /UserInfo.java)
```
