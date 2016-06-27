# DataHub 待办任务列表

##前端
* 运营页面：
* 删除的数据查看。
* 自动登录功能。自动登录的用户在订购、提现时强制登录。
* 微信分享。
* 微信登录。
* 群发邮件【V1.8,V1.9】
* 搜索引擎功能引用【6.12-6.18规划具体功能】
* Client端工具-Windows环境下客户端下载安装（规划sdk下载功能）【6.12-6.18规划具体功能】
* BD互链-滚动展示(放到前端改版中)
* 合作伙伴运营实现可编辑（放到前端改版中）
* 首页改版 
* 前端存在的问题。注册功能没有放到重构后的web 文件夹中。*
* 前端的重构没有将js作为公用模块提出来，很麻烦。*
* 用户用搜狗浏览器报导航栏自动移位(20160607用户提出)
* API接口信息可配置，增加接口调用测试功能【6.12-6.18规划具体功能】
* web cli的开发【v2.1】 
* DH跳转到WEB CLI【v2.1,王迪】
* 会员级别调整-遗留会员降级

### 运营功能
* 会员级别调整、认证审核功能，广州交易所、DH的运营页面增加用户渠道来源参数判断。即广州交易所仅能查看调整广州用户、认证广州用户；DH仅能查看调整DH用户、认证DH用户。【V2.2】
* api在线调试【V2.2】
* 工具页面增加OS环境下客户端安装，SDK下载安装【V2.2】
———————————————————————————————————————— 
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
* 前端css、js、html的拆分。【v1.7 2016.04.8】
* 精选编辑页面【v1.9 2016.04.29】
* 在线的数据地图。【已经发布的公开数据、私有数据 v1.9 2016.04.29】
* 交易所首页 【v1.9 2016.04.29】
* 手机端页面访问，token参数补充。【v1.8, 2016.05.13】
* 平台介绍，关于我们调整到首页【V1.9, 2016.05.13】
* 帮助改为下拉菜单（客户端命令介绍，用户入驻，数据发布，数据获取）【V2.0, 2016.05.13】
* 增加企业互链【V2.0, 2016.05.13】
* 广州交易所新增注册等页面【V2.0, 2016.05.13】
* 广州交易所页面静态页面的开发（首页内链接的静态页面，半周时间）【V2.0, 2016.05.13】
* 关于我们、平台介绍调整到首页后按新切图开发页面【V2.0 2016.05.16】
* 用户激活【V2.0, 2016.05.20】
* 运营代办认证【V2.0, 2016.05.20】
* 个人、企业认证 【V2.0，2016.05.27】
* 会员自认证，校验功能。【v2.1，2016.06.17】
* 认证审核不通过，跳转到重新录入认证信息页面（需求当时有遗漏，沟通一下） 【v2.1,2016.06.17】
* 管理员代录入，校验功能。【v2.1，2016.06.17】
* 会员级别调整【v2.1 2016.06.17】
* 运营认证审核。【2.1】
* 精选图片运营实现可编辑【v2.1】 

##客户端
* 抽象文件操作，以支持插件式文件访问
* daemon的后端服务化，与df的集成，简化数据托管区，简化数据提供者的操作
* 数据提供方在pull完成后调用transaction提供的接口告知【1.8】 `有前置任务`
* 代码走读缺陷修改
* entrypoint优化，通过隧道实现
* 客户端证书、加密传输。
* PULL的三方认证方案。
* 命令自动联想
* 批量发布tag,通过tag名或者符合某种名称规则的tag
* 批量pull tag，在一个item下可直接通过tag名下载多个，或者满足某种规则的tag名下载多个，或者某个item下全部tag。
* pub后保存配置数据到Datahub及恢复处理
* 自动升级
* R Rython Excle 客户端。
* Daemon对Client端的认证方式。
* pub item时增加数据类型参数。
* heatbeat的redis持久化到mysql中。
* dp dpname命令中补充展示每个tag的comment（comment支持中文）【v2.0】。
* 健康检查邮件，需要完善。【v2.2】
* web cli对应需要调整的功能。包括用户数据池全量文件扫描；sqlit中的信息需与本地文件保持一致、服务端的信息亦需要一致；新建item，只能在dp下一级目录新建；本地文件未发布过的，需要记录。【v2.1】
* web -cli  （备注：hearbeat传递给server的信息中增加托管区daemon的访问地址。）
* cli help命令输出标准化。
* datahub ep设置ip、port之后的输出文案需要调整。提示用户此时ep已经设置，可以通过datahub ep命令查看设置是否有效。
* os操作系统下的客户端。
* window操作系统下的客户端版本是否同步了linux的版本。
* 数据健康检查的功能，需要连同邮件一起发出来。
* data hub job 需要把正在下载的job作为默认输出，hub job —a输出全部。
* 用户pull到本地的文件，需要自动帮用户补充元数据文件、样例文件。
* 发布DataItem的工作调整到页面上，那么daemon的工作需要调整。改为在某个item下第一次发布tag时需要指定存储dp、路径。（此时的UE需要修改，包括页面的、webcli的需要对应的调整）（待item元数据样式设计完成后）。
———————————————————————————————————  
 **已经完成的需求放这里，标明版本和时间**
