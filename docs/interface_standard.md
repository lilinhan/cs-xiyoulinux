
##应用编码规范

为了提高平台代码的复用以及可维护性，平台及应用应该使用统一的命名规范。

####文件命名规范

模式   | 描述 |示例
------:|-------|----
cs_*.class.php | 平台接口类文件  | cs_user.class.php
*.class.php    | 应用接口类文件  | feedback.class.php
cs_*.inc.php   | 平台函数文件    | cs_valid.inc.php
*.inc.php      | 普通函数文件    | valid.inc.php

####变量命名规范

模式  |描述 | 示例
-----|------|---
$cs_*_object | 平台接口类实例 | $cs_user_object
$cs_str_* | 全局字符串变量(global string) | $cs_str_login_uid
$cs_bool_* | 全局布尔变量(global bool) 
$cs_const_* | 全局静态变量(global constant)
