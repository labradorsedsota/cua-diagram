# CUA 视觉智能体：找 Bug 能力四阶进化路径

```mermaid
graph TB
    classDef stage fill:#1e1e2f,stroke:#646cff,stroke-width:2px,color:#fff,font-weight:bold;
    classDef action fill:#2a2a35,stroke:#4caf50,stroke-width:1px,color:#ddd;
    classDef goal fill:#2d2114,stroke:#ff9800,stroke-width:1px,color:#fff;
    classDef flow fill:none,stroke:none,color:#646cff,font-weight:bold,font-size:16px;

    subgraph Agentic_TDD_Bootstrapping ["🚀 CUA 视觉智能体：找 Bug 能力四阶进化路径"]
        direction TB

        %% Stage 1
        S1["🛡️ 阶段一：启发式规则注入 (Heuristics)"]:::stage
        A1["📋 植入 UI/UX 视觉检查清单"]:::action
        A2["🔍 强制每步中断，执行全屏扫描"]:::action
        G1(("🎯 目标：<br>打破机械点击<br>建立基础视觉常识")):::goal

        %% Stage 2
        S2["🔨 阶段二：破坏性操作空间 (Chaos Action)"]:::stage
        B1["⌨️ 混沌输入 (超长文本/代码注入)"]:::action
        B2["📏 视口频繁极限缩放 (响应式打击)"]:::action
        B3["🖱️ 无序狂点 (并发状态破坏)"]:::action
        G2(("🎯 目标：<br>捕获布局溢出<br>与前端状态死锁")):::goal

        %% Stage 3
        S3["⚔️ 阶段三：AI 变异对抗 (Mutation Self-Play)"]:::stage
        C1["🔴 Vibe 侧：故意生成包含隐蔽 Bug 的代码"]:::action
        C2["🔵 CUA 侧：盲测并尝试捕获植入的 Bug"]:::action
        C3["🔄 提纯：漏网 Bug 转为 Few-shot 记忆池"]:::action
        G3(("🎯 目标：<br>左右互搏<br>训练深层 Bug 嗅觉")):::goal

        %% Stage 4
        S4["🤖 阶段四：多智能体并发探索 (Swarm Testing)"]:::stage
        D1["🏃♂️ Agent A: 竞速跑者 (测主干逻辑)"]:::action
        D2["🥴 Agent B: 笨拙用户 (测后退与回滚)"]:::action
        D3["🕵️ Agent C: 边缘猎手 (测边界与防御)"]:::action
        G4(("🎯 目标：<br>无脚本全覆盖<br>构建自动化 QA 集群")):::goal

        %% Connections
        S1 --> A1 & A2 --> G1
        G1 ===> |"🧠 获得基础感知力"| S2
        S2 --> B1 & B2 & B3 --> G2
        G2 ===> |"🛠️ 掌握破坏工具"| S3
        S3 --> C1 & C2 & C3 --> G3
        G3 ===> |"📈 建立对抗直觉"| S4
        S4 --> D1 & D2 & D3 --> G4
    end
```
