# ShooterGameTPS
## 第二次作业

1. 实现了击中靶子和击飞的效果；  
2. 实现了手雷投掷，没找到好的模型，使用了一个Shpere代替，按“G”投出，设置了投掷动画，由于Movement的速度没有加上人物移动速度，所以移动抛出时效果较差；  
3. 加入了Idle，Walk，Shoot，Jump等动作动画，但是做混合时，上下半身不对应，导致子弹射出方向和枪口方向不对应；  
4. 添加了枪身材质和手电效果，按“F”开启关闭手电，加入了POST Processing的景深效果；  
5. 完成了八方向移动动画，没有找到抬枪动画，没有完成上下左右开枪的动画效果，但子弹的生成位置是由Controller的旋转角决定的。

使用Shipping打包成Win64平台，UI没有做上次的迁移，积分不更新，Esc退出游戏。
