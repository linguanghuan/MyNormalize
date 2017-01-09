#java 个人编程规范
##eclipse设置utf-8编码
    Window -> Preferences -> General -> Workspace -> Text file encodeing
    设置为utf-8

##注释

###类注释
####eclipse设置位置
    Window -> Preferences -> java -> Code Style -> Code Template
####eclipse设置内容
    /**
    * @Author linguanghuan
    * @Time ${time}
    * @Desc 
    *    
    */
####例子
    /**
    * @Author linguanghuan
    * @Time 2017-01-09 14:41:55
    * @Desc 
    *    linux c zlib库 的java解压方式
    */


###函数注释
    /**
    *@Desc
    *
    */
####例子
    /**
    * @Desc
    *   初始化配置
    */

##代码
###类名
    使用 UpperCamelCase风格，必须遵从驼峰形式，但以下情形例外：（领域模型的相关命名） DO / DTO / VO / DAO 等
    例子：UserDO XmlService TaPromotion
###方法名
    方法名、参数名、成员变量、局部变量都统一使用 lowerCamelCase风格，必须遵从驼峰形式。
    例子： userId getHttpMessage()

##其他
###缩进4个空格
####eclipse设置
    Window -> Preferences -> Editor -> TextEditors -> Insert space for tabs (checked) 
    Window -> Preferences -> Java -> Code Style -> Formatter -> Edit -> Tab policy -> Spaces only
    
    
##参考
    阿里巴巴Java开发手册（公开版）.pdf

    

