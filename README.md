# Moge800

工場内の設備・運用に近いところで、Pythonを中心に日常業務や現場改善に使える小さなツールを作っています。  
主な関心領域は **PLC / IoT / 画像処理 / OCR / LLMバックエンド / 運用自動化** です。

## Focus

- Raspberry Pi / Pico / M5Stackを使った小型デバイス向けアプリケーション
- Pico / M5Stackを使ったPLC連携・遠隔操作まわりの組み込み制御
- PLC / MC Protocol まわりの通信ツール
- 工場内の記録、監視、検査、遠隔操作を支える現場向けツール
- カメラ、異常検知、画像処理まわりの検証と実装
- OCR、検索、API化などのバックエンド
- 運用を楽にする自動化ツール

## Selected Work

公開しているものの中から、最近触っている領域に近いものを中心に載せています。

- **PLC / Factory Automation**
  - [gomcprotocol](https://github.com/Moge800/gomcprotocol)  
    三菱電機PLCのMC Protocol通信を扱うGoライブラリ
  - [gomc-rest](https://github.com/Moge800/gomc-rest)  
    MC Protocol通信をHTTP APIとして扱うためのRESTサーバー
  - [micromcprotocol](https://github.com/Moge800/micromcprotocol)  
    ESP32 / Raspberry Pi Pico W向けの軽量MC Protocolクライアント
  - [plc_trigger_recorder](https://github.com/Moge800/plc_trigger_recorder) / [plc_trigger_cam](https://github.com/Moge800/plc_trigger_cam)  
    PLCのビット変化をトリガーに、カメラ録画・撮影を行うGUIツール

- **Vision / Inspection**
  - [PatchcoreBackend](https://github.com/Moge800/PatchcoreBackend) / [patchcore-inspection](https://github.com/Moge800/patchcore-inspection)  
    PatchCore系の異常検知バックエンドと検証用ツール
  - [yolox_wrapper](https://github.com/Moge800/yolox_wrapper)  
    YOLOXまわりの検証・利用をしやすくするためのラッパー

- **Search / OCR / LLM Backend**
  - [faiss-knowledge-search](https://github.com/Moge800/faiss-knowledge-search)  
    FAISSベースのナレッジ検索
  - [ocr_web_api](https://github.com/Moge800/ocr_web_api)  
    OCR処理をWeb APIとして扱うためのバックエンド
  - [llm_query_backend](https://github.com/Moge800/llm_query_backend) / [llm_backend](https://github.com/Moge800/llm_backend)  
    LLM連携まわりのバックエンド実装

## Current Interests

- Discord / OpenClaw まわりの運用整備
- 現場寄りツールを使いやすく残せる形に整えること
- プロトタイプを継続して使える形に整えること

## Tech Stack

- **Main**: Python
- **Device / Embedded**: MicroPython, C++
- **Also exploring**: Go, Rust, C#, JavaScript
- **Platform**: Linux, Raspberry Pi, Raspberry Pi Pico, M5Stack, self-hosted

## Notes

各リポジトリの説明文やREADMEを少しずつ整理しています。  
気になるものがあれば、IssueやDiscussionで声をかけてもらえるとうれしいです。
