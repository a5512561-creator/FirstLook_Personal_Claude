# Specification

## 專案目的
VibeCoding 測試專案，驗證 Python 與 Git 環境正常運作。

## 專案結構
```
FirstLook_Personal_Claude/
├── docs/
│   └── spec.md          # 本規格文件
├── scripts/
│   └── hello_world.py   # Hello World 程式
├── .env                 # 環境設定（不上傳 git）
├── .env.example         # 環境設定範本（公開）
├── .gitignore           # Git 排除清單
└── requirements.txt     # Python 依賴清單
```

## 功能規格
- 執行 `scripts/hello_world.py` 應印出 `Hello World`
- `.env` 放置敏感設定（Git Token 等），不上傳至 GitHub
- `.env.example` 提供設定範本給其他開發者參考

## 環境需求
- Python 3.8+
- Git 2.x+
