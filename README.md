# fed-e-task-03-06

1.  说说 application/json 和 application/x-www-form-urlencoded 二者之间的区别。

    `application/json` 用来告诉服务端消息主体是序列化后的 JSON 字符串

    ```bash
    {"title":"test","sub":[1,2,3]}
    ```

    `application/x-www-form-urlencoded` 告诉服务端提交的数据按照 key1=val1&key2=val2 的方式进行编码，key 和 val 都进行了 URL 转码

    ```bash
    title=test&sub%5B%5D=1&sub%5B%5D=2&sub%5B%5D=3
    ```

2.  说一说在前端这块，角色管理你是如何设计的。

    前端主要控制权限，谈不上设计

3.  @vue/cli 跟 vue-cli 相比，@vue/cli 的优势在哪？

    - 抽离 cli service 层
    - 插件化
    - GUI 界面
    - 快速原型开发
    - 现代模式

4.  详细讲一讲生产环境下前端项目的自动化部署的流程。

    根据具体使用的技术灵活配置

5.  你在开发过程中，遇到过哪些问题，又是怎样解决的？请讲出两点。

    - 看官方文档
    - github issue 查阅相关问题
    - Google

6.  针对新技术，你是如何过渡到项目中？

    - 看官方文档
