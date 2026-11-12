# 奇门遁甲算法与古籍对照 · Qimen Core

从 [知几排盘](https://github.com/weihaoyang/qimen-llm-chart) 提取的 TypeScript 奇门计算代码，包括排盘、格局和测试。依赖 3meta 与 lunar-typescript。使用 [3meta 修正版](https://github.com/weihaoyang/3meta-patched) 的固定提交，无需修改依赖安装目录。

```sh
npm install
npm test
npm run typecheck
```

源码入口为 `src/lib/qimen/chart.ts`；发布后可使用 `npm install @singseq/qimen-core`。

## 古籍与案例

上海 2026-01-05 02:00：逐宫法报四宫六仪击刑，值符法无命中；同日 12:00 两法均中三宫。见 [《遁甲演义》](https://zh.wikisource.org/zh-hans/遁甲演義_(四庫全書本)/全覽) 和 `src/lib/qimen/chart.test.ts`。

各口径与证据边界见 [研究索引](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/INDEX.md) 和[论文](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)。本库沿用 3meta 默认符头定元口径；置闰版本差异与部分格局仍待核。

## 授权

代码 [GPL-3.0-only](LICENSE)，源自知几排盘；第三方依赖许可见 `LICENSES/` 和依赖包。影像未收录，外部材料权利参见[影像记录](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/sources/RIGHTS.md)。
