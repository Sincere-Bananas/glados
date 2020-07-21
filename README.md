# glados
穿墙术
======
注册地址：
-----
1、打开 https://github.com/glados-network/GLaDOS ，找到[Register（注册）] 点击打开（pc浏览器可以用ctrl+f 查找），
打开链接，填写邮箱 在邮箱输入的下方点击小字发送验证码到邮箱  打开邮箱获取验证码，验证后进行登录使用下面的激活码进行激活。

2、输入激活码QJBJI-XRP7S-GN471-QFO4Q，进行激活，获得3天试用。

3、每天手动进行checkin一次，能增加一天。

脚本功能：
-----
1、通过Github Action自动定时运行checkin.py脚本。

2、通过cookies自动登录（https://glados.rocks/console/checkin)，脚本会自动进行checkin。

3、然后通过“Server酱”（http://sc.ftqq.com/3.version)，自动发通知到微信上。

食用姿势：
-----
先“Fork”本仓库。

注册GLaDOS，方法见上。

登录GLaDOS后获取cookies。（简单获取方法：浏览器快捷键F12，打开调试窗口，点击“network”获取）

在仓库“Settings”里创建3个“Secrets”，分别是：

COOKIE（必填）
SERVE（server酱开关，默认是off，填on的话，会同时开启cookie失效通知和签到成功通知）
SCKEY（填写server酱sckey，不开启server酱则不用填）
提交后，每天零点会自动触发，并会执行自动checkin，如果开启server酱，会自动发通知到微信上。

如果以上都不会的话，注册GLaDOS后，每天勤奋点记得登录后手动进行checkin即可。

[如果是Edu邮箱，可免费升级为360天。]
