#### 公众号模板内容 可以根据自己的需要变更内容
```text
你叫{{friendName.DATA}}
今年{{howOld.DATA}}
距离下一次生日{{nextBirthday.DATA}}天
具体我们的下一次纪念日{{nextMemorialDay.DATA}}天
现在在{{province.DATA}}{{city.DATA}}
当前天气{{weather.DATA}}
当前气温{{temperature.DATA}}
风力描述{{winddirection.DATA}}
风力级别{{windpower.DATA}}
空气湿度{{windpower.DATA}}
{{author.DATA}}
{{origin.DATA}}
{{content.DATA}}
```
其中
```text
{{author.DATA}}
{{origin.DATA}}
{{content.DATA}}
```
是古诗的变量，如果`Bootstrap`中配置未开启随机古诗 那么这三个就是不要的


#### 核心类介绍

```
Application.java          // 启动类
Bootstrap.java            // 一些启动配置(公众号信息在这里配置)
core/MessageFactory.java  // 创建微信消息对象的代码就在这里面 有需要可以自己修改下变量
```
