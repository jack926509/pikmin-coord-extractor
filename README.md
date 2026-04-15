# 皮克敏座標擷取器

專為 Telegram 皮克敏報菇群設計的座標擷取工具。貼上頻道訊息，自動解析座標，點一下即複製。

🔗 **線上使用**：[https://jack926509.github.io/pikmin-coord-extractor](https://jack926509.github.io/pikmin-coord-extractor)

---

## 功能

- 一次貼上多筆訊息，自動擷取全部座標
- 點任意位置即複製單筆座標，不需拉選文字
- 「複製全部」一鍵取得所有座標（換行分隔）
- 自動顯示地點名稱方便對照
- 支援負數座標（如紐西蘭、美國）
- `Ctrl + Enter` 快速觸發擷取

---

## 支援訊息格式

```
1. (紐西蘭) Albert-EdenGreenlane
• 座標：-36.891357,174.795049
• 這裡自飛可進，而且無邀。
• 建議：中高優先

2. (美国) Rochester
• 座標：44.021698,-92.460725
• 這是活動菇，還有 2 個免券位，自飛可進。
• 建議：高優先
```

---

## 使用方式

### 線上版（推薦）

直接開啟上方連結，無需安裝。

### 本機版

```bash
git clone https://github.com/jack926509/pikmin-coord-extractor.git
cd pikmin-coord-extractor
# 用瀏覽器開啟 index.html 即可
open index.html
```

---

## 部署到 GitHub Pages

1. 將此 repo fork 或 clone 到自己帳號
2. 進入 repo 的 **Settings → Pages**
3. Source 選擇 `Deploy from a branch`，Branch 選 `main`，資料夾選 `/ (root)`
4. 儲存後等約 1 分鐘，即可透過 `https://<你的帳號>.github.io/<repo名稱>` 存取

---

## 檔案結構

```
pikmin-coord-extractor/
├── index.html   # 主程式（單一檔案，無外部依賴）
└── README.md    # 說明文件
```

---

## 授權

MIT License
