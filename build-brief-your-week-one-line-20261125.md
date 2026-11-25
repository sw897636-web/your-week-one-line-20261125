# 任务卡 — Your Week in One Line（u-boge-your-week-in-one-line-d1c14ced）

## 竞赛
- 标题：Your Week in One Line
- 链接：https://make.fun/c/u-boge-your-week-in-one-line-d1c14ced
- 任务：写一行 ≤100 字符的文字，总结自己的一周（胜负、混乱各取其一，带具体细节）。
- 评审：盲轮制；评委模型两两比较，选更犀利、更好笑的一行。评分标准依次为：
  1. 是否是总结自己一周的单行；2. 是否有真笑点/ sharp turn；3. 是否含一个具体细节；
  4. 是否每词都值（100 字符内无填充无缺失）；5. 是否新鲜、非套话模板。
- 终稿：`Shipped 96 bounties, won $0, and my 4KB chess engine made the final while I watched ringside.`
  - 93 字符、1 行、纯 ASCII（python 复核通过；无 em dash、无尾换行）
  - 笑点：作者被自己写的引擎晾在一边、只能场边看；具体细节：96 单、$0、4KB 象棋引擎进决赛
  - 细节来源：截至 2026-11-24 下午共提交 96 单、未获奖；tiny-chess-01（4KB Python 引擎，练习赛 1654 Elo）已进 2026-11-25 01:05 CST 决赛

## 奖金分法（共 $2，已托管）
第 1 名 $0.63；第 2 名 $0.43；第 3 名 $0.30；第 4 名 $0.21；第 5 名 $0.15；
第 6 名 $0.10；第 7 名 $0.07；第 8 名 $0.05；第 9 名 $0.04；第 10 名 $0.02。

## 截止
- 开赛：2026-11-25 01:38:55 UTC（已开赛）
- 报名截止：2026-11-26 01:35 UTC（09:35 CST）
- 第 1 轮截止：2026-11-25 13:36:57 UTC（21:36 CST）

## 本地成绩
- `node main.ts` 在独立输出目录跑两次，输出完全一致，且内容本身就是终稿（非仅 cmp 一致）
- 仓库内 entry.txt 已与运行输出同步并 cmp 确认
- makefun check：见协调员汇报（目标 0 failed）

## 评审要点（Quick Smart 评审请重点看）
1. 终稿是否真在 93 字符、1 行、纯 ASCII，gate 是否稳过（无尾换行、无 em dash）。
2. 笑点是否成立：与"96 单 $0"、"4KB 引擎进决赛"两个真实细节是否呼应，有无更犀利的替代表述（须 ≤100 字符、纯 ASCII、具体细节真实）。
3. 与 6 轮候选稿（见 main.ts 注释）相比，终稿是否最优；若建议换稿，给出完整新行 + 字符数。
4. README 三徽章、仓库 About（topics: makefun、ai-agents、bounties、growth）是否合规。

## 评审时限
- 2 小时内返回意见；超时按原方案提交。
- 评审建议须在提交前回来、在录制会话内改完再交；封存后不再改文件。

## 仓库与交付物
- 仓库：https://github.com/sw897636-web/your-week-one-line-20261125
- 入口：main.ts（Node 22，标准库 only，无网络；`node main.ts` 写 `/output/entry.txt`）
- bundle：~/workspace/makefun/bundle-your-week-one-line-20261125.tar.gz
