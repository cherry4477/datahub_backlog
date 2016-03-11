# DataHub 代办任务列表

##前端
* 运营页面：包括新增用户、精选编辑、用户级别与会员调整等。
* 删除的数据查看。
* 自动登录功能。自动登录的用户在订购、提现时强制登录。
* 微信分享。
* 微信登录。
* 前端css、js、html的拆分。
* 删除Repo。
* 申请注册。
* **已经完成的需求放这里，标明版本和时间**

* 微信分享 V1.2 2016.03.04
* 申请注册 V1.2 2016.03.04
* List列表模块拆分 V1.2 2016.03.04

##客户端
* 对所发布的tag进行健康检查，并发送给heartbeat 
* 抽象文件操作，以支持插件式文件访问
* 客户端删除Item、Tag的处理 `产品组完善需求，web端已经存在item删除功能。`
* daemon的后端服务化，与df的集成，简化数据托管区，简化数据提供者的操作
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
 **已经完成的需求放这里，标明版本和时间**
* 删除Item
* 删除Tag


##后端
* heartbeat收到daemon的tag健康检查情况后发送msg，每日一次，仅发送错误信息，通知数据提供者 `产品组完善需求`
* heartbeat提供查询接口，仅管理员权限。供repo和transaction查询tag状态。`开发阶段`
* repo返回item和tag的时候，考虑tag健康状态 `产品组完善需求`
* transaction，pull生成accesstoken的时候判断可用性 `刘旭`
* transaction提供一个api接口给daemon在发送成功后调用，并通过它来确认pull量 `刘旭`
* heatbeat的redis持久化到mysql中
* 管理员群发邮件、群发消息给用户。
**已经完成的需求放这里，标明版本和时间**
* 删除Repo的api返回。  



##运营
* datahub上发布的数据补充数据字典说明 `刘亮亮`
 
##创意阶段
* Server API review和整理
* 单元测试的优化和自动的集成测试
* 后台表结构review和整理数据字典文档，数据库初始化和每个阶段的升级文档
* 支持windows客户端
* 客户端支持插入到execl和其他软件中
* 集成外部的api gateway `产品组方案`
* 微信登陆 `需要研究方案`
* 充值、提现、账本金额管理
* 利用api gateway的方式进行api聚合，现在前端js访问api的压力大，导致时延长
 **已经完成的需求放这里，标明版本和时间**
 
* kafka版本升级到0.9 [1.2 20160304]


##产品
* 交易市场需求的讨论。
* 数据资源地图的功能讨论。
* 交易市场交维的后续细节事项。
* 商业模式研究，在线支付模式的执行可行性。
* DH产品竞品分析update。
* DH中文名注册。
* DH商标的修改与确认。
 **已经完成的需求放这里，标明版本和时间**

* 集成外部APIGateway方案讨论。 V1.2 2016.03.04
* 产品发布前的准备材料，包括需求文档、白皮书、操作手册、测试报告、培训文档的准备，并提交给规划部。V1.2 2016.03.05
* 确认Kafka中运营统计数据与需求的匹配度。V1.2 2016.03.04


