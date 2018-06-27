# 更新日志
### 2018-06-27

**修改功能：**

优化：      
- @blogHeader宏标签数据动态获取      
- 开启websocket的逻辑调优，host从config表中获取    
- 项目readme文档完善并拆分    
- 项目maven版本修改为`2.0.1.Beta`

增加：
- ISSUE和PR的模板    

----

### 2018-06-20

**修改功能：**

优化：  
- 升级Spring Boot至2.0.1版本及其他关联版本升级；  
- 使用Maven Profile管理Spring Boot Profiles，支持动态切换profile；

----

### 2018-06-10

**修改功能：**

新增：    
- markdown版的编辑器、评论框    
- 控制文章的评论框是否显示    
- 修改密码功能    
优化：相关页面进行优化    

----

### 2018-06-05

**修改功能：**

修复： admin用户首页报错的问题    

优化：
1. ROOT用户默认拥有所有权限
2. admin页面改为macro引用的方式
3. 登录界面
4. 日志记录

----

### 2018-05-25

**修改功能：**

1. 修复后台标签等分页失败的问题
2. 修复前台自动申请友链失败的问题
3. 其他一些问题

----

### 2018-05-22

**修改功能：**

1. 完善shiro权限（数据库、页面）。注：需要重新执行下`sys_resources`和`sys_role_resources`两张表的`insert`语句
2. redis配置默认不含密码（鉴于大多数朋友的redis都没有密码做此修改，不过本人 **强烈建议**设置下密码）

----

### 2018-05-18

**修复bug：**

1. web端自动申请友链后不显示的问题
2. config表修改后不能实时刷新的问题
	
**增加功能：**
1. 网站赞赏码
2. 百度推送功能(链接提交到百度站长平台)
	
**修改功能：**
1. 百度api的ak和百度推送的token以及七牛云的配置改为通过config表管理
3. admin模块菜单通过标签实时获取
3. 弹窗工具类js结构调整