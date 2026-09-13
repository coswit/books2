# 第7章　深入理解ContentProvider


的处理流程。

本章主要内容：

深入分析ContentProvider的创建和启动，以及SQLite相关的知识点。

深入分析Cursorquery和close函数的实现。

深入分析ContentResolveropenAssetFileDescriptor函数的实现。

本章所涉及的源代码文件名及位置：

```
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
M ediaStore. java
(fram eworks/base/core/java/android/p
rovider/M ediaStore.java)
ContentResolver. java
(fram eworks/base/core/java/android/c
ontent/ContentResolver.java)
ContentProvider. java
(fram eworks/base/core/java/android/c
ontent/ContentProvider.java)
M ediaProvider. java
(package/providers/M ediaProvider/src
/java/com /android/M ediaProvider/M edi
aProvider.java)
SQ LiteDatabase. java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteDatabase.java)
SQLiteCom piledSql. java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteCom piledSql.java
)
android_database_SQ LiteDatabase. cpp
(fram eworks/base/core/jni/android_da
tabase_SQLiteDatabase.cpp)
android_database_SQLiteCom piledSql.
cpp
(fram eworks/base/core/jni/android_da
tabase_SQLite-Com piled-Sql.cpp)
sqlit e3_android. cpp
(external/sqlit e3/android/sqlit e3_andr
oid.cpp)
SQ LiteQueryBuilder. java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteQueryBuilder.java
)
SQ LiteCursorDriver. java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteCursorDriver.java)
SQ LiteQuery. java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteQuery.java)
SQ LiteCursor. java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteCursor.java)
SQ LiteProgram . java
(fram eworks/base/core/java/android/d
atabase/sqlit e/SQ LiteProgram .java)
CursorToBulkCursorAdaptor. java
(fram eworks/base/core/java/android/d
atabase/CursorToBulkCursorAdaptor.jav
a)
BulkCursorToCursorAdaptor. java
(fram eworks/base/core/java/android/d
atabase/BulkCursorToCursorAdaptor.jav
a)
CursorW indow. java
(fram eworks/base/core/java/android/d
atabase/CursorW indow.java)
android_database_CursorW indow. cpp
(fram eworks/base/core/jni/android_da
tabase_CursorW indow.cpp)
CursorW indow. cpp
(fram eworks/base/libs/binder/Cursor
W indow.cpp)
android_database_SQLiteQuery. cpp
(fram eworks/base/core/jni/android_da
tabase_SQLiteQ uery.cpp)
CursorW rapper. java
(fram eworks/base/core/java/android/d
atabase/CursorW rapper.java)
AbstractCursor. java
(fram eworks/base/core/java/android/d
atabase/AbstractCursor.java)
BulkCursorN ative. java
(fram eworks/base/core/java/android/d
atabase/BulkCursorNative.java)
ParcelFileDescriptor. java
(fram eworks/base/core/java/android/o
s/ParcelFileD escriptor.java)
M ediaProvider. java
(packages/providers/M ediaProvider/sr
c/com /android/providers/m edia/M edia
Provider.java)
android_util _Binder. cpp
(fram eworks/base/core/jni/android_u
til _Binder.cpp)
```
