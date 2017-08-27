# springcloud-config
springcloud的配置文件
配置服务器，启动微服务事，如果部署了配置服务器，微服务寻找配置文件规则：
   1 先根据配置的application.name在git上寻找与名称相同的配置文件，如custom1服务找custom1.yml。
   2 如果不存在，就寻找git上面的名称为application.yml的配置文件。该文件可以当做公共配置。
   3 两者都没有，就寻找本地工程中的配置文件。
