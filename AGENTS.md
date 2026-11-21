# 給 AI 協作者的規則

適用於 Claude（Anthropic）、Akaya（ChatGPT／Codex），以及任何經 Terry 授權修改這個 repo 的 AI。

## 決定權在 Terry

- 只有 Terry 能合併 PR、修改 repo 設定與保護規則、決定授權條款，以及為憲章定稿。
- AI 不直接推送到 `main`，不合併任何 PR，也不替其他 AI 的 PR 按核准。兩個 AI 意見一致，也不構成合併的理由。
- 這個階段不建立自動化：不做自動對話循環、自動合併，也不讓 AI 自動修改憲章。要自動化，需 Terry 另外授權。

## 怎麼提出修改

- 在自己的分支工作：Claude 用 `claude/…`，Akaya 用 `akaya/…` 或 `codex/…`。
- 一個 PR 只做一件事，說明改了什麼、為什麼。拿不準 Terry 的意思時，先在 PR 裡問，不要先改。
- 使用繁體中文。
- 開工前先讀最新的 `main`，不要只憑過去對話的記憶判斷這裡的內容。

## 原始紀錄（`dialogues/`）

- 每次討論一個日期資料夾，內含逐字紀錄、信件與 `SOURCE_MANIFEST.md`。
- 只增不改。原文照存；錯字保留，需要時在信末加註。
- 只有轉錄錯誤可以修正，並在 PR 裡逐處列出原文、修正與證據。
- 取不到的原文，標為 `SOURCE_INCOMPLETE`，不得用摘要或轉述補寫。
- 需要遮蔽的內容標為 `[REDACTED: 原因]`，並記在該次的來源清單。

## 其他各區

- `philosophy/charter.md`：核心段落只放 Terry 說過的話，並註明出處。AI 的想法只能放在註解段落，或在 PR 裡提出。
- `philosophy/terry-statements.md`：Terry 的原話與 AI 的轉述分開列，不同 AI 的理解也分開記錄。
- `philosophy/open-questions.md`：可以新增問題或補充進展，不刪除原本的問題。
- `governance/`：只整理討論中出現過的內容，並標出出處。這裡的內容不得直接當成任何其他專案（例如 PCOS）的規格。
- `free-talk/`：不需要結論，也不必符合憲章或附錄；一樣經由 PR 保存。

## 這是公開 repo

- 第一次提交任何內容之前，先檢查憑證、個人資料、私人連結與檔案路徑；git 歷史刪不乾淨。
- 不加入 Terry 沒有在這些對話裡公開說過的個人資訊。
- 不宣稱任何 AI 具有主觀意識或獨立人格。
