# 2024TencentUE5-Assignment1

## 效果

红色为特殊方块，击中将获得双倍分数，左上角显示目前分数，上方中间显示剩余秒数

![Figure1](https://github.com/Rozannn/2024TencentUE5-Assignment1/blob/main/Figure/Figure1.png)

新建ATarget作为目标，含有可在蓝图中调整参数Score为击中后获得分数。

![Figure2](https://github.com/Rozannn/2024TencentUE5-Assignment1/blob/main/Figure/Figure2.png)

将原本WeaponComponent替换为AWeapon。

为子弹类添加可调整参数Damage，为击中后将物体放缩倍数。



![Figure3](https://github.com/Rozannn/2024TencentUE5-Assignment1/blob/main/Figure/Figure3.png)

游戏结束后会在左上角输出角色uid与分数，以及所有角色分数总和

![Figure4](https://github.com/Rozannn/2024TencentUE5-Assignment1/blob/main/Figure/Figure4.png)

GameMode类中添加参数控制游戏开始时特殊方块数量与游戏时间

![Figure5](https://github.com/Rozannn/2024TencentUE5-Assignment1/blob/main/Figure/Figure5.png)
