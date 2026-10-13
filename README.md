# XP-算子研究项目

研究函数方程成立位置所定义的相关集 X_P(f)，以及紧线性差、非齐次函数方程与自然性。

## 阅读入口与文件索引

| 文件 | 内容 | 版本 |
|---|---|---|
| [研究讲义 PDF](drafts/lecture/XP_operator_research_lecture.pdf) / [TeX](drafts/lecture/XP_operator_research_lecture.tex) | 综合阅读入口；基本框架、线性理论、Cauchy相关集与整函数分类 | 2026-10-13 整合初稿 |
| [线性差详细汇报 PDF](drafts/linear/linear_difference_report.pdf) / [TeX](drafts/linear/linear_difference_report.tex) | 存在唯一性、自然性、有限模板、低支撑分类 | 2026-10-09 |
| [综合草稿 PDF](drafts/general/XP_operator_draft.pdf) / [TeX](drafts/general/XP_operator_draft.tex) | 紧性、线性差、自然性与加法/乘法Cauchy相关集 | 2026-10-09 修订 |
| [整函数分类 PDF](drafts/entire/entire_defect_classification.pdf) | 原文件《X-算子的性质.pdf》；任意维数整函数乘法缺陷分类 | 2026-10-07 |

研究讲义已合并专题稿中的部分内容。专题稿作为来源保留；不因上传时间较晚而认定所有结论更强。上述数学结论是原稿的陈述，本次归档未重新完成独立审稿。

## 术语

“线性差”专指对函数变量满足 K-线性的算子；仅满足可加性的对象称“加性差”。

## 编译入口

安装包含中文支持的 TeX Live 或 MiKTeX，以及 latexmk；在相应源文件目录运行：

```bash
cd drafts/lecture
latexmk -xelatex XP_operator_research_lecture.tex
```

其余 TeX 文件同样使用 XeLaTeX。讲义无需外部图片、bib 或其他 TeX 输入文件；字体优先 Noto Sans CJK SC，其次 Fandol/SimSun。本次保留已有 PDF，没有重新编译。

## 验证与下一步

本次找到的项目文件只有 TeX 和 PDF，没有独立验证程序。PDF 可正常提取文字；SHA-256 清单见 [文件来源与校验](docs/source-manifest.json)。编译成功不代表数学证明已通过独立验证。

以下问题来自讲义“结论边界与后续研究”，仍属于待研究事项：

1. 高支撑秩二模板的方向耦合与齐次核分类。
2. 将非齐次有限行关系压缩为可执行的余循环条件。
3. 高阶广义多项式的多重张量代数描述。
4. 无限维值域中消除延拓障碍的附加条件。
5. 高维高次加法 Cauchy 缺陷的不可约性与实现分类。
6. 乘法多项式相关集的乘积、交集、平移同构和次数问题。
7. 有理/亚纯函数及加法子群上的定义域约定与分类。
8. 给定一致点子群的全部实函数对分类。

建议先为以上任务记录准确假设、对应章节、预期产出及验收标准，再补充符号验证程序。

## 归档说明

本次按内容分类保存原稿，未修改数学正文。两个原文件《X-算子的性质.pdf》和《X-算子的性质(1).pdf》逐字节相同，仅保留一份；来源映射与哈希均记录在清单中。没有添加许可声明。