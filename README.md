# Tarot App · 私用塔羅抽牌工作台

設下問題,洗牌,讓牌陣回答你。這是一個抽牌工具,不是占卜——把牌當作思考鏡面。

## 🔗 Live Demo

**<https://tarot-app-five-umber.vercel.app/>**

## 功能特色

- **自訂牌陣**:自由新增、編輯、刪除牌陣位置,或直接套用內建範例牌陣:
  - 單張指引(1 張)
  - 時間三張:過去/現在/未來(3 張)
  - 心智三張:想法/感受/行動(3 張)
  - 決策五張(5 張)
  - 凱爾特十字(10 張)
- **牌池範圍**:完整 78 張、大阿爾克那 22 張、小阿爾克那 56 張三種模式
- **逆位開關**:可選擇是否包含逆位(50% 機率)
- **加密安全亂數**:使用 `crypto.getRandomValues` 進行 Fisher–Yates 洗牌與逆位擲幣
- **匯出 AI 解讀 Prompt**:抽牌後一鍵將問題、牌陣設定、抽牌結果與解讀指示組成 prompt 複製到剪貼簿,拿去問 Claude/Gemini 解讀

## 技術棧

- [React 19](https://react.dev/)
- [Vite 8](https://vite.dev/)
- 部署於 [Vercel](https://vercel.com/)

## 本地開發

```bash
# 安裝依賴
npm install

# 啟動開發伺服器
npm run dev

# 建置正式版本
npm run build

# 預覽建置結果
npm run preview

# 執行 ESLint
npm run lint
```
