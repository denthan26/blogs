# 使用状态机创建玩家

- 新建场景
- 创建2D节点，将节点类型改为characterbody2D
- 保存
## 动画添加
- 添加子节点，AnimatedSprite2D
- 在检查器、Animation、Sprite Frames中新建帧
- 点击符号，则会出现spriteframes界面
- 点击从精灵表中添加帧
- 点击前两个，添加帧，播放动画，修改名称为idle front
- 点击加载后默认动画，为玩家的初始动画，即加载时自动播放该动画
- 依次添加back、left、right
- 动作快时，降低zhenlv，这里设置为3fps
- 完成tilling的动画添加
- 完成chopping的动画添加
- 完成watering的动画添加
- 完成walk的动画添加
- 小技巧：在2D中，通过方向键来控制人物位置

## 添加碰撞体
这里添加是因为系统提示添加
- 在player下添加collisionshap2D，创建圆形形状，包围玩家

## 测试玩家
- 进入玩家测试场景
- 将player场景拖入工作区中，运行测试

## 创建键盘输入
在创建状态机之前，添加按键输入
- walk按键映射
- 进入玩家场景，创建状态机
