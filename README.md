# OverthinkingPapers

![Peer Review](https://img.shields.io/badge/Peer_Review-None-lightgrey?style=flat-square)
![Rigor](https://img.shields.io/badge/Rigor-Unnecessary-blue?style=flat-square)
![Utility](https://img.shields.io/badge/Practical_Utility-Zero-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

> *Rigorous mathematical and physical modeling applied to completely unserious topics.*  
> 将过于严谨的数理建模与分析方法，应用于完全不严肃的日常与脑洞话题。

---

## 📖 About / 关于本仓库

这里存放着一系列**非正式（Informal）**、**未经同行评审（Unpeer-reviewed）**的个人研究手稿与玩具模型（Toy Models）。

它们通常诞生于某些“本来没必要想这么深”的瞬间——比如游戏底层机制的逆向推导、亚文化现象的量化建模，或是纯粹的几何与动力系统思维体操。虽然话题很随意，但推导过程依然尽量保持数学与物理上的自洽。

---

## 📚 Index of Papers / 论文目录

| Date | Title & Abstract / 标题与核心结论 | Domain / 涉及领域 | Files / 附件 |
| :--- | :--- | :--- | :--- |
| `2026-11` | **[《BanG Dream! 少女乐团派对！》判定偏移机制的数学分析与校准方法](./01-bangdream-offset-calibration/paper.pdf)**<br><sub>建立音画与触摸三类物理延迟（$d_m, d_g, d_t$）的时间模型，揭示“节奏图标显示时机”与“判定时机”对严格音押/目押玩家的解耦规律（$\partial \epsilon_{\text{visual}} / \partial a = 0$），并给出基于控制变量法的两阶段新设备校准流程。</sub> | Rhythm Game Mechanics / Timing Modeling | [PDF (ZH)](./01-bangdream-offset-calibration/paper.pdf) |
| `2026-11` | **[未知初始位置与未知速度下的平面追逃（Planar Pursuit）](./02-planar-pursuit-rendezvous/paper.pdf)**<br><sub>研究直角墙壁环境下、投影动力系统驱动的开环四方向确定性会合策略。利用竖直边界的单向不变性与倍减速度下界搜索（$w_k = 2^{-k}$），证明了给定环境下的有限时间统一上界；同时通过交错半无限墙反例给出 $\tau \ge R(N-1)/8$ 的时间下界，说明上界对墙体分布的不可约依赖。</sub> | Projected Dynamical Systems / Differential Geometry | [PDF (ZH & EN)](./02-planar-pursuit-rendezvous/paper.pdf) |

---

## 📂 Repository Structure / 目录结构

```text
OverthinkingPapers/
├── 01-bangdream-offset-calibration/
│   └── paper.pdf         # 《BanG Dream!》判定偏移机制分析与校准
├── 02-planar-pursuit-rendezvous/
│   └── paper.pdf         # 未知初值与未知速度下的平面追逃（中英双语版）
└── README.md
```

---

## ⚠️ Disclaimer / 免责声明

1. **No Peer Review:** 所有文章均未经过任何学术期刊或同行评审，作者不对任何因过度思考导致的脑细胞损耗负责。
2. **Work in Progress:** 部分工程与机制建模存在理想化假设与边界简化，欢迎通过 Issue 提出反例、边界情况或更优雅的证明。
3. **Citation:** 如果你真的想在某个地方引用这些内容，建议直接甩出 GitHub 链接，格式随意。

---

## 📄 License

Unless otherwise noted, any accompanying code and scripts in this repository are licensed under the [MIT License](LICENSE), and the written manuscripts are shared under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).