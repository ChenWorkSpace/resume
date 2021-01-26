# 简历-陈广平（全栈/服务端）
**手机**:152*****6123&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**邮箱**:chen1494518303@outlook.com
# 关于
## 个人信息
* 陈广平/雄性/1996
* 本科/内蒙古工业大学·数据科学与应用学院·软件工程
* 城市：北京
* 工龄：2019 ~
# 工作经历
## 奇安信集团(2019/07 ~)
### 总工办
* 2019/10-2020/04：奇安信发布系统  
  
  集团对外的制品统一发布系统，分为内部发布界面及对外的下载中心两部分。于可配置的工作流模式上完成文件的归集、本地上行、存储备份、散列白名单、CDN等。目前支持集团各业务线的制品发布及下载管理，是软件制品交付的官方渠道。系统由 Go 语言实现。  
  
  负责系统服务端核心模块之一：**文件上传模块(支持大文件>30G)**，以及产品、版本、文件等模块。  

* 2020/04：聚变平台  
  
    聚变（fusion）平台是集团数字化体系中的一部分，提供研发类数据指标度量及devops流水线实现。  
  
  研发类数据包括代码（VCS）和问题（sonarqube及其它静态分析工具）的各种维度数据，工作量的实时采集分析（静默行为）、代码质量扫描（静默行为），基于组织和项目的代码质量报告、门禁通知等。  
  
  工程数据覆盖集团近4000研发人员，万余代码库，超过20万开发分支，百万次提交行为，代码文本行数超百亿，每日静默分析行为平均4000-5000次。  
      
  平台服务化实现，基于 Go 语言、vue实现，数据承载于 Postgresql。  
  
  负责**从零到一搭建聚变平台服务端/前端**，结合Table、Echarts组件实现**列表数据一键可视化**，配合数据处理插件，实现**声明式数据获取->展示**，质量报表插件化数据展示。
 * 自动化工具：2019/07-至今  
     1. Jira蓝信通知服务  
       
           集团移动化服务组件之一，毫秒级Jira消息事件转发，同时也是代码质量扫描、集团签名系统、发布系统等通用系统蓝信通知接口提供方。  
             
             基于 Java 语言,包括Jira Plugin、MessageServer(SpringBoot)、kafka  
      2. 集团产品BUG流自动化组件  
        
          自动化关联集团Tac系统(销售用产品问题追踪平台),Jira统一BUG流(研发用问题追踪平台)，实现双系统问题状态响应式更新(任一系统问题状态更新，另一系统即实时更新相应问题状态),单向问题创建处理。  
       两个系统分别面向集团客户和产品开发部门导致数据维度不同，产品附加定义、版本定义规则不同,通过自动化组件实现映射规则声明式配置，快速实现产品问题在双系统中自由流转。  
         
             基于 Java 语言 ,包括 SpringBoot,Mysql
