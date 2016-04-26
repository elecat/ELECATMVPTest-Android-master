# ELECATMVPTest-Android-master

##项目简介
这是我对MVP架构进行学习与总结的小项目。

##首先需要了解

####1、为什么需要MVP架构？
避免创建神类。如果一个类需要花费时间从其他类中通过Get()和Set()检索数据（也就是说，需要深入业务并且告诉它们如何去做），所以是否应该把这些功能函数更好的组织到其它类而不是上帝类中。
避免Activity类往往会越来越大。这是因为，在Android中，允许View和其它线程共存于Activity内。其实最大的问题莫过于在Activity中同时存在业务逻辑和UI逻辑。这会增加测试和维护的成本。

####2、什么是MVP架构？
MVP代表Model，View和Presenter。






