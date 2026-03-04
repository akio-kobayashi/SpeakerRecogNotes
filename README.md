# SpeakerRecogNotes

話者識別のための学習ノートブック一式です。
このノートブックは、Google Colab で実行することを想定しています。

## ノートブック一覧

- **[01_data_prepare.ipynb](https://colab.research.google.com/github/akio-kobayashi/SpeakerRecogNotes/blob/main/01_data_prepare.ipynb)**: データの準備（Google Drive上の音声データから学習用のCSVファイルを作成）
- **[01_speaker_recognition.ipynb](https://colab.research.google.com/github/akio-kobayashi/SpeakerRecogNotes/blob/main/01_speaker_recognition.ipynb)**: 話者識別モデルの学習、評価、推論（Lightning 2.0+ 対応済み）

## 依存リポジトリ
このノートブックは学習・推論のバックエンドとして [SpeakerClassify](https://github.com/akio-kobayashi/SpeakerClassify) を使用します。
