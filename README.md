# oil_mine_programming
#项目是对油田的各个单元的打井数进行优化。我建立了lightgbm模型进行各个单元年产油量的预测，并把各个单元年产油量看成一个随机变量，建立机会约束模型；求解上将不确定优化问题退化为等价的确定优化问题，将多目标规划转化为单目标，并对降级为条件的目标进行敏感性分析；依据比例选择策略，在pareto非劣解解集中选出偏好解。
