# FamilyTrust 鏈上信託前端

| 頁面 | 說明 |
|---|---|
| `index.html` | v2 控制台：總覽、三個角色工作台、現金流、承購定價、帳簿、規則、設定 |
| `v3.html` | v3：加上家族多簽（Safe）偵測、受益人資料分享、受益人財務紀錄 |
| `v4.html` | v4：配合可升級合約 FamilyTrustV2，加上支付（信託直付、收款方核可）與做市商（收購報價、轉售、轉讓） |
| `legacy.html` | 原本的前端（含一鍵部署） |
| `DESIGN.md` | 介面設計規範 |
| `contracts/RecordConsent.sol` | 受益人授權查詢合約（v3、v4 用，獨立部署） |
| `contracts/FamilyTrustV2.sol` | 可升級信託合約（UUPS），v4 用 |

網址加 `?trust=0x…` 載入合約，加 `?demo=1` 看示範資料。

**Remix 部署合約：見 [DEPLOY.md](DEPLOY.md)。**
