# Unity 环境下实现的消息中心模块
### 功能及特点
* 消息类型通过枚举定义。
* 支持同步(SendMessage)和异步(PostMessage)发送消息。
* 回调函数注册能够自动校验参数类型合法性。
* 能够保证回调函数不被重复注册。
* 消息数据通过参数传递，无需为每个消息定义消息体类型。
* 支持移除指定对象的所有回调。