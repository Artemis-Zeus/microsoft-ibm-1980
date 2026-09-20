# Paterson 博客自辩（Dos Man Drivel，2007）

## 基本信息

- **题名**：Tim Paterson 博客文章四篇：《Is DOS a Rip-Off of CP/M?》（2007-08-08）、《The Contributions of CP/M》（2007-08-17）、《The Design of DOS》（2007-09-30）、《The First DOS Machine》（2007-11-24）；另《Paul Allen and I》（2011-08-02）
- **类型**：博客（当事人第一人称；多因 Evans 书引发的诉讼期而写）

## 来源与收藏

- **出处**：https://dosmandrivel.blogspot.com/2007/08/is-dos-rip-off-of-cpm.html 等
- **查见日期**：2026-09-20（逐篇核读）

## 内容摘录（关键原句）

- 「There is no suggestion that I copied any CP/M code when I wrote DOS. (To this day, I have never seen any CP/M code.)」
- 「DOS implements the same Application Program Interface (API) as CP/M.」——坦承接口层兼容。
- 「So I made CP/M translation compatibility a fundamental design goal.」（设计目标即翻译兼容）
- 「Step one was to write down what CP/M-80 did. Step two was to design a file system that was fast and efficient.」
- 「No one ever used or cared about translation compatibility. I had been wrong to think it was a valuable feature.」——坦承商业上判断失误。
- 对 CP/M 的贡献：「Gary Kildall's CP/M was the first general-purpose operating system (OS) for 8-bit computers… DOS was built on this general groundwork.」但又说他「can think of no specific technical innovations demonstrated by CP/M」。
- 起因与假设：「At one point we were expecting it [CP/M-86] to be available at the end of 1979. Had it made its debut at any time before DOS was working, the DOS project would have been dropped.」/「SCP wanted to be a hardware company, not a software company.」
- 「Paul Allen and I」：吐槽艾伦回忆录拼错其姓氏——二手文献最常见笔误的当事人勘误。

## 提要与备注

- **价值**：与 Softalk83 逐条互证的第二代自述；坦承与辩护并存，可信度高。
- **局限**：诉讼期的自辩立场；技术细节与商业动机需分开评估。
- **佐证**：OS/2 Museum 反汇编分析——86-DOS BDOS 大量使用 8086 特有指令、无 8080 对应物、磁盘格式与 CP/M 完全不兼容，「zero evidence that 86-DOS (or MS-DOS) infringed on Digital Research's copyright in any way」。【OS2Museum12】
- **关联**：[争议#4](../04-谜团与争议/争议4_QDOS是否克隆CPM.md)
