# 行人素材第一批（生成草稿）

生成方式：ChatGPT 內建 image_gen；本次未修改網站程式。

4 個角色、每人 toward / away 兩個方向。每張圖為 4 欄 × 3 列，共 12 個姿勢，從左至右、從上至下排列。共 8 張圖表、96 個姿勢格；尚未拆為 96 張獨立 PNG。

角色：
- man-coat：深色長外套男子、靛藍傘。
- woman-backpack：短髮女子、橄欖綠短外套、棕色背包、酒紅傘。
- woman-trench：低馬尾女子、灰褐風衣、灰藍傘。
- man-jacket：眼鏡男子、海軍藍夾克、棕色長褲、綠傘。

## 檢查結果與限制

這批是生成草稿，不是已驗收的循環動畫。姿勢有重複、步幅與基準位置尚不完全一致，需逐格校正及試播。部分傘尖接近畫布邊緣，拆圖前需檢查裁切。

以下檔案沒有 alpha，棋盤格已烘焙入圖片，不能直接當透明素材使用：
- man-coat-away.png（已嘗試透過生圖去背一次，仍未成功）
- woman-trench-away.png
- man-jacket-away.png

其餘 5 張檔案有 alpha，但邊緣雜色、透明殘留仍需檢查。不要只憑棋盤格外觀認定透明。

## 提示詞規格

每位角色均使用：photorealistic cinematic rainy Kyoto night, subtle amber left rim and cool blue fill; exactly 12 chronological walk-cycle frames in uniform 4 columns by 3 rows; consistent identity, clothing, umbrella, camera, scale and foot baseline; complete alternating left/right contact-down-passing-up cycle; full umbrella and shoes with padding; genuine transparent alpha PNG, no backdrop, no floor, no text.

各正面圖依上列角色服裝生成，背面圖以對應正面圖作為參考，要求 same character, back view walking away, preserve costume and lighting。具體生成提示詞可在本對話各次生圖呼叫中查看。
