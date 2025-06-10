# 量子計算アプリケーション ハンズオン教材

このリポジトリは、授業「量子計算アプリケーション」のためのハンズオン教材です。

## 概要

本教材は、量子計算アプリケーションの授業内容を、実際にコードを動かしながら学べるように設計されています。
各章はJupyter Notebookで構成されており、理論と実践をバランスよく学習できることを目指しています。

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

## 使用ライブラリ

本教材では主に以下のライブラリを使用します：

- NumPy, Matplotlib, Jupyter: 科学計算と可視化の基本ツール

## 参考文献

- Nielsen & Chuang "Quantum Computation and Quantum Information"

## ライセンス

本教材の著作権はQIQBに所属します。

## 貢献

バグ報告、改善提案、プルリクエストを歓迎します。詳細は[CONTRIBUTING.md](CONTRIBUTING.md)をご覧ください。

## 謝辞

本教材の作成にあたり、[Qulacs-Osaka/quantum_software_handson](https://github.com/Qulacs-Osaka/quantum_software_handson)を参考にさせていただきました。
