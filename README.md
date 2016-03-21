# DataHub 代办任务列表

##前端
* 运营页面：包括新增用户、精选编辑、用户级别与会员调整等。
* 删除的数据查看。
* 自动登录功能。自动登录的用户在订购、提现时强制登录。
* 微信分享。
* 微信登录。
* 前端css、js、html的拆分。
* 删除Repo。
* API页面集成。
* 重置密码增加链接24小时失效判断流程。
  ——————————————————————————————————  
* **已经完成的需求放这里，标明版本和时间**
* 微信分享 【V1.2 2016.03.04】
* 申请注册 【V1.2 2016.03.04】
* List列表模块拆分 【V1.2 2016.03.04】
* 数据精选页 【v1.3 2016.03.11】
* 搜索结果页 【v1.3 2016.03.11】
* Repo详情页 【v1.3 2016.03.11】
* 数据拥有方详情 【v1.3 2016.03.11】
* 评论模块 【v1.3 2016.03.11】
* 模态框组件提取 【v1.3 2016.03.11】
* 登录模块 【v1.3 2016.03.11】
* URL路径调整 【v1.3 2016.03.11】
* 错误页面捕获 【v1.3 2016.03.11】  
* 申请注册。 【v1.3 2016.03.11】  
* item详情页的整合，包括了整个订购流程 【v1.4 2016.03.18】  
* repo的白名单与协作者 【v1.4 2016.03.18】 
* repo列表 【v1.4 2016.03.18】 
* 删除repo的功能模块 【v1.4 2016.03.18】 
* 自动化文件编写 【v1.4 2016.03.18】 
* 忘记密码 【v1.4 2016.03.18】
* 消息自动接收 【v1.4 2016.03.18】

##客户端
* 抽象文件操作，以支持插件式文件访问
* 客户端删除Item、Tag的处理 `产品组完善需求，web端已经存在item删除功能。`
* daemon的后端服务化，与df的集成，简化数据托管区，简化数据提供者的操作
* 数据提供方在pull完成后调用transaction提供的接口告知 `有前置任务`
* 代码走读缺陷修改
* entrypoint优化，通过隧道实现
* 客户端证书、加密传输。
* PULL的三方认证方案。
* 命令自动联想
* 批量发布tag,通过tag名或者符合某种名称规则的tag
* 批量pull tag，在一个item下可直接通过tag名下载多个，或者满足某种规则的tag名下载多个，或者某个item下全部tag。
* 自动pull tag，通过jobs实现
* pub后保存配置数据到Datahub及恢复处理
* 自动升级
* 支持扩展dp类型，hdfs。
* R Rython Excle 客户端。
* Daemon对Client端的认证方式。
* pub item时增加数据类型参数。
* 修改启动sudo stop命令的说明，为启、停 daemon的命令。非CLI。
* sqlite3 数据健康检查。 
* heatbeat的redis持久化到mysql中
———————————————————————————————————  
 **已经完成的需求放这里，标明版本和时间**
* 删除Item 【V1.2 2016.03.04】
* 删除Tag 【V1.2 2016.03.04】
* 对所发布的tag进行健康检查，并发送给heartbeat 【v1.3 2016.03.11】
* 批量删除tag，同一个item下的tag。【v1.3 2016.03.11】
* subs 命令将item在线状态、tag健康状态体现出来。【v1.4 2016.03.18】
* subs repo/item：tag 的逻辑调整，需要先判断用户是否有订购repo/item,再判断tag的存在性。【v1.4 2016.03.18】
* help 命令的规范化。【v1.4 2016.03.18】




##后端
* heartbeat收到daemon的tag健康检查情况后发送msg，每日一次，仅发送错误信息，通知数据提供者 `产品组完善需求`
* repo返回item和tag的时候，考虑tag健康状态 `产品组完善需求，WEB页面不错调整，建议Client端做subs repo/item 时候带出item状态、tag状态`（此功能暂不需要）
* transaction提供一个api接口给daemon在发送成功后调用，并通过它来确认pull量 `刘旭`
* 管理员群发邮件、群发消息给用户。
* 增加根据nickname 查询 loginname的接口。 郭立强
* 投诉功能。
* 订单完成前产生的投诉导致退款。
* 邮箱链接24小时失效判断。 刘雪莹
* 与api网关，api网关取订单，且置订单已经取走的状态。
* 与api网关，置订单的pull量，每天一次。
* 与api网关，给每日的详单流水。用户单点登录过去查看。
* 与api网关合作，提供用户登录认证功能给api网关。
——————————————————————————————————  
**已经完成的需求放这里，标明版本和时间**
* 删除Item，tag。   【1.1 20160304】
* 删除Repo的api返回。  【1.2 20160309】
* 订单统计数据。  【1.2 20160309】
* transaction，pull生成accesstoken的时候判断可用性 【1.2 20160309】
* heartbeat提供查询接口，供repo和transaction查询tag状态。【v1.3 2016.03.11】
* 搜索内容为空时按照Rank值返回。“为您找到相关结果0个，推荐热门数据如下：”【v1.4 2016.03.18】


##运营
* datahub上发布的数据补充数据字典说明 。
* 个推的数据，接到datahub上。
* 长沙位置数据，接到datahub上。  
——————————————————————————————————  
**已经完成的需求放这里，标明版本和时间**
 * datahub上发布的数据补充数据字典说明 【1.3 20160311】
* 个推的数据（广州），接到datahub上。【1.3 20160311】
* 长沙位置数据，接到datahub上。【1.3 20160311】
 
 
 
##创意阶段
* Server API review和整理
* 单元测试的优化和自动的集成测试
* 后台表结构review和整理数据字典文档，数据库初始化和每个阶段的升级文档
* 支持windows客户端
* 客户端支持插入到execl和其他软件中
* 集成外部的api gateway `产品组方案`* 
* 微信登陆 `需要研究方案`
* 充值、提现、账本金额管理
* 利用api gateway的方式进行api聚合，现在前端js访问api的压力大，导致时延长  
———————————————————————————————————  
 **已经完成的需求放这里，标明版本和时间**
 
* kafka版本升级到0.9 【1.2 20160304】


##产品
* 交易市场交维的后续细节事项。
* 商业模式研究，在线支付模式的执行可行性。
* DH产品竞品分析update。
* DH商标的修改。
* 交易市场it系统原型。
* 交易市场系统的可用性、历史使用情况、历史数据。
* client端集成到一体机、自助分析工具中。
* 白皮书完善。增加开源具体链接、传输过程保护等描述。
———————————————————————————————————  
 **已经完成的需求放这里，标明版本和时间**
* 集成外部APIGateway方案讨论。 【V1.2 2016.03.04】
* 产品发布前的准备材料，包括需求文档、白皮书、操作手册、测试报告、培训文档的准备，并提交给规划部。【V1.2 2016.03.05】
* *增加订单累统计数据需求。【V1.2 2016.03.04】
* 确认Kafka中运营统计数据与需求的匹配度。【V1.2 2016.03.04】
* R、Rython熟悉。叶鹏介绍。【1.3 20160311】
* api集成需求设计。【v1.4 2016.03.18】
* 数据地图需求设计。指定公司内部账号可以看见。包括已经发布到datahub上数据内容的展示、协议框架类的数据的编辑。【v1.4 2016.03.18】
* 需求信息发布、数据资源信息发布。指定公司内部账号可以看见。 【v1.4 2016.03.18】
* 文案完善。修改文案，在前端重构时完成。【v1.4 2016.03.18】
* 原型完善。修改repo、item 原型配套文案重新做。 【v1.4 2016.03.18】
