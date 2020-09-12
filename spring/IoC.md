## 一、IoC的发展
   1.什么是IoC
    是一种设计思想，在Java开发中，将你设计好的对象交给容器控制，而不是显示地用代码进行对象的创建。
    把创建和查找依赖对象的控制权交给 IoC 容器，由 IoC 容器进行注入、组合对象。这样对象与对象之间是松耦合、
    便于测试、功能可复用（减少对象的创建和内存消耗），使得程序的整个体系结构可维护性、灵活性、扩展性变高。
## 二、IoC的主要实现策略
    1.使用service locator pattern(服务定位模式) 
        javaEE的一种服务模式，通常使用JNDI获取Java ee组件
    2.使用dependency injection
      （1）Constructor Injection构造器注入
      （2）Parameter Injection 参数注入
      （3）Setter Injection Setter注入
      （4）Interface Injection 接口注入
    3.Contextuailized lookup 上下文依赖查询
      java里的java Beans技术使用通用上下文BeanContext,既可以传输bean，也可以管理bean的层次性
    4.template method design pattern（模板方法设计模式）
      比如Jdbc Template实现
    5.celve模式
### IoC的容器职责
    1.依赖处理
      .. 依赖查找
        主动（名称，类型查找，类型转换处理）
      ..依赖注入
        容器被动
    2.生命周期
      ..容器
      ..托管资源
 ### IoC的主要实现
       javaSE:
          .java Beans
          .java ServiceLoader SPI
          .JNDI(java Naminf And Directory Interface)
       javaEE
          .EJB(依赖查询   3.0后注入)
          .Servlet（）
       开源
          .PicoContainer
          .Google Duice
          .Spring Framework
   
    
### IoC的实现
      
    
    
    
    
    
    
    
