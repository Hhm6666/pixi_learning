### pixi实现飞船射击外星人小游戏
根据官方文芳简单了解了pixi知识，然后写了这个小demo<br>
1、界面组成
- GameScene画布 ：<br>
  - ship精灵<br>
  - alien精灵<br>
  - 子弹bullet (Graphics类的实例化)<br>
  - 分数条scoreBar<br>
  - 生命条healthBar<br>
- GameOverScene画布 ：<br>
   - You Won文本<br>
   - You Lost文本<br>
 
 2、游戏流程<br>
 玩家通过左箭头按键和右箭头按键操作控制飞船的左右移动<br>
 space键发射子弹<br>
 当子弹击中外星人时，分数条增多一格，分数条颜色充满时，游戏结束，玩家获胜<br>
 不断移动中的外星人碰撞到飞船时，生命条减少一格，生命条颜色减少至全黑时，游戏结束，玩家失败<br>
 