* 删除Item 【V1.2 2016.03.04】
* 删除Tag 【V1.2 2016.03.04】
* 对所发布的tag进行健康检查，并发送给heartbeat 【v1.3 2016.03.11】
* 批量删除tag，同一个item下的tag。【v1.3 2016.03.11】
* 自动pull tag，通过jobs实现。【v1.3 2016.03.11】
* subs 命令将item在线状态、tag健康状态体现出来。【v1.4 2016.03.18】
* subs repo/item：tag 的逻辑调整，需要先判断用户是否有订购repo/item判断tag的存在性。【v1.4 2016.03.18】
* help 命令的规范化。【v1.4 2016.03.18】
* sqlite3 数据健康检查。[V1.5 2016.03.26] 
* 客户端删除Item、Tag的处理 [V1.5 2016.03.26]
* 支持扩展dp类型，hdfs。【v1.6 2016.04.8】
* 未登录前输出标准化。【v1.6 2016.04.8】
* window客户端与linux客户端版本同步。【v1.6 2016.04.8】
* 健康检查邮件内容。【v1.6 2016.04.8】



##后端
* transaction提供一个api接口给daemon在发送成功后调用，并通过它来确认pull量 `刘旭`【1.8】
* 投诉功能。
* 与api网关，api网关取订单，且置订单已经取走的状态。【1.8将接口定义出来】
* 与api网关，置订单的pull量，每天一次。
* 与api网关，给每日的详单流水。用户单点登录过去查看。
* 增加写订单取走状态、订单用量的接口。【1.8将接口定义】
* api网关（修改接口创建订单，统一接口调用方式，修改现有接口； 同步到信息到本地，更新订单配额控制，限制，按订单需求控制流量； 按月消耗量进行收费；）【V2.0】
* servicebroker：（MySQL接口开发，作为可配置，支持sqlite3和MySQL两种模式；web客户端开发，调用daemon的api； datahub daemon与web客户端之间改为http协议通信，支持用户名密码Basic认证。provision时生成用户名密码；日志输出；
使用s3和hdfs类型datapool时，在provision时，传参数。）【V2.0】
api gateway（陈一庚负责的版本）

——————————————————————————————————  
**已经完成的需求放这里，标明版本和时间**  

