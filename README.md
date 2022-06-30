# gzhu_qndxx
你还在为青年大学习而烦恼吗，其实问题很简单，有两种方法。  

方案一、点击“开始学习”后，视频开始播放即可返回，不放心可以查看记录，会有记录的；  
（但是方案一每周仍然得用差不多一分钟时间，而且也可能忘记看然后被催，所以更推荐方案二） 

方案二、python！  
(1)下载main.py , mid.txt  
(2)公众号广州青年-青年大学习-认证资料-生成电子团员证-（底部）生成电子团员证-···-复制链接  
（应为https://tuan.12355.net/wechat/view/information/member_certification_generated.html?memberId=XXXXXXX&showMemberAdditionNames=&showMemberRewardIds=&isShowAllFee=true）， 将XXXXXXX添加至mid.txt后保存（可多账号，一行一mid即可）  
(3)python main.py测试，去青年大学习界面查看是否有记录  
（PS：记录只会显示本周第一次学习的时间，后面再学习不会覆盖，所以如果学了建议新的一周再测试）  
(4)自动化实现方式请自行百度“windows怎么设置定时任务”（每周执行时间自行选择一个确保自己电脑开机的时间且尽量不要周一周一qndxx不稳定）  
（建议：使用.bat而不使用.py，.bat文件方法---创建main.txt，写入正常用cmd执行python main.py需要的步骤，例如d:&cd qndxx&python main.py之后将.txt后缀改完.bat即可）  
(5)为了方便确认是否进行任务，此处采用pushplus推送（www.pushplus.plus） [设置环境变量，变量名:PPTKEY， 值:your pushplus token]
