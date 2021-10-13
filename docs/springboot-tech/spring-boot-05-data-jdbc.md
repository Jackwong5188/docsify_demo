# spring-boot-05-data-jdbc



## 一、springboot

Spring Boot是由Pivotal团队提供的全新[框架](https://baike.baidu.com/item/%E6%A1%86%E6%9E%B6/1212667)，其设计目的是用来[简化](https://baike.baidu.com/item/%E7%AE%80%E5%8C%96/3374416)新[Spring](https://baike.baidu.com/item/Spring/85061)应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置。通过这种方式，Spring Boot致力于在蓬勃发展的快速应用开发领域(rapid application development)成为领导者。

```
@EnableAsync
@EnableRetry
@EnableScheduling
@EnableSwagger2
@SpringBootApplication
public class IntegrationModuleApplication {
    public static void main(String[] args) {
        SpringApplication.run(IntegrationModuleApplication.class, args);
    }
}
```



## 二、data

data，英文单词，名词，作名词时意为“数据（datum的复数）；资料，人名；(日)驮太 (姓)；(印、葡)达塔”。



## 三、jdbc

Java数据库连接，（Java Database Connectivity，简称JDBC）是[Java语言](https://baike.baidu.com/item/Java%E8%AF%AD%E8%A8%80)中用来规范客户端程序如何来访问数据库的[应用程序接口](https://baike.baidu.com/item/%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E6%8E%A5%E5%8F%A3/10418844)，提供了诸如查询和更新数据库中数据的方法。JDBC也是Sun Microsystems的商标。我们通常说的JDBC是面向关系型数据库的。