# 0.3.1

* 增加指令`#ws帮助` Copyright miao-plugin

# 0.3.0

* 增加指令`#ws关闭连接``#ws打开连接``#ws查看连接`
    *`#ws关闭连接` 不会删除已有连接,同时不进行连接
    *`#ws打开连接` 打开已关闭的连接
    *`#ws查看连接` 查看已有的所有连接名字和状态
    *`#ws添加连接` 添加一个新的连接 
    *`#ws删除连接` 删除一个已有的连接 
    *`#ws重新连接` 强制断开已有的所有连接并重新连接 
* 暂时关闭正向ws连接

# 0.2.0

* 增加通知事件上报,默认关闭,需要可自行使用`#ws设置`进行开启
    * 增加以下通知事件
    * 群管理员变动,群成员减少,群成员增加
    * 群禁言,好友添加,群消息撤回
    * 好友消息撤回,群内戳一戳

# 0.1.0

* 增加指令`#ws版本``#ws设置` Copyright miao-plugin

# 0.0.5

* 增加指令`#ws重新连接`
* 增加首次连接时将结果通知主人设置

# 0.0.4

* 增加断线自动重新连接
* 增加断线和重连通知主人设置

# 0.0.3

* 适配gsuid群聊导出抽卡记录和私聊发送抽卡记录json文件

# 0.0.2

* 增加指令`#ws添加连接``#ws删除连接`

# 0.0.1

* 初始化插件
* 可连接支持onebotv11协议的bot以及gsuid_core
* 适配了部分onebot api
  