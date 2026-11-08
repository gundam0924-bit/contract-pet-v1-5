# 《契約戰寵》V1.5 — 瀏覽器規格與戰鬥畫面驗收台

> **狀態：工程基底 V0.1；不是已驗收的完整遊戲，也不是正式戰鬥引擎。**

本專案遵守《契約戰寵》V1.5 已核准部分。**不以推測數值替代正式數值，也不將未核准的研究成長曲線寫入正式程式。**

## 可操作功能

- 瀏覽器五分頁：總覽、三種初始戰寵圖鑑、戰鬥畫面視覺演示、規格資料、A／B 驗收。
- 展示 Lv30 基礎面板、初始天賦與技能、一般契約率、已知核准效果。
- 戰鬥演示只檢查移動與視覺效果，**沒有技能 AI、傷害計算、勝負或勝率**。
- 完整規格文字請見 `specs/`、`SPEC_STATUS.md`、`research/`。

## 使用 GitHub Pages（不需要編譯）

將本專案**根目錄所有檔案**上傳至 GitHub 新的公開版本庫；到 `Settings → Pages → Build and deployment` 選 `Deploy from a branch`，再選 `main` 與 `/(root)`，按 `Save`。GitHub Pages 會直接提供 `index.html`。

## 使用 StackBlitz

公開版本庫建立後，前往 `https://stackblitz.com/github/<使用者名稱>/<版本庫名稱>`；StackBlitz 使用 `package.json` 啟動 Vite 預覽。這份專案在 Pages 無需 npm install。

## 版本控管及安全邊界

- 基礎版本：V1.5 設計規格／工程基底 0.1.0。
- 已核准數值：僅能依來源逐條確認後變更。
- 未核准候選：不得轉正或據以調整角色能力。
- 已核准美術不得重新生成相似圖替代；目前介面僅用符號佔位。
- GitHub 版本庫、StackBlitz、GitHub Pages 尚須帳號端建立及啟用，不得聲稱已線上部署。
