# HightAndroid
Android开发艺术探索


第一章：activity的生命周期和启动模式
  so easy
  
第二章：IPC机制（Inter-Process Communication 进程间的通信）

  2.1 进程与线程是包含于被包含关系
  2.2 多进程运行机制：
  每个进程都分配一个独立的虚拟机，不同的虚拟机在内存分配上有不同的地址空间，导致不同虚拟机中访问同一个类对象会产生多份副本。
  2.3 Serializable和Parcelable区别:
  Serializable是java的序列化借口，Parcelable是Android的序列化方式。Parcelable主要用在内存序列化上，Serialazable对于用在将对象序列化存储设备中或者将对象序列化后通过网络传输。
  
    
