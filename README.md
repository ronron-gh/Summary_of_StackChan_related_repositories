# Summary_of_StackChan_related_repositories
今までに登録したｽﾀｯｸﾁｬﾝ関連リポジトリのまとめです。

## 開発環境

| 項目 | 名称 | バージョン |
| --- | --- | --- |
| M5Stack実機 | M5Stack Core2 / CoreS3 |
| 開発用PC | Windows 11 Pro | 21H2 |
| IDE | PlatformIO  |Core 6.1.7 Home 3.4.4 |

ｽﾀｯｸﾁｬﾝはタカオ版キットで動作確認済み。サーボのピン設定を変えれば他のキットにも対応できると思いますが、シリアルサーボは非対応です。

## リポジトリ一覧

| No. | リポジトリ名 | 概要 | 対象M5Stack | M5 Burner | Twitter | ベースリポジトリ |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | [M5CoreS3_CameraTest](https://github.com/ronron-gh/M5CoreS3_CameraTest) | CoreS3の内蔵カメラでキャプチャした画像をLCDに表示するテストプログラム。| CoreS3 | - | - | - |
| 2 | [M5CoreS3_FaceDetect](https://github.com/ronron-gh/M5CoreS3_FaceDetect) | CoreS3の内蔵カメラで顔検出するテストプログラム。| CoreS3 | - | [〇](https://twitter.com/motoh_tw/status/1659731386054606848) | - |
| 3 | [M5CoreS3_FaceRecognition](https://github.com/ronron-gh/M5CoreS3_FaceRecognition) | CoreS3の内蔵カメラで顔検出及び顔認識するテストプログラム。| CoreS3 | - | [〇](https://twitter.com/motoh_tw/status/1662099298002280448) | - |
| 4 | [M5Unified_StackChan_ ChatGPT_Google_CoreS3_ FaceDetectExample](https://github.com/ronron-gh/M5Unified_StackChan_ChatGPT_Google_CoreS3_FaceDetectExample) | robo8080さんのAIｽﾀｯｸﾁｬﾝ(多言語対応)に、顔検出を組み込んだプログラム。| CoreS3 | 〇 | [〇](https://twitter.com/motoh_tw/status/1663206042359169024) | [AIｽﾀｯｸﾁｬﾝ](https://github.com/robo8080/M5Unified_StackChan_ChatGPT_Google) |
| 5 | [AI_StackChan2_DevCam](https://github.com/ronron-gh/AI_StackChan2_DevCam) | robo8080さんのAIｽﾀｯｸﾁｬﾝ2 (VoiceVox)に、顔検出を組み込んだプログラム。| CoreS3 | 〇 | - | [AIｽﾀｯｸﾁｬﾝ2](https://github.com/robo8080/AI_StackChan2) |
| 6 | [AI_StackChan2_FuncCall](https://github.com/ronron-gh/AI_StackChan2_FuncCall) | OpenAIのFunction Callingを使って、robo8080さんのAIｽﾀｯｸﾁｬﾝ2に便利なタイマー機能を追加しました。| Core2 / CoreS3 | - | [〇](https://twitter.com/motoh_tw/status/1675171545533251584) | [AIｽﾀｯｸﾁｬﾝ2](https://github.com/robo8080/AI_StackChan2) |





