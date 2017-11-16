# Spring Boot 规范

#### 项目目录

* project
  * src/main/java
    * com.xxx.yyy.zzz
      * controller
      * service
        * impl
      * dao
      * dto
      * vo
      * exception
      * Application.java
  * pom.xml

#### Controller

必须加的三个注解

`@RestController`

`@RequestMapping`

`@Validated`

#### Validation

| 字段类型 | 校验名称 |
| :--- | :--- |
| Integer |  |
| Double |  |
| Float |  |
| String |  |
| Boolean |  |
| LocalDate/LocalTime/LocalDateTime |  |
| Enum |  |
| Object |  |

BindingResult处理：

