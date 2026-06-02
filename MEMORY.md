# Memory Index

- [Karpathy Guidelines Skill Deployment](project_karpathy_skill.md) — karpathy-guidelines skill deployed 2026-05-18; source at `.agents/skills/karpathy-guidelines/`, symlinked in `skills/` and `.claude/skills/`, CLAUDE.md created at workspace root
- [Karpathy Behavioral Guidelines](feedback_karpathy_guidelines.md) — 4 Karpathy rules (Think Before Coding, Simplicity First, Surgical Changes, Goal-Driven Execution) are workspace-level coding standards, auto-loaded via CLAUDE.md every session
- [HTML 設計風格圖鑑 Skills](project_html_design_skills.md) — 40 個島嶼共鳴 2026 設計 Skills 已部署至 ~/.claude/skills/；html-style-picker 提供互動風格選單；產出 HTML 前先觸發選擇器
- [Apify Agent Skills 部署](project_apify_skills.md) — 11 個 Apify v1.6.1 skills 於 2026-05-21 部署至 ~/.claude/skills/；涵蓋爬蟲/行銷情報/電商；需 APIFY_TOKEN
- [HTML 輸出格式確認規則](feedback_html_output_format.md) — 產出任何 HTML 前必問：標準動態SVG / 互動式SVG / open-slide 三選一，不可省略
- [Computer Vision Projects Skill](project_cv_skill.md) — 75 個 CV 子專案部署於 skills/computer-vision-projects/；skill 在 ~/.claude/skills/computer-vision-project.md；安裝腳本 scripts/setup/install_cv_projects.py
- [Codex Repair Toolkit](project_codex_repair.md) — codex-repair v1.0.0 部署於 ~/.claude/tools/codex-repair/；skill 在 ~/.claude/skills/codex-repair.md；修復 Codex 0.131 SQLite 啟動 Bug
- [3D_CAD CAD Skills Project](project_3d_cad.md) — earthtojake/text-to-cad 部署於 Antigravity WorkSpace/3D_CAD/；7 個 skills (cad/render/urdf/sdf/srdf/step-parts/sendcutsend) 在 ~/.claude/skills/cad*.md；需 Python 3.12 for build123d
- [三層式思考架構](feedback_three_layer_thinking.md) — 導入 Claude Code 三層思考邏輯：解構 $\rightarrow$ 推演 $\rightarrow$ 極簡實作，結合 SPARC 與 Karpathy 準則
- [低熵上下文流水線](low-entropy-context-pipeline.md) — L1-L3 三層管理架構 (Prefix/Compaction/Memory)
- [前綴穩定化標準](prompt-prefix-standard.md) — 嚴格的 Prompt 組裝順序以最大化 KV Cache 命中率
- [狀態保留壓縮策略](compaction-state-preservation.md) — Context 壓縮時保留 State-Vector 而非全文本摘要
- [結構化記憶儲存](structured-memory-store.md) — 採用 K-V Markdown 文件的長期記憶實現
