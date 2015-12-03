# spring源码

---
## BeanFactory
beanfactory 是一个提供了容器基本功能的接口
具有三个直接继承的接口
1.	AutowireCapableBeanFactory 这个接口是使容器具备了自动装配的功能，可以用来装配不是spring 管理的bean
2.	ListableBeanFactory 这个接口具备了可以遍历的功能
3.	HierarchicalBeanFactory 使容器具备了层级关系 
	1.	getParentBeanFactory
	2.	containsLocalBean
4.	ConfigurableBeanFactory 很多容器的父接口，继承这个接口可以增加更多的配置
5.	ConfigurableListableBeanFactory 继承 ListableBeanFactory, AutowireCapableBeanFactory, ConfigurableBeanFactory 三个接口 添加了配置项
6.	DefaultSingletonBeanRegistry

## alias
6.	AliasRegistry 别名
7.	BeanDefinitionRegistry 提供了保存BeanDefinition别名的功能
8.	SimpleAliasRegistry 单纯的实现了AliasRegistry
9.	

## resource
1.	

## SingletonBeanRegistry
1. SingletonBeanRegistry 单例的bean的管理
2. DefaultSingletonBeanRegistry 默认管理单例bean的事例 以及别名

## factoryBean 容器里事例的bean的工厂


