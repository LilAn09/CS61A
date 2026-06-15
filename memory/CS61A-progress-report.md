---
name: CS61A-progress-report
description: CS61A 课程学习进度全面报告，截至 2026-06-15
metadata:
  type: project
---

# 🎓 CS61A 学习进度报告

> 报告生成日期：2026-06-15
> 上次学习活动：2026-04-27（已中断约 **49 天**）
> 总完成度：**约 25%**（已完成 7/27 个模块）

---

## 📊 总览

| 类别 | 总数 | 已完成 | 进行中 | 未开始 |
|------|:----:|:------:|:------:|:------:|
| Homework (HW) | 10 | 4 (HW01, HW02, HW03*, HW04) | 0 | 5 (HW05~HW10) |
| Lab | 13 | 3 (Lab00~Lab02) | 0 | 10 (Lab03~Lab12) |
| Project | 4 | 1 (Hog 🎲) | 0 | 3 (Cats, Ants, Scheme) |

> *HW03 完成了 5/7 道题，约 71%，算作进行中

---

## ✅ 已完成模块

### 📝 Homework

#### HW01 — 函数、控制 `[100%]`
| 函数 | 知识点 |
|------|--------|
| `a_plus_abs_b` | 高阶函数作为返回值 |
| `two_of_three` | 条件表达式 |
| `largest_factor` | `while` 循环 |
| `hailstone` | 冰雹序列 + 循环 |

#### HW02 — 高阶函数 `[100%]`
| 函数 | 知识点 |
|------|--------|
| `product` | 序列乘积 |
| `accumulate` | 通用累计函数（抽象） |
| `summation_using_accumulate` | 用 `accumulate` 实现求和 |
| `product_using_accumulate` | 用 `accumulate` 实现求积 |
| `make_repeater` | 函数重复应用（返回函数） |

#### HW03 — 递归 `[~71%]`
| 函数 | 知识点 | 状态 |
|------|--------|:----:|
| `num_eights` | 数字中 8 的个数（递归） | ✅ |
| `digit_distance` | 数字相邻位差之和（递归） | ✅ |
| `interleaved_sum` | 交替求和（递归，不用 %） | ✅ |
| `count_dollars` | 找零钱（从大到小） | ✅ |
| `count_dollars_upward` | 找零钱（从小到大） | ✅ |
| `move_stack` | **汉诺塔（未完成）** | ❌ |
| `make_anonymous_factorial` | **匿名函数递归（未完成）** | ❌ |

#### HW04 — 序列、数据抽象、树 `[100%]`
| 函数 | 知识点 |
|------|--------|
| `shuffle` | 列表交错 |
| `deep_map` | 嵌套列表递归映射（原地修改） |
| `planet / mass` | 数据抽象（行星） |
| `balanced` | Mobile 平衡检查（抽象屏障） |
| `berry_finder` | 树搜索 |
| `max_path_sum` | 树最大路径和 |

### 🔬 Lab

#### Lab00 — 入门 `[100%]`
- `twenty_twenty_four` 基础运算

#### Lab01 — 控制、循环 `[100%]`
| 函数 | 知识点 |
|------|--------|
| `digit` | 数位提取 |
| `middle` | 三个数取中间值 |
| `falling` | 下降阶乘 |
| `divisible_by_k` | 被 k 整除的数 |
| `sum_digits` | 数位求和 |
| `double_eights` | 连续两个 8 检测 |

#### Lab02 — 高阶函数 `[100%]`
| 函数 | 知识点 |
|------|--------|
| `composite_identity` | 函数复合后比较 |
| `count_cond` | 满足条件的数的个数 |
| `multiple` | 最小公倍数 |
| `cycle` | 函数循环应用 |

### 🎮 Project

#### Hog 🎲 — 骰子游戏 `[100%]`
> **全部 12 道题 + UI 修复已完成**

