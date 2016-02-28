# DataHub 代办任务列表

##前端
* 运营页面：包括新增用户、精选编辑、用户级别与会员调整等。
* 删除的数据查看。
* 自动登录功能。自动登录的用户在订购时强制登录。
* 微信分享。
* 微信登录。
* 前端css、js、html的拆分。

##客户端
* 对所发布的tag进行健康检查，并发送给heartbeat 
* 抽象文件操作，以支持插件式文件访问
* 客户端删除Item、Tag的处理 `产品组完善需求，web端已经存在item删除功能。`
* 数据提供方在pull完成后调用transaction提供的接口告知 `有前置任务`
* 代码走读缺陷修改
* entrypoint优化，通过隧道实现
* 客户端证书、加密传输。
* PULL的三方认证方案。
* 命令自动联想
* 批量发布tag
* 自动pull tag，通过jobs实现
* pub后保存配置数据到Datahub及恢复处理
* 自动升级
***
* **已经完成的需求放这里，标明版本和时间**

##后端
* heartbeat收到daemon的tag健康检查情况后发送msg，每日一次，仅发送错误信息，通知数据提供者 `产品组完善需求`
* heartbeat提供查询接口，仅管理员权限。供repo和transaction查询tag状态。`开发阶段`
* repo返回item和tag的时候，考虑tag健康状态 `产品组完善需求`
* transaction，pull生成accesstoken的时候判断可用性 `刘旭`
* transaction提供一个api接口给daemon在发送成功后调用，并通过它来确认pull量 `刘旭`
* heatbeat的redis持久化到mysql中

##运营
* datahub上发布的数据补充数据字典说明 `刘亮亮`
 
##创意阶段
* Server API review和整理
* 单元测试的优化和自动的集成测试
* kafka版本升级到0.9
* 后台表结构review和整理数据字典文档，数据库初始化和每个阶段的升级文档
* 支持windows客户端
* 客户端支持插入到execl和其他软件中
* 集成外部的api gateway `产品组方案`
* 微信登陆 `需要研究方案`
* 充值、提现、账本金额管理
* 利用api gateway的方式进行api聚合，现在前端js访问api的压力大，导致时延长

