```mermaid
%%{ init: { 'flowchart': { 'curve': 'linear', 'nodeSpacing': 15, 'rankSpacing': 60 } } }%%
graph TB
    %% --- 全局样式设置 ---
    classDef common fill:#fff,stroke:#000,stroke-width:1px,shape:rect,font-size:13px;

    %% --- 根节点 ---
    Root[箴言书院<br/>虚拟漫游系统]:::common

    %% ==========================================
    %% 核心结构：使用直线连接
    %% ==========================================
    
    %% 1. 核心目标
    Goal[核心目标]:::common
    Root --- Goal
    Goal --- G1[文化传承]:::common
    G1 --- G2[审美教育]:::common
    G2 --- G3[沉浸体验]:::common

    %% 2. 第一阶段
    Phase1[第一阶段:<br/>基础调研]:::common
    Root --- Phase1
    Phase1 --- P1_1[历史内涵]:::common
    P1_1 --- P1_2[建模依据]:::common
    P1_2 --- P1_3[建筑空间]:::common

    %% 3. 第二阶段
    Phase2[第二阶段:<br/>系统构建]:::common
    Root --- Phase2
    Phase2 --- P2_1[PBR/光影]:::common
    P2_1 --- P2_2[自由视角]:::common
    P2_2 --- P2_3[晨诵午读]:::common

    %% 4. 第三阶段
    Phase3[第三阶段:<br/>体验优化]:::common
    Root --- Phase3
    Phase3 --- P3_1[UI与<br/>引导机制]:::common
    P3_1 --- P3_2[用户体验<br/>理论]:::common
    P3_2 --- P3_3[提升<br/>沉浸感]:::common

    %% 5. 第四阶段
    Phase4[第四阶段:<br/>评估产出]:::common
    Root --- Phase4
    Phase4 --- P4_1[策略迭代]:::common
    P4_1 --- P4_2[用户测试]:::common
    P4_2 --- P4_3[价值评估]:::common

    %% --- 样式应用 ---
    class Root,Goal,G1,G2,G3,Phase1,P1_1,P1_2,P1_3,Phase2,P2_1,P2_2,P2_3,Phase3,P3_1,P3_2,P3_3,Phase4,P4_1,P4_2,P4_3 common
