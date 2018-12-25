# Android_assignment_3
安卓第三次作业，再上一个项目的基础上面，新的增加了用户登录界面。

合作者：
汤泓敏（16301132）
明旭冉（16301013）

任务总述：
在前面项目的基础上，完善用户登录的功能

项目逻辑：
用户在初次使用APP的时候，需要利用手机进行登录操作，在登录成功之后才可以使用。

使用流程：
1. 打开APP
2. 进入欢迎界面（播放一定时间）
  检测用户状态
  ——用户已经登录，直接进入主界面
  ——用户没有登录，输入手机号，获取验证码，正确输入服务端发送的验证码之后，进入主界面
3. APP包含三个主要的界面，继承【assignment2】的内容，用户可以在登录之后，按照自己的喜欢使用APP。

项目亮点：
1. 利用服务器，学习服务器配置，利用服务器发送验证码；
2. 实现手机验证码进行验证登录的功能，符合当下手机用户的惯用方式；
3. 快速注册登录，省去不必要的冗余信息（相关信息，可以进入APP后在“个人中心进行修改”）
