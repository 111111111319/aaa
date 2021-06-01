cothroller：放的是界面控制器，主要写每个界面对应的功能，相当于程序的核心，进行调用server接口实现。@Controller  注解，，标识为控制层，用于加在类上。故，@Repository加在DAO层，@Server加在服务层。@RequestMapping("getHome")该方法对应的uri，根据返回的字段找到界面视图



interceptor：拦截器    ，创建拦截器实HandlerInterceptorAdapter，，，

在springmvc的核心配置文件中添加拦截器，设置服务器的语言，从而实现服务器端响应内容。





mapper：Mybatis里面的mapper和xml的语句的映射，是针对SQL构建的，if ，choose， where ， set， foreach， bind，script等元素

pojo：存放实体类，使用pojo类型进行数据绑定

service：服务类，主要功能开发的地方，就是server接口中编写方法，，然后在serviceimpl中实现service接口，并且在return mapper中的方法类实现功能，使用时直接调用service。



