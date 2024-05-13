# Dataset說明
為了可以更快且低成本地針對特定空對地通訊進行建模，並快速開發相關通訊應用之原型(Prototype)，本團隊使用了開源的軟體對交大校園環境的通訊進行光線追蹤(Ray-tracing)進行高精度的模擬並生成資料集。
資料集內容描述如下表：
| Contents         | Description                                         |
|------------------|-----------------------------------------------------|
| Tx_x             | X coordinate of Tx (m)                              |
| Tx_y             | Y coordinate of Tx (m)                              |
| Tx_z             | Z coordinate of Tx (m)                              |
| Rx_x             | X coordinate of Rx (m)                              |
| Rx_y             | Y coordinate of Rx (m)                              |
| Rx_z             | Z coordinate of Rx (m)                              |
| Distance         | Distance between Tx and Rx (m)                     |
| Elevation angle  | Elevation angle between Tx and Rx (°)              |
| Frequency        | Radio frequency (GHz)                              |
| LOS flag         | LOS flag (1: LOS, 0: nLOS)                         |
| Path loss        | Path loss (dB)                                     |
