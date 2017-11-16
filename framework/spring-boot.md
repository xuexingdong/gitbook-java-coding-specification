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

validation所校验的对象，通常情况下是包装类，以下情况除外

* 表示分页的页数时
* 字段有默认值时

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

