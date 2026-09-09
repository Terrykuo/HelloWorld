# HelloWorld

一個使用 SwiftUI 建立的基礎 iOS Hello World 範例專案。

## 專案簡介

`HelloTest` 是一個最簡單的 SwiftUI App，畫面上顯示一個地球圖示與 "Hello, world!" 文字，作為學習與練習 SwiftUI 專案結構的起點。

## 環境需求

- Xcode 14 以上
- iOS 16.1 以上（Deployment Target）
- Swift 5.0

## 專案結構

```
HelloTest/
├── HelloTest.xcodeproj        # Xcode 專案檔
├── HelloTest/                 # App 主程式
│   ├── HelloTestApp.swift     # App 進入點
│   ├── ContentView.swift      # 主畫面
│   └── Assets.xcassets        # 圖片與顏色資源
├── HelloTestTests/             # 單元測試
└── HelloTestUITests/           # UI 測試
```

## 如何執行

1. 使用 Xcode 開啟 `HelloTest/HelloTest.xcodeproj`
2. 選擇模擬器或實機裝置
3. 點擊 Run（`Cmd + R`）即可啟動 App
