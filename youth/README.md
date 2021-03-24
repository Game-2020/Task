Quantumult X中青看点全套薅羊毛脚本

🔘 添加定时任务
编辑配置文件，在[task_local]下粘贴Task脚本
# 中青看点签到 & 开转盘宝箱&阅读时长
10 */1 * * * https://raw.githubusercontent.comert/Scripts/master/Task/youth.js, tag=中青看点签到&开转盘宝箱&阅读时长, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/youth.png, enabled=true
# 中青自动阅读
10 */2 * * * https://raw.githubusercontent.comert/Scripts/master/Task/Youth_Read.js, tag=中青看点自动阅读, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/youth.png, enabled=true
# 中青看点浏览赚 & 看看赚
30 6 * * * https://raw.githubusercontent.com/ztxtop/x/main/youth_banner.js, tag=中青看点看看赚&浏览赚, img-url=https://raw.githubusercontent.com/Orz-3/mini/master/Color/youth.png, enabled=true

🔘 添加远程重写订阅
编辑配置文件，在[rewrite_remote]下粘贴重写订阅
# 中青看点Cookie & Body获取
https://raw.githubusercontent.com/erdongchanyo/Rules/main/Quantumult%20X/Youth/Youth_cookie.conf, tag=中青看点cookie获取, update-interval=86400, opt-parser=false, enabled=false
https://raw.githubusercontent.com/erdongchanyo/Rules/main/Quantumult%20X/Youth/Youth_Read.conf, tag=中青看点阅读Body获取, update-interval=86400, opt-parser=false, enabled=false
# 中青看点浏览赚&看看赚Cookie(打开资源解析器)
https://raw.githubusercontent.com/ztxtop/x/main/rewrite-zqkkz.plugin, tag=中青看点看看赚&浏览赚Cookie获取, update-interval=86400, opt-parser=true, enabled=false

🔘使用方法：
进入[重写]-[引用]
启用「中青看点Cookie & Body获取」
进入APP点 - 我的 - 任务中心
获取签到Cookie
阅读一篇文章或者视频(等圈圈转完)
获取阅读请求Body&阅读时长
在阅读文章拉下面有个惊喜红包，点击获取(概率性，如果没有，请跳过)
获取惊喜红包
获取100个文章&100个视频的Body，由于获取量大，可以抽空阅读文章或视频，获取更多的Body

各执行一次task任务 中青看点签到&开转盘宝箱&阅读时长 / 中青看点自动阅读，看脚本运行是否正常

获取浏览赚&看看赚Cookie
进入中青任务中心，找到看看赚入口 点击里面的任务获取Cookie，每个任务都获取一遍Cookie，会叠加。 然后手动运行一次脚本看看是否成功。
在看看赚的任务栏上方，点击阅读文章获取浏览赚Cookie

执行一次task任务 中青看点浏览赚&看看赚，看脚本运行是否正常
