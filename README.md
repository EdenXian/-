# 这是一基于layUI+bootstrap+springBoot+sqlserver的后台管理系统
前端主要用了layUI和bootstrap
其中消息处理用了toastr和layUi所带的独立组件layer
table页使用了jQueryTable.为什么没有使用自带的table，我是为了更好的处理后台过来的数据，其实不是很好，后面有时间我会使用layUi自带的table
登录页面目前只使用了简单的登录，有layuI版带验证码的和bootstrap版的，目前使用的是bootstrap版的
总的来书就是layUi一套通用的后台模板

# 后台springboot+sqlserver 
工具：eclipse+Tomcat7+jdk1.8+windows
这后台主要写的是excel的处理和接口数据的加密，
其中excel插入数据比较简单，数据的加密使用了现在主流的非对称加密，公钥和私钥
接口方面也是发送数据和接入数据，对数据的处理，放入数据库中
