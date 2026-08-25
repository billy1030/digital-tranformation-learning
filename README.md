# 數位轉型與 AI 提速實戰全指南 (Digital Transformation & AI Acceleration Hub)

本專案是一套專為企業決策者、架構師、產品經理與工程師設計的 **體系化數位轉型 (DX) 與 AI 智能提速課程**，並配備了原生 **互動式 Web 學習平台**。

---

## 📚 課程目錄結構 (Curriculum Overview)

| 模組編號 | 課程 Markdown 檔案 | 核心內容與主題 |
| :---: | :--- | :--- |
| **00** | [`00-curriculum-overview.md`](./00-curriculum-overview.md) | 課程總綱、全景架構地圖、學習路徑指南 |
| **01** | [`01-what-is-digital-transformation.md`](./01-what-is-digital-transformation.md) | 什麼是數位轉型？3D 演進階梯、PPTD 四大支柱、五大常見迷思 |
| **01.1** | [`01.1-live-examples-and-analogies.md`](./01.1-live-examples-and-analogies.md) | 生活化比喻 (馬車/熱炒店/醫療)、米其林/IKEA/SHEIN 真實案例 |
| **01.2** | [`01.2-pain-points-and-resolutions.md`](./01.2-pain-points-and-resolutions.md) | 轉型常見 8 大真實痛點深入剖析 (員工抗拒、數據孤島、PoC 黑洞) 與實戰解法 |
| **02** | [`02-dx-strategy-and-value-creation.md`](./02-dx-strategy-and-value-creation.md) | 5 步戰略框架、數位成熟度評估 (DMM)、商業模式創新、價值 vs 複雜度矩陣、ROI/OKRs |
| **03** | [`03-modern-tech-and-data-foundation.md`](./03-modern-tech-and-data-foundation.md) | 雲原生演進、API 優先、現代數據棧、Data Mesh (數據網格)、Strangler Fig 絞殺者架構 |
| **04** | [`04-ai-and-agentic-dx-acceleration.md`](./04-ai-and-agentic-dx-acceleration.md) | AI 加速轉型範式、GenAI + RAG + Multi-Agent 自主工作流、各業務職能 10x 提速場景 |
| **05** | [`05-culture-leadership-and-change-management.md`](./05-culture-leadership-and-change-management.md) | 變革管理曲線、ADKAR 模型落地、跨職能 Squad 小組、全員 AI 素養培訓金字塔 |
| **06** | [`06-execution-playbook-and-governance.md`](./06-execution-playbook-and-governance.md) | 4 階段推進法 (PoC ➔ MVP ➔ Scale)、雙軌敏捷交付 (Dual-Track Agile)、三道防線治理架構 |
| **07** | [`07-case-studies-and-anti-patterns.md`](./07-case-studies-and-anti-patterns.md) | 成功案例 (DBS 星展銀行、Dominos 達美樂)、失敗覆盤 (GE Digital、Nike DTC)、十大反模式 |
| **08** | [`08-mastery-and-future-proofing.md`](./08-mastery-and-future-proofing.md) | 組合式企業 (Composable PBCs)、自主企業 (Autonomous Enterprise)、6 維度成熟度自我診斷表 |

---

## 🌐 線上預覽與部署 (GitHub Pages Deployment)

本專案已完全適配 **GitHub Pages**。只要將代碼推送到 GitHub Repo，即可免費獲得一個專屬的線上互動學習網站：

### 🚀 啟用 GitHub Pages 步驟：
1. 將本專案 Push 到你的 GitHub Repository。
2. 進入 GitHub 倉庫的 **Settings ➔ Pages**。
3. 在 **Build and deployment ➔ Source** 中選擇 **`GitHub Actions`**。
4. 每次推送程式碼或新增 Markdown 檔案，GitHub Actions 都會**自動打包並部署**！

---

## 💻 本地運行 (Local Development)

```bash
# 1. 啟動自動同步監聽程式 (新增 .md 時自動打包)
node watch-lessons.js --watch

# 2. 啟動本地靜態伺服器
npx -y serve . -p 3000
```
瀏覽器打開 `http://localhost:3000` 即可訪問。
