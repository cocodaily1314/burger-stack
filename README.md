# 漢堡疊疊樂 🍔

左右移動底盤，靠眼力接住跌落嘅材料，限時疊出完美漢堡。每局材料池會洗牌。畫面用 three.js 立體渲染底包、頂包同各種 topping（燈光 + soft shadows）。

## 點玩
1. 用瀏覽器打開 [GitHub Pages](https://cocodaily1314.github.io/burger-stack/) 或本地 `index.html`（毋須安裝／build；需可連 CDN 載入 three.js）
2. 點「開始疊漢堡」
3. 拖曳、撳左／右半邊，或用方向鍵 ← → 移動底盤
4. **冇度位指示**——全靠眼力對齊；頂部有倒數時間 bar，時間到即完場
5. 疊到頂包就完場；對齊太差會散枱
6. 主廚／傳說廚神頭銜極罕有——速度快、時間緊、評分嚴

## 評分標準
落地時以水平重疊％計分：完美置中加分，突出部分會削窄下一層寬度；重疊不足即散枱出局。畫面唔會顯示對齊輔助線。

## 點分享
完場後撳「下載結果圖」儲存結果卡（含總分、層數、對齊、完美次數、Run ID、時間戳），再分享挑戰朋友。

## 點開
直接雙擊或：
```bash
python3 -m http.server 8080
# 開 http://localhost:8080
```

Playable: https://cocodaily1314.github.io/burger-stack/
