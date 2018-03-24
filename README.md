# getUserAutoconfirmTime-zhwiki
获取一个用户成为自动确认用户的时间，仅适用于中文维基百科

本项目有2个PHP文件，一个是用于提供服务的主文件（[getUserAutoconfirmTime.php](https://github.com/RazeSoldier/getUserAutoconfirmTime-zhwiki/blob/master/getUserAutoconfirmTime.php)），一个是用于高亮前者代码的文件（[getUserAutoconfirmTime-code.php](https://github.com/RazeSoldier/getUserAutoconfirmTime-zhwiki/blob/master/getUserAutoconfirmTime-code.php)）。

## 功能
通过中文维基百科的API来计算出已注册用户成为自动确认用户的时间。

## 使用
主文件可独立作为一个网页运行，包含UI。主文件几乎可视为开箱即用，但仍需在php.ini配置`allow_url_fopen = on`。
