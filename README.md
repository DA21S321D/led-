# led-点阵风扇
led点阵风扇
北邮大二数电实验2020年，led点阵风扇
只有基础功能（SW开关有瑕疵，不过不影响功能）




 下面是题目要求：
* [x] 1、用8x8点阵模拟风扇转动，并采用双色点阵显示；
* [x] 2、风扇转动方式如图1所示，包括四个点阵显示状态并按顺序循环显示。风扇转动速度根据环境温度分为4档，其中1档的四个显示状态之间的切换时间为1秒，2档为0.5秒，3档为0.25秒，4档为静止不动；
* [x] 3、环境温度通过2个按键设置，BTN1用来增加，BTN2用来减少，温度可设置范围为10℃——40℃，温度精度为1℃，并用两个数码管DISPI和DISPO进行温度显示。风扇根据不同的温度自动采用不同的转动速度，其中20℃——24℃对应1档，25℃——29℃对应2档，30℃——40℃对应3档，10℃——19℃对应4档，用一个数码管DISP7显示档位：
* [x] 4、定时模式：在风扇不同转动速度下，可以通过按键切换进入定时模式。定时时间可设置范围为10~39秒，采用两个数码管进行倒计时显示，当倒计时结束后，风扇状态保持静止不动；
* [x] 5、设置开关键Sw2，风扇开机初始状态为20℃、1档，关机状态为点阵、数码管全灭。
/n提高要求：
* [x] 1、设计LED风扇的其他工作模式；
* [x] 2、利用实验板上的温度传感器代替按键直接获取温度数据，实现对LED风扇四档转速的自动控制；
* [x] 3、用数码管实时显示温度传感器的温度数据，精度为0.1℃；
* [x] 4、自拟其他功能。
