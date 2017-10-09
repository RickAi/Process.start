```
.
├── README.md
└── src
    ├── dalvik
    │   └── src
    │       └── main
    │           └── java
    │               └── dalvik
    │                   └── system
    │                       └── ZygoteHooks.java
    ├── frameworks
    │   └── base
    │       ├── cmds
    │       │   └── app_process
    │       │       └── app_main.cpp
    │       ├── core
    │       │   ├── java
    │       │   │   ├── android
    │       │   │   │   ├── app
    │       │   │   │   │   └── ActivityThread.java
    │       │   │   │   └── os
    │       │   │   │       └── Process.java
    │       │   │   └── com
    │       │   │       └── android
    │       │   │           └── internal
    │       │   │               └── os
    │       │   │                   ├── RuntimeInit.java
    │       │   │                   ├── Zygote.java
    │       │   │                   ├── ZygoteConnection.java
    │       │   │                   └── ZygoteInit.java
    │       │   └── jni
    │       │       ├── AndroidRuntime.cpp
    │       │       └── android_util_Process.cpp
    │       ├── jni
    │       │   └── com_android_internal_os_Zygote.cpp
    │       ├── libs
    │       │   └── binder
    │       │       └── ProcessState.cpp
    │       └── services
    │           └── java
    │               └── com
    │                   └── android
    │                       └── server
    │                           └── am
    │                               └── ActivityManagerService.java
    ├── libart
    │   └── src
    │       └── main
    │           └── java
    │               ├── dalvik
    │               │   └── system
    │               │       └── VMRuntime.java
    │               └── java
    │                   └── lang
    │                       └── Daemons.java
    ├── platform_bionic
    │   └── libc
    │       └── bionic
    │           ├── fork.cpp
    │           └── pthread_atfork.cpp
    └── runtime
        ├── native
        │   └── dalvik_system_ZygoteHooks.cc
        └── runtime.cc
```