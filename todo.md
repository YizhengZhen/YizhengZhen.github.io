## 推荐优先级

### 1. 🔴 最高优先 — 填完 `_tabs/works.md`
这是访问者第二常看的页面（仅次于首页）。你的 publications 页面虽然齐全，但 `works.md` 里的 **Selected Works** 和 **Recent Talks** 是学术主页的门面——就像简历里的 "代表性成果"。你已经有了 `index.html` 里提到的三篇代表作（Science 2026、Nature 2026、arXiv 2025），直接挑 3-5 篇放上去就行。Recent Talks 也至少补 1-2 条。

### 2. 🔴 最高优先 — 填完 `_tabs/research.md`
目前完全是骨架。而你的 `index.html` 已经有四个 Research Focus 卡片（Information Thermodynamics、Quantum Foundations、Quantum Communication、Hybrid Quantum Systems）——直接把那四个作为 research.md 的 **Main Research Topics** 展开写就行。每个写 2-3 句 Background、What we do、Goal，工作量不大但能彻底告别"TBD"。

### 3. 🟡 中等优先 — 填完 `_tabs/activities.md`
学术主页少了活动记录会显得"只有成果没有过程"。你已经有 27 篇论文，一定能挑出参加过的会议（哪怕只有 2-3 个写上）。GitHub Projects 至少可以放个占位（比如 quantum-rss-radar 或其他）。

### 4. 🟡 中等优先 — 首页 "Links" 扩充
目前首页底部只有一条 link (`/works`)。加上 ORCID、Google Scholar、arXiv 的直链会让访问者更快找到你的学术资料——这些你已经在 `works.md` 底部放了，搬到首页也很合理。

### 5. 🟢 较低优先 — 上传 CV PDF
`about.md` 写着 `[PDF CV coming soon]`。如果 CV 还没做好，至少可以去掉这行或者换成 `[Available upon request]`，避免给人"未完成"的感觉。

### 6. 🟢 较低优先 — Google Analytics
在 `_config.yml` 填入 GA ID，可以追踪访问量——对学术主页很有用，但不是内容的"完整度"问题。

### 7. ⚪ 可选 — Notes 页面
`_tabs/notes.md` 完全空白。如果你不打算写非正式笔记，可以考虑直接把这个 tab 从侧边栏隐藏（把 `icon` 那行去掉就行，sidebar.html 的逻辑是 `unless tab.icon` 才 skip）。

---

**总结一句话：先搞定 Works 和 Research 两个页面（大约 80% 的"未完成感"来自这两个），然后清理其他 TBD。**
