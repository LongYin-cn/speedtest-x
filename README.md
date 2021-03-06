# speedtest-x

本仓库为 [LibreSpeed](https://github.com/librespeed/speedtest) 的延伸项目，LibreSpeed 是一个非常轻巧的网站测速工具。

speedtest-x 使用文件数据库来保存来自不同用户的测速结果，方便您查看全国不同地域与运营商的测速效果。

## 扩展细节
 - 用户测速会上传测速记录并保存至网站服务器
 - 不依赖 MySQL，使用文件数据库
 - IP 库改用 [ip.sb](https://ip.sb)，运营商记录更为精确

## 恰饭

Jetbrains 全家桶教育许可，正规国内大学渠道，9.9 元，购买地址：[https://xiaozhu.win](https://xiaozhu.win)

## 使用

1、下载本仓库并解压到网站目录，访问 `{你的网站地址}/index.html` 进行测速

2、打开 `{你的网站地址}/results.html` 查看测速记录 

> 修改 `backend/config.php` 中的 `MAX_LOG_COUNT` 可定义最大可保存多少条测速记录

## 环境要求
 - PHP 5.6+

## 截图

![index](https://raw.githubusercontent.com/BadApple9/images/main/indexdemo.png)
![results](https://raw.githubusercontent.com/BadApple9/images/main/resultsdemo.png)

## 鸣谢
 - [LibreSpeed](https://github.com/librespeed/speedtest)
 - [ip.sb](https://ip.sb)
 - [SleekDB](https://github.com/rakibtg/SleekDB)
