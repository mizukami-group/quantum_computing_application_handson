# 量子計算アプリケーション ハンズオン教材

このリポジトリは、授業「量子計算アプリケーション」のためのハンズオン教材です。QURI Partsを使用して量子計算アプリケーションを学びます。

## 概要

本教材は、量子計算アプリケーションの授業内容を、実際にコードを動かしながら学べるように設計されています。
各章はJupyter Notebookで構成されており、理論と実践をバランスよく学習できることを目指しています。

[QURI Parts](https://quri-parts.qunasys.com/)は、量子アルゴリズムの研究・開発のための統合的なオープンソースライブラリです。

## 環境構築

### 方法1: Google Colabを使用（最も簡単）

教材の各ノートブックにあるColabバッジをクリックするだけで、Googleアカウントがあればすぐに実行できます。
各ノートブックの最初のセルでQURI Partsが自動的にインストールされます。

### 方法2: MyBinderを使用（インストール不要）

以下のバッジをクリックすることで、ブラウザ上で即座に実行環境を構築できます：

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mizukami-group/quantum_computing_application_handson/main)

### 方法3: ローカル環境での実行

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

## 教材へのアクセス

### 最初のノートブック

QURI Partsの基本的な使い方を学ぶ最初のノートブックはこちらです：

| ノートブック | 内容 | Colab | MyBinder |
|------------|------|-------|----------|
| [01_quri_parts_introduction.ipynb](doc/source/notebooks/01_quri_parts_introduction.ipynb) | QURI Parts入門 - 量子回路と量子状態の基礎 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mizukami-group/quantum_computing_application_handson/blob/main/doc/source/notebooks/01_quri_parts_introduction.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mizukami-group/quantum_computing_application_handson/main?labpath=doc%2Fsource%2Fnotebooks%2F01_quri_parts_introduction.ipynb) |

## 教材の構成（予定）

教材は以下のような構成になっています（今後追加予定）：

### 第1章: QURI Partsと量子計算の基礎
- 量子ビットとゲート操作
- 量子回路の構築

## 使用ライブラリ

本教材では主に以下のライブラリを使用します：

- [QURI Parts](https://quri-parts.qunasys.com/): 量子アルゴリズム開発のための統合ライブラリ
- [Qulacs](https://github.com/qulacs/qulacs): 高速な量子回路シミュレータ（QURI Partsのバックエンド）
- [Mitiq](https://mitiq.readthedocs.io/): 量子エラー緩和ライブラリ
- [OpenFermion](https://quantumai.google/openfermion): 量子化学計算ライブラリ
- NumPy, Matplotlib, Jupyter: 科学計算と可視化の基本ツール

## 参考文献

- [QURI Parts Documentation](https://quri-parts.qunasys.com/)
- [QURI Parts Tutorials](https://quri-parts.qunasys.com/tutorials/)
- Nielsen & Chuang "Quantum Computation and Quantum Information"

## ライセンス

本教材の著作権はQIQBに所属します。

## 貢献

バグ報告、改善提案、プルリクエストを歓迎します。詳細は[CONTRIBUTING.md](CONTRIBUTING.md)をご覧ください。

## 謝辞

本教材の作成にあたり、[Qulacs-Osaka/quantum_software_handson](https://github.com/Qulacs-Osaka/quantum_software_handson)を参考にさせていただきました。
