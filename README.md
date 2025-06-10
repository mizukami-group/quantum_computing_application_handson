# 量子計算アプリケーション ハンズオン教材

このリポジトリは、量子計算アプリケーションを学ぶためのハンズオン教材です。

## 概要

本教材は、量子コンピュータの基礎から応用まで、実際にコードを動かしながら学べるように設計されています。各章はJupyter Notebookで構成されており、理論と実践をバランスよく学習できます。

## 環境構築

### 方法1: MyBinderを使用（推奨）

以下のバッジをクリックすることで、ブラウザ上で即座に実行環境を構築できます：

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mizukami-group/quantum_computing_application_handson/main)

### 方法2: ローカル環境での実行

1. リポジトリをクローン
```bash
git clone https://github.com/mizukami-group/quantum_computing_application_handson.git
cd quantum_computing_application_handson
```

2. Python環境の構築（Python 3.8以上推奨）
```bash
python -m venv venv
source venv/bin/activate  # Windows の場合: venv\Scripts\activate
```

3. 必要なパッケージのインストール
```bash
pip install -r requirements.txt
```

4. Jupyter Notebookの起動
```bash
jupyter notebook
```

## 教材の構成

教材は以下のような構成になっています（今後追加予定）：

### 第1章: 量子計算の基礎
- 量子ビットとゲート操作
- 量子回路の構築
- 測定と観測

### 第2章: 量子アルゴリズムの基礎
- 量子フーリエ変換
- グローバーのアルゴリズム
- 変分量子アルゴリズム（VQE）

### 第3章: 量子機械学習
- 量子カーネル法
- 量子ニューラルネットワーク

### 第4章: 量子化学計算への応用
- 分子の基底状態計算
- 励起状態の計算

### 第5章: 量子誤り訂正
- ノイズモデル
- エラー緩和技術

## 使用ライブラリ

本教材では主に以下のライブラリを使用します：

- [Qulacs](https://github.com/qulacs/qulacs): 高速な量子回路シミュレータ
- [QulacsVis](https://github.com/qulacs/qulacs-visualizer): 量子状態の可視化ツール
- NumPy, Matplotlib, Jupyter: 科学計算と可視化の基本ツール

## 参考文献

- [Qulacs Documentation](http://docs.qulacs.org/)
- Nielsen & Chuang "Quantum Computation and Quantum Information"
- 藤井啓祐 "量子コンピュータによる機械学習"

## ライセンス

本教材はMITライセンスの下で公開されています。

## 貢献

バグ報告、改善提案、プルリクエストを歓迎します。詳細は[CONTRIBUTING.md](CONTRIBUTING.md)をご覧ください。

## 謝辞

本教材の作成にあたり、[Qulacs-Osaka/quantum_software_handson](https://github.com/Qulacs-Osaka/quantum_software_handson)を参考にさせていただきました。