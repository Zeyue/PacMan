# PacMan
A simple PacMan game using Cocos for IOS

游戏名称：吃豆豆 
开发环境：VS 2013 + C++ + Cocos 
Git：Github 
UML:  Gliffy 
操控方式：滑动改变方向 
 
游戏角色： 
  1. Pac man 
  2. Ghosts 
 
游戏界面： 
  1. 砖块地图 
    a. 墙 
    b. 通道 
  2. 状态栏 
    a. 生命 
    b. 分数 
    c. pacman状态 
      (1) 普通 
      (2) 变身，显示剩余时间 
  3. 控制栏 
    a. 主菜单按钮 
    b. 暂停（继续） 
  4. 主菜单 
    a. 开始（继续） 
    b. 静音 
    c. 游戏说明 
    d. 制作人 
  5. 结束画面 
    a. 胜利画面 
    b. 失败画面 
  6. 资源 
    a. 超级豆子。吃到超级豆子后，pac man可攻击ghosts 
    b. 豆子。必须吃掉全部才能过关 
  7. *bonus：神器加成   
    a. 无敌 
    b. 穿墙 
    c. 加速 
 
游戏描述： 
1. 作为Ghosts，在地图一个封闭区域内产生，区域有出口； 
2. 作为Ghosts，当和pacman在同一条通路上时，才可看到pacman，进行追踪；否则，自动寻路，遍历所有通路； 
3. 作为Pacman，出生在地图中下位置，共有3条命； 
4. 作为Pacman，必须吃掉所有豆子才能过关； 
5. 作为Pacman，吃到超级豆后拥有5秒的吃ghosts能力； 
6. 作为Ghosts，当pacman变身后，要切换为逃命状态，躲避pacman； 
7. 作为Ghosts，当pacman变身后，被pacman追上，判定死亡，并在出生点重生； 
8. 作为Pacman，当在正常状态下被Ghost追上，判定死亡。若有剩余生命，则在出生点重生；否则游戏结束。
