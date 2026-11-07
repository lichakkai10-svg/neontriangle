# core28a · 行車廊 vs 櫃堆鎖（boss-p0）

- **L1** centerline ±**6.75 GU** 零櫃堆
- **L0** corridor ±**6.0 GU** 零櫃堆
- **閘 keepout** r=20 m ≈ **30 GU**（bake 閘 A/B／序章錨）
- 櫃堆只准 `yard_kc`／`crane_strip_kc`（hub：東岸 x≥12 或西廂 x∈[-110,-40]）
- 執行：`kwRejectStackOnDriveable(lx,lz)`（`index.html`）
- bake 閘：A (−1513.4,−3018.7)／B (−1312.7,−2156.2)／prologue (−1776,−2736.7)
- 對齊：`data/core28a-kwai-driveable-vs-stack-locks.json`、`data/core28a-kwai-terminal-hkgeo-bake.json`
- 唔升 `?v=`
