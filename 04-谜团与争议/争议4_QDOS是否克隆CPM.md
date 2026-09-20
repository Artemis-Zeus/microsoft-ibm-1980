# 争议 #4 考辨：QDOS 是否「克隆」了 CP/M？

> 状态：**已考订**（2026-09-20 研究轮）｜总清单：[争议清单.md](争议清单.md)

## 一、争论的谱系

- 指控侧：流行叙事长期称 QDOS 为 CP/M 的「换皮抄袭」；Evans《They Made America》（2004）定性为 "slapdash clone"（草率拼凑的复制品）。
- 辩护侧：Paterson 涉案反驳；因该书提起诽谤诉讼——2007-08 开审前被驳回（法官认定他为 limited purpose public figure、涉诉表述属受保护意见）。【WikiPaterson】
- 技术中立侧：OS/2 Museum 反汇编分析（2012）——86-DOS BDOS 大量使用 8086 特有指令（字符串指令/LOOP），无 8080 对应物；磁盘格式与 CP/M 完全不兼容；结论「zero evidence that 86-DOS (or MS-DOS) infringed on Digital Research's copyright in any way」。【OS2Museum12】

## 二、Paterson 的完整立场（自辩+坦承）

- 坦承接口承继：「DOS implements the same Application Program Interface (API) as CP/M.」设计目标即「翻译兼容」；方法论「第一步，写下 CP/M-80 都做了什么」。
- 坚决否认代码承继：「To this day, I have never seen any CP/M code.」
- 动机的坦白：「I've always hated CP/M and thought I could do it a lot better.」
- 商业误判的坦白：「No one ever used or cared about translation compatibility. I had been wrong.」
- 对 CP/M 的承认：「CP/M was the first general-purpose operating system for 8-bit computers… DOS was built on this general groundwork.」【Drivel】

## 三、事实层（多源可硬化）

1. 参考物是**公开出版物**：DRI 的 CP/M 手册/1976 Interface Guide（Paterson 1976 年花 $5 买的 CP/M 手册是他本人的说法）。⚠ 注意：「SCP 持有 CP/M 使用许可」一说**未获一手证实**，不可引。【Softalk83】【Wiki86】
2. 文件系统来自微软血统：FAT（Marc McDonald 构想）而非 CP/M 的文件系统；DRI 曾主动接洽 SCP 欲移植 CP/M 未果——86-DOS 诞生前 DRI 自己错过了这个位置。【Drivel】【Softalk83】
3. 代码独立性的技术证据：OS2Museum12。
4. 讽刺的回旋：IBM 要求 CP/M 风格提示符——「IBM wanted CP/M prompts. It made me throw up.」最终产品「长得更像 CP/M」是 IBM 的要求。【Softalk83】
5. Kildall 一侧的反应：顾问 Johnson-Laird 指出 PC DOS 与 CP/M 高度相似，Kildall 确认后一度威胁起诉；1981-07-21 对质的结果是 IBM 同意同时销售 CP/M-86（商业安排，非著作权认定）。【Evans04转引】

## 四、本库的结论

> 「QDOS 抄袭 CP/M」在**著作权意义上不成立**（无代码承继，技术鉴定与法院结果一致）；在**产业伦理意义上部分成立**（API 兼容是刻意设计，86-DOS 得以站上 CP/M 现成的应用生态）。准确表述是 Paterson 自己给的那句：**接口是 CP/M 的，代码是自己的，生态位置是抢来的**。而「谁该为这场替代负责」的问题，答案一半在 DRI 自己拖延的 CP/M-86，一半在 IBM 的价差——见 [争议#1](争议1_Kildall是否错过会面.md)。
>
> 证据链：[2007_Paterson博客自辩.md](../02-史料摘录/2007_Paterson博客自辩.md)｜[1983_Softalk_RootsOfDOS.md](../02-史料摘录/1983_Softalk_RootsOfDOS.md)｜[2004_TheyMadeAmerica.md](../02-史料摘录/2004_TheyMadeAmerica.md)｜[2026_微软公开DOS源码清单.md](../02-史料摘录/2026_微软公开DOS源码清单.md)

## 五、待解清单

- BYTE 1983-06《An Inside Look at MS-DOS》原文；86-DOS 与 CP/M 系统调用的逐条对照表（可做成本库的技术附录）。
