# WordPress使用文档

##  前端入口文件

 访问站点首先执行入口文件\(入口文件index.php\)。

放在Wordpress应用之前.这个文件不作任何事情,但是加载wp-blog-header.php文件然后告诉Wordpress去加载主题.

告诉WordPress加载WordPress主题并输出它.

定义常量`WP_USE_THEMES` = `true`

加载WordPress环境和模板

引入`wp-blog-header.php`文件

##  加载WordPress环境和模板

加载WordPress环境和模板\(wp-blog-header.php\)

设置全局变量`$wp_did_header`为`true`

加载WordPress类库文件`wp-load.php`

设置WordPress查询`wp()`

加载主题模板

## 常规模版函数参考

### **1. get\_header\( string $name = null \)**

Load header template.**\(**加载头模板。\)

描述：  
Includes the header template for a theme or if a name is specified then a specialised header will be included.  
包含主题的头模板，或者如果指定了名称，则包含专门的头模板。  
For the parameter, if the file is called "header-special.php" then specify "special".  
对于参数，如果文件被称为"header-special.php"然后指定"special"。

参数：  
`$name`  
\(string\) \(Optional\) The name of the specialised header.  
\(字符串\)\(可选\)专用标题的名称。  
Default value: null  
默认值:空

来源：  
File: wp-includes/general-template.php

## 主题函数参考

###  **1. the\_custom\_header\_markup\(\)**

Print the markup for a custom header.**\(**打印自定义头的标记。\)

描述：  
A container div will always be printed in the Customizer preview.  
容器div将始终打印在自定义器预览中。

来源：  
File: wp-includes/theme.php

