# 第4章 深入理解zygote


本章涉及的源代码文件名及位置下面是本章分析的源码文件名及其位置。

App_main.cpp（framework/base/cmds/app_process/App_main.cpp）

AndroidRuntime.h（framework/base/include/android_runtime/AndroidRuntime.h）

android_debug_JNITest.cpp（framework/base/core/jni/android_debug_JNITest.cpp）

ZygoteInit.java（framework/base/core/java/com/android/internal/os/ZygoteInit.java）

dalvik_system_Zygote.c（dalvik/vm/native/dalvik_system_Zygote.c）

RuntimeInit.java（framework/base/core/java/com/android/internal/os/RuntimeInit.java）

SystemServer.java（framework/base/services/java/com/android/server/SystemServer.java）

com_android_server_SystemServer.cpp（framework/base/services/jni/com_android_server_SystemServer.cpp）

system_init.cpp（framework/base/cmds/system_server/library/system_init.cpp）

Watchdog.java（framework/base/services/java/com/android/server/Watchdog.java）

ActivityManagerService.java（framework/base/services/java/com/android/server/am/ActivityManagerService.java）

Process.java（framework/base/core/java/android/os/Process.java）

ZygoteConnection.java（framework/base/core/java/com/android/internal/os/ZygoteConnection.java）
