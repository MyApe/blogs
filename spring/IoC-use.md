## spring IoC查找
    . 根据bean名称查找
        实时查找
        延迟查找
        
    . 根据bean类型查找
       单个对象
       集合对象
     . 根据id和name复核查询
     .根据java注解查询
     

## spring IoC依赖注入
    . 根据bean名称注入
    . 根据类型注入
        单个bean对象
        集合bean对象
     . 注入容器内建对象
     . 注入非bean对象
     . 注入类型
        实时注入
        延迟注入
## spring IoC依赖来源
      . 自定义bean
      . 容器内部的bean对象
      . 容器内建依赖
## spring IoC配置元信息
      . bean定义配置
        基于xml
        基于property
        基于注解
        基于api
      . ioc容器配置
        xml文件
        注解
        api
      . 外部配置
## 谁才是ioc容器BeanFactory  or  ApplicationContext
    BeanFactory 是底层的ioc容器
    ApplicationContext组合了beanfactory 是其超集。
    在其基础上 提供了更好的特性
      
## ApplicationContext除了IoC还提供
    . 面向切面（AOP）
    . 配置元信息
    . 资源管理
    . 事件
    . 国际化
    . 注解
    . Environment抽象



