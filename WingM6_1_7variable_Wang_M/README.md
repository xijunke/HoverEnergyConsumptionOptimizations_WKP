# 说明注释区别

## 由WingM5_4_10variable_Prescribed_Harmonic改变而来；

重新采用Wang ZJ的翅膀运动学模式(含快变扭转运动)，共计7个翅膀运动学参数

hybrid_GA_fminsearch_WingM4_4_2不同于hybrid_GA_fminsearch_WingM4_4_1

0.hybrid_GA_fminsearch_WingM4_4_2由hybrid_GA_fminsearch_WingM4_4_1进化修改而来

1.该文件夹下为11变量GA混合优化之程序—fmincon—搜索算法

2.含翅膀形貌学和运动学参数(快变扭转翅膀运动学规律(7个参数))共计11个变量

3.功率调用函数和气动力调用函数一起调用同一个函数Aero_F_M_fruitfly——程序较简洁

4.变量约束区间改小——注意数据的上下限修改——直指频率约束f∈[150,260];

5.kenimatics_wing_and_AoA_fruitfly_sim输出(1000*9)矩阵

6.由WingM5_4_10variable_group演化而来


# Aerodynamic power for wingbeat pattern from the paper of 2007 Journal of Fluid Mechanism by Wang Z.J. etc.

## 沿着扭转轴x-axis的气动功率f=185.125Hz

![Aerodynamic power for wingbeat pattern](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WKP/blob/main/WingM6_1_7variable_Wang_M/aerodynamic_power_Wang_ZJ_wingbeat_pattern/pic_png/%E6%B2%BF%E7%9D%80%E6%89%AD%E8%BD%AC%E8%BD%B4x-axis%E7%9A%84%E6%B0%94%E5%8A%A8%E5%8A%9F%E7%8E%87f%3D185p125.png)

## 沿着拍打轴z-axis的气动功率f=185.125Hz

![Aerodynamic power for wingbeat pattern](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WKP/blob/main/WingM6_1_7variable_Wang_M/aerodynamic_power_Wang_ZJ_wingbeat_pattern/pic_png/%E6%B2%BF%E7%9D%80%E6%8B%8D%E6%89%93%E8%BD%B4z-axis%E7%9A%84%E6%B0%94%E5%8A%A8%E5%8A%9F%E7%8E%87f%3D185p125.png)

## 沿着扭转轴x-axis和拍打轴z-axis的总功率输出f=185.125Hz

![Aerodynamic power for wingbeat pattern](https://github.com/xijunke/HoverEnergyConsumptionOptimizations_WKP/blob/main/WingM6_1_7variable_Wang_M/aerodynamic_power_Wang_ZJ_wingbeat_pattern/pic_png/%E6%B2%BF%E7%9D%80%E6%89%AD%E8%BD%AC%E8%BD%B4x-axis%E5%92%8C%E6%8B%8D%E6%89%93%E8%BD%B4z-axis%E7%9A%84%E6%80%BB%E5%8A%9F%E7%8E%87%E8%BE%93%E5%87%BAf%3D185p125.png)