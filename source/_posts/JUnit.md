title: JUnit
date: 2016-02-18 23:41:33
tags: 测试
---

## Java语言的单元测试框架

## 它的组成：
* TestRunner(帮助管理测试过程，执行测试，生成测试报告等)
* 测试类
* 测试用例，也叫test case，即测试类里面的各个测试方法
* test suite，可由多个测试类组成，TestRunner的执行单元

## Junit版本及差异：
* JUnit3
> * import junit.framework.*
> * 测试类需要继承自TestCase类
> * 测试方法必须以test开头
> * 使用`setup`和`teardown`来初始化和清理测试环境
* JUnit4
> * import org.junit.*
> * 可以不继承子TestCase类
> * 测试方法前用`@Test`注解，测试方法为`public`，无返回值，没有参数
> * 用`@Before` `@After`取代`setup`和`teardown`，且增加了`@BeforeClass` `@AfterClass` `@Rule`等各种annotation




