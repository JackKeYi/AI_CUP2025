# AI_CUP2025
## 專案架構
CardiacSegV2/
├─ data_utils/           # 資料載入、前處理與視覺化工具
├─ datasets/             # 各醫療資料集的包裝類別
├─ expers/               # 訓練/推論腳本與參數設定
├─ exps/                 # 實驗紀錄與設定（JSON、Notebook）
├─ images/               # README 相關示意圖
├─ losses/               # 損失函數實作
├─ networks/             # 模型架構與組件
├─ optimizers/           # 最佳化器與學習率策略
├─ runners/              # 訓練/驗證/測試執行流程
├─ transforms/           # MONAI 風格的資料增強流程
├─ download_data.py      # 資料下載腳本
├─ requirements.txt      # 專案依賴
└─ README.md             # 專案說明
### C:\Users\User\Desktop\AI_CUP\CardiacSegV2\networks\network.py 有模型種類
### args.tune_mode == 'optim' 可以測試不同學習率
### C:\Users\User\Desktop\AI_CUP\CardiacSegV2\exps\data_dicts\chgh\AICUP_training.json 資料集劃分
### 問題 好像沒有用到全部資料集
### 可以學習optuna
### 可以更換模型試試