* 删除Item，tag。   【1.1 20160304】  
* 删除Repo的api返回。  【1.2 20160309】
* 订单统计数据。  【1.2 20160309】
* transaction，pull生成accesstoken的时候判断可用性 【1.2 20160309】
* heartbeat提供查询接口，供repo和transaction查询tag状态。【v1.3 2016.03.11】
* 搜索内容为空时按照Rank值返回。“为您找到相关结果0个，推荐热门数据如下：”【v1.4 2016.03.18】
* heartbeat收到daemon的tag健康检查情况后发送msg，每日一次，仅发送错误信息，通知数据提供者【v1.6 2016.03.29】
* repo返回item和tag的时候，考虑tag健康状态 ，Wweb serverEB页面不错调整，建议Client端做subs repo/item 时候带出item状态、tag状态`tag健康检查情况后发送msg，每日一次，仅发送错误信息，通知数据提供者【v1.6 2016.03.29】
* 邮箱链接24小时失效判断。 【v1.6 2016.03.29】
* 管理员群发邮件、群发消息给用户。【v1.6 2016.03.29】
* 增加根据nickname 查询 loginname的接口。【v1.6 2016.03.29】
* 订单号修改为11位。【v1.7 2016.04.8】
* 协作者逻辑调整，开放repo有协作者。【v1.7 2016.04.8】
* 删除协作者逻辑调整，有发布协作item时无法删除。【v1.7 2016.04.8】
* 命令帮助文档修改 对于client端启停的描述。【v1.7 2016.04.8】
* 位置信息api完成和datahub用户打通功能【v2.0 2016.05.20】
* 42条免费API接入DH，已完成DH打通功能【V2.0 2016.06.08】

##运营
* datahub上发布的数据补充数据字典说明 。
* keyword修订。
* 首页增加datahub文字。
* 与外部网站相互链接。  

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
* 微信登陆 `需要研究方案`
* 充值、提现、账本金额管理

———————————————————————————————————  
 **已经完成的需求放这里，标明版本和时间**
* kafka版本升级到0.9 【v1.2 20160304】
* 集成外部的api gateway【v2.0 201605】

##产品
* 交易市场交维的后续细节事项。
* 商业模式研究，在线支付模式的执行可行性。
* DH产品竞品分析update。
* DH商标的修改。
* 交易市场it系统原型。
* 交易市场系统的可用性、历史使用情况、历史数据。
* client端集成到一体机、自助分析工具中。
* 信息发布功能的设计。需要先研究一下contentful的api接口。
* 完成信息在datahub上的手动发布。
* 每周Kafka中数据的统计。
* 产品遗留事项：web cli未考虑协作删除事项。因为daemon未做协作发布。
* 手工发布api.
* Client端的工作，无论使用和实现的了解，需要深入。
* Python、R、Java、Go SDK api整理。【6.12-6.17 龚】
* 与可视化工具的合作方案。  【6.12-6.17 龚】
* 与网易有数的合作方案。【6.12-6.17 龚】
* DH未来功能规划，讨论。【6.12-6.17 龚】
* DH首页改版设计。
* cms接口整理和输出。形成发布的需求文档。包括发布者增删改（管理员具备删改权限），其它人浏览。
* 运营功能：配额调整功能。     
* 操作手册，增加ep命令中对端口的说明。对于hdfs、s3的发布、下载说明。增加创建hdfs、s dp的操作说明。【6.12-6.17 吴】
* 认证审核不通过，跳转到重新录入认证信息页面（需求当时有遗漏），修订需求文档，原型增加审核不通过跳转判断。  
* 运营精选功能增加图片编辑功能，需要原型补充。【6.12-6.17 吴】
* API用户体验优化，功能设计。【6.12-6.17 吴】
* 工具页面，整体规划，增加sdk、unix、window等工具下载和获取。【6.12-6.17 吴】
* Openshift上dh的功能验证。【6.12-6.17 全体】
* DACP联调测试。【6.12-6.17 全体】
* API测试。【6.12-6.17 全体】
* client端命令输出标准化。命令语法、命令用途、命令举例、命令参数说明。参考oc命令的输出。
输入oc get --help
输出 Usage:
  	oc get [(-o|--output=)json|yaml|wide|go-template=...|	go-template-file=...|jsonpath=...|jsonpath-file=...] 	(TYPE [NAME | -l label] | TYPE/NAME ...) [flags] 	[options]

Examples:  

 	 # List all pods in ps output format.
  	$ oc get pods  
  	

  	# List a single replication controller with specified ID in ps output format.
  	$ oc get rc redis

  	# List all pods and show more details about them.
  	$ oc get -o wide pods

  	# List a single pod in JSON output format.
  	$ oc get -o json pod redis-pod

  	# Return only the status value of the specified pod.
  	$ oc get -o template pod redis-pod --template={{.currentState.status}}

Options:  

   	--all-namespaces=false: If present, list the 	requested object(s) across all namespaces. Namespace in current context is ignored even if specified with --namespace.  
   	
      --export=false: If true, use 'export' for the resources.  Exported resources are stripped of cluster-specific information.  
      
  	-f, --filename=[]: Filename, directory, or URL to a 	file identifying the resource to get from a server.  
  	
 	 -L, --label-columns=[]: Accepts a comma separated 	list of labels that are going to be presented as 	columns. Names are case-sensitive. You can also use multiple flag statements like -L label1 -L label2...
      --no-headers=false: When using the default output, don't print headers.  
      
 	 -o, --output='': Output format. One of: json|yaml|wide|name|go-template=...|go-template-file=...|jsonpath=...|jsonpath-file=... See golang template [http://golang.org/pkg/text/template/#pkg-overview] and jsonpath template [http://releases.k8s.io/release-1.2/docs/user-guide/jsonpath.md].
      --output-version='': Output the formatted object with the given group version (for ex: 'extensions/v1beta1').  
      
	  -l, --selector='': Selector (label query) to filter on  
	  
 	 -a, --show-all=true: When printing, show all resources (false means hide terminated pods.)
      --show-labels=false: When printing, show all labels as the last column (default hide labels column)
      --sort-by='': If non-empty, sort list types using this field specification.  The field specification is expressed as a JSONPath expression (e.g. '{.metadata.name}'). The field in the API resource specified by this JSONPath expression must be an integer or a string.  
      
  	-t, --template='': Template string or path to template file to use when -o=go-template, -o=go-template-file. The template format is golang templates [http://golang.org/pkg/text/template/#pkg-overview].  
  	
  	-w, --watch=false: After listing/getting the requested object, watch for changes.
      --watch-only=false: Watch for changes to the requested object(s), without listing/getting first.
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
* 白皮书完善。增加开源具体链接、传输过程保护等描述。[V1.5 2016.03.26]
* 弹窗归一化调整。[V1.5 2016.03.26]
* 网站文案归一化调整。[V1.5 2016.03.26]
* Cliet端未登录前命令行提示的归一化整理。[V1.6 2016.03.29]
* 增加了工具中的window下载功能设计。【v1.7 2016.04.8】
* 交易市场原型，登录、认证功能。【v1.7 2016.04.8】
* 广州交易市场首页ui。【1.8 】
* window 客户端、s3/hdfs文件抽象 cli测试。【v1.7 2016.04.8】
* DataHub开源资料整理(中关村大数据产业联盟介绍,命令介绍,server端api接口编写格式标准化) 【2016.05.06】
* 首页帮助调整展示内容为：客户端命令介绍，用户入驻，数据发布，数据获取。【2016.05.06】
* DataHub开源资料整理-Client端命令介绍更新【V2.0, 2016.05.20】
* 复用认证及认证审核页面原型【V2.0, 2016.05.20】
* WEB CLI原型修改 
  文件下载时：
  1、设置DataItem的存储路径，增加提示信息(DataItem的存储目录需为DP的下一级目录。）
  在提交时后端判断是否为DP的下一级别目录，若不是“目录无效”，停留在当页。
  2、 目标文件名称，存储路径均为必选项，失去焦点时须有提示。
  3、说明：从WEB跳转到CLI，若自动登陆不成功，则跳转到登陆界面，登陆成功后跳转到下载队列页面。
  4、有疑问的地方，若为本地文件，DataItem可以选择目录。若为HDFS、S3，需手动输入地址。“此处输入的信息需要与伟明确认一下。”
  新建数据池时：
  1、输入参数均为必选项，须有标示，输入错误，须有提示。
  页头：
  新增用户身份，未登录时显示“未登录”，登录后显示“用户登录名”
* 个人、企业认证-需求文档更新

##数据交易市场
* 哈尔滨首页设计---首页UI设计
* 武汉首页交互---登录前页面，登录后首页的内容和交互
* 讨论需求发布(三个交易市场)---UI设计需求列表页和需求详情页、开发
* 新闻资讯发布---UI设计新闻、资讯列表页和详情页、开发
* 运营页面三个数据交易市场需要区分

————————————————————————————————————————
* 广州交易市场首页ui 【2016.04.13】
* 广州交易市场首页修改 【2016.04.22】
* 广州首页（静态页面）【2016.04.27】
* 广州首页交互和静态内容、集成DataHub功能【2016.05.13】
* 广州会员自注册激活、会员自注册激活【2016.05.20】
* 广州新增API分类，增加API列表接口，产品/方案列表页，产品/方案详情页【2016.06.05】
* 广州部署两套：京东云部署地址http://gzproduct-gzweb-product.app.dataos.io 亚马逊部署地址http://gzweb-harbor.app.asiainfodata.com【2016.06.05】
* 
* 武汉数据交易市场原有系统割接维护 【2016.05.18】
* 
* 哈尔滨数据交易市场原有系统割接维护 【2016.05.18】
