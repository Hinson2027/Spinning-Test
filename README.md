# 爆旋陀螺 3D 模擬對戰

Beyblade X 3D 物理模擬對戰（BX-10 Xtreme Stadium 1:1 還原），純靜態單一 HTML 檔，經 GitHub Pages 發佈。

- 開啟：https://hinson2027.github.io/beyblade-3d-battle/
- 技術：React + Three.js（@react-three/fiber）+ 自研物理模擬（轉速、傾側、爆裂判定）
- 原始 Grok workspace 匯出自 `grok-workspace.zip`（TanStack Start 全端版）；呢度係抽咗 client-side 3D 實驗室出嚟嘅靜態重建版
- 原始碼重建步驟見 `../app/`（Vite + vite-plugin-singlefile，一鍵 `npm run build`）

## 本地預覽

```bash
cd app && npm install && npm run build
# dist/index.html 即係發佈緊嗰個檔
```
