# Deep Learning ハンズオン

このリポジトリには、深層学習のハンズオン用サンプルコードが含まれています。

## 📁 ファイル一覧

### YOLOv8物体検出
- **yolov8_object_detection.ipynb**: YOLOv8を使った物体検出のGoogle Colabサンプル

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fwiy0728/dl-hands-on/blob/main/yolov8_object_detection.ipynb)

### MoveNet姿勢推定
- **movenet_pose_estimation.ipynb**: MoveNet Lightningを使った姿勢推定のGoogle Colabサンプル

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fwiy0728/dl-hands-on/blob/main/movenet_pose_estimation.ipynb)

### PIMA Diabetes予測
- **pima_diabetes_prediction.ipynb**: PIMA Indian Diabetes Datasetを使った糖尿病予測のGoogle Colabサンプル

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fwiy0728/dl-hands-on/blob/main/pima_diabetes_prediction.ipynb)

## 🚀 使用方法

### YOLOv8物体検出ノートブック
1. Google Colabで`yolov8_object_detection.ipynb`を開く
2. セルを順番に実行
3. 画像をアップロードして物体検出を実行

### MoveNet姿勢推定ノートブック
1. Google Colabで`movenet_pose_estimation.ipynb`を開く
2. セルを順番に実行
3. 人物が写った画像をアップロードして姿勢推定を実行

### PIMA Diabetes予測ノートブック
1. Google Colabで`pima_diabetes_prediction.ipynb`を開く
2. セルを順番に実行
3. 身体測定データを入力して糖尿病リスクを予測

## 📋 必要な環境
- Python 3.8以上
- Google Colab（推奨）

## 🔧 主な機能

### YOLOv8物体検出
- リアルタイム物体検出
- 80種類のオブジェクト検出対応
- 画像・動画両方に対応
- カスタムデータセットでの訓練サポート

### MoveNet姿勢推定
- 高速なリアルタイム姿勢推定
- 17個のキーポイント検出
- 軽量モデル（Lightning版）
- 信頼度スコア付きの結果

### PIMA Diabetes予測
- 機械学習による糖尿病リスク予測
- 複数アルゴリズムの性能比較
- 特徴量重要度分析
- インタラクティブな予測ツール
- モデルの保存・読み込み機能

## 📖 参考リンク
- [Ultralytics YOLOv8](https://docs.ultralytics.com/)
- [TensorFlow Hub - MoveNet](https://tfhub.dev/google/movenet/singlepose/lightning/4)
- [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Google Colab](https://colab.research.google.com/)

---
Created by shotamaki
