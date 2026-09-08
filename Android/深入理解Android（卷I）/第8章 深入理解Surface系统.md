# 第8章 深入理解Surface系统


本章涉及的源代码文件名及位置：

ActivityThread.java（framework/base/core/java/android/app/ActivityThread.java）

Activity.java（framework/base/core/java/android/app/Activity.java）

Instrumentation.java（framework/base/core/java/android/app/Instrumentation.java）

PolicyManager.java（frameworks/policies/base/phone/com/android/internal/policy/impl/PolicyManager.java）

Policy.java（frameworks/policies/base/phone/com/android/internal/policy/impl/Policy.java）

PhoneWindow.java（frameworks/policies/base/phone/com/android/internal/policy/impl/PhoneWindow.java）

Window.java（framework/base/core/java/android/view/Window.java）

WindowManagerImpl（framework/base/core/java/android/view/WindowManagerImpl.java）

ViewRoot.java（framework/base/core/java/android/view/ViewRoot.java）

Surface.java（framework/base/core/java/android/view/Surface.java）

WindowManagerService.java（framework/base/services/java/com/android/server/WindowManagerService.java）

IWindowSession.aidl（framework/base/core/java/android/view/IWindowSession.aidl）

IWindow.aidl（framework/base/core/java/android/view/IWindow.aidl）

SurfaceSession.java（framework/base/core/java/android/view/SurfaceSession.java）

android_view_Surface.cpp（framework/base/core/jni/android_view_Surface.cpp）

framebuer_service.c（system/core/adb/framebuer_service.c）

SurfaceComposerClient.cpp（framework/base/libs/surfaceflinger_client/SurfaceComposerClient.cpp）

SurfaceFlinger.cpp（framework/base/libs/surfaceflinger/SurfaceFlinger.cpp）

ISurfaceComposer.h（framework/base/include/surfaceflinger/ISurfaceComposer.h）

Layer.h（framework/base/include/surfaceflinger/Layer.h）

Layer.cpp（framework/base/libs/surfaceflinger/Layer.cpp）

LayerBase.cpp（framework/base/libs/surfaceflinger/LayerBase.cpp）

Surface.cpp（framework/base/libs/surfaceflinger_client/Surface.cpp）

SharedBuerStack.cpp（framework/base/libs/surfaceflinger_client/SharedBuerStack.cpp）

GraphicBuer.h（framework/base/include/ui/GraphicBuer.h）

GraphicBuer.cpp（framework/base/libs/ui/GraphicBuer.cpp）

GraphicBuerAocator.h（framework/base/include/ui/GraphicBuerAocator.h）

GraphicBuerAocator.cpp（framework/base/libs/ui/GraphicBuerAocator.cpp）

GraphicBuerMapper.cpp（framework/base/libs/ui/GraphicBuerMapper.cpp）

Android_natives.h（framework/base/include/ui/egl/Android_natives.h）

android_native_buer.h（framework/base/include/ui/android_native_buer.h）

native_handle.h（system/core/include/cutils/native_handle.h）

graoc.h（hardware/libhardware/include/hardware/graoc.h）

ISurface.cpp（framework/base/libs/surfaceflinger_client/ISurface.cpp）

DisplayHardware.cpp（framework/base/libs/surfaceflinger/DisplayHardware.cpp）
