
# 说明注释区别

由WingM6_1_7variable_Wang_M改变而来

重新采用Wang ZJ的翅膀运动学模式(含快变扭转运动)，共计6个翅膀运动学参数

hybrid_GA_fminsearch_WingM4_4_2不同于hybrid_GA_fminsearch_WingM4_4_1

0.hybrid_GA_fminsearch_WingM4_4_2由hybrid_GA_fminsearch_WingM4_4_1进化修改而来;

1.该文件夹下为11变量GA混合优化之程序—fmincon—搜索算法;

2.含翅膀形貌学和运动学参数(快变扭转翅膀运动学规律(6个参数))共计11个变量;

3.功率调用函数和气动力调用函数一起调用同一个函数Aero_F_M_fruitfly——程序较简洁;

4.变量约束区间改小——注意数据的上下限修改——直指频率约束f∈[150,260];

5.kenimatics_wing_and_AoA_fruitfly_sim输出(1000*9)矩阵;

6.由WingM6_1_7variable_Wang_M演化而来.