| 问题 | 功能 |
|:----:|------|
| 1 | `roll_dice` — 掷骰子（出现 1 则 Pig out） |
| 2 | `boar_brawl` — 野猪搏斗规则 |
| 3 | `take_turn` — 一回合得分 |
| 4 | `num_factors` / `sus_points` / `sus_update` — Sus Fuss 规则 |
| 5 | `play` — 完整游戏循环 |
| 6 | `always_roll` — 固定骰子数策略 |
| 7 | `is_always_roll` — 检测固定策略 |
| 8 | `make_averaged` — 函数平均化装饰器 |
| 9 | `max_scoring_num_rolls` — 最优骰子数 |
| 10 | `boar_strategy` — 野猪策略 |
| 11 | `sus_strategy` — Sus Fuss 策略 |
| 12 | `final_strategy` — 最终策略 |

**修复记录**：`play` 函数中调用策略时缺少 `(score, opponent_score)` 参数，已修复。

---

## ❌ 未开始模块

### 📝 Homework (HW05 ~ HW10)

| 作业 | 内容 | 知识点 |
|:----:|------|--------|
| **HW05** | 生成器 | `yield`、`hailstone` 生成器、`merge`、`stair_ways`、`yield_paths` |
| **HW06** | OOP + 链表 | `VendingMachine`、`store_digits`、`deep_map_mut`、`two_list` |
| **HW07** | Scheme 基础 | `pow`、`cadr`/`caddr`、`repeatedly-cube` |
| **HW08** | Scheme 列表 | `ascending?`、`my-filter`、`interleave`、`no-repeats` |
| **HW09** | Scheme 宏 | `curry-cook`、`curry-consume`、`switch` 宏 |
| **HW10** | SQL | 父-子表、狗尺寸表、SQL 查询 |

### 🔬 Lab (Lab03 ~ Lab12)

| 实验 | 知识点 |
|:----:|--------|
| Lab03 | 高阶函数（`print_if`、`make_onion` 等） |
| Lab04 | 数据抽象（城市、距离计算） |
| Lab05 | 列表、树、可变序列 |
| Lab06 | 面向对象（银行账户、邮件系统、硬币） |
| Lab07 | 继承、链表、递归链表 |
| Lab08 | 树、可变树、递归树操作 |
| Lab09 | Scheme 函数（`over-or-under`、`gcd` 等） |
| Lab10 | Scheme 解释器（`calc_eval` 等） |
| Lab11 | Scheme 宏 |
| Lab12 | SQL |

### 🎮 Project (Cats, Ants, Scheme)

| 项目 | 内容 | 规模 |
|:----:|------|:----:|
| **Cats 🐱** | 打字速度测试 + 自动纠错 | 10 道题 |
| **Ants 🐜** | 植物大战僵尸风格塔防 | 12 道题 + 扩展 |
| **Scheme 🧮** | Scheme 解释器 | 16 道题 + 扩展（最大项目） |

---

## 📈 知识地图

根据 CS61A 课程进度，你当前处于：

```
Python 基础 ───→ 高阶函数 ───→ 递归 ───→ 数据抽象 ───→ OOP ───→ 生成器 ───→ Scheme ───→ SQL
    ✅              ✅           ✅ ✅         ✅              ❌       ❌         ❌        ❌
  HW01/Lab00      HW02/Lab02   HW03/Lab03   HW04/Lab04     HW06     HW05      HW07-09   HW10/Lab12
  Lab01                        Hog🎲                                              Lab09-11
                                                                                 Scheme项目
```

---

## 💡 推荐学习路线

根据你当前的进度，以下是最合理的路线：

1. **🔥 抓紧 HW03 收尾**（最有连续性）
   - 完成 `move_stack`（汉诺塔递归）
   - 完成 `make_anonymous_factorial`（Y 组合子思想）

2. **进入生成器阶段**
   - Lab05 → HW05

3. **面向对象编程**
   - Lab06 → HW06

4. **树与递归深化**
   - Lab07 → Lab08

5. **开始新项目**
   - Cats 🐱（打字游戏，趣味性强）

6. **Scheme 函数式编程**
   - Lab09 ~ Lab11 → HW07 ~ HW09

7. **SQL**
   - Lab12 → HW10

8. **最后攻坚**
   - Ants 🐜（塔防游戏）
   - Scheme 🧮（解释器，大魔王）
