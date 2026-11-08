# Concrete-Strength-Statistical-Analysis
Statistical analysis of the relationships between concrete mix composition, curing age, and compressive strength using Python.

## 1. 研究目的（Objective）

本プロジェクトでは、Pythonを用いて、コンクリートの材料配合条件および養生期間と圧縮強度の関係を統計的に分析する。

探索的データ解析、相関分析、重回帰分析を実施し、各説明変数と圧縮強度との関連を検討する。

また、多重共線性、残差の分布、異分散性などのモデル診断を行い、統計解析結果の妥当性および限界について考察する。

## 2. 使用データ（Dataset）

**Dataset**: Concrete Compressive Strength

**Source**: UCI Machine Learning Repository（Kaggle経由）

**Number of observations**: 1,030

**Number of variables**: 9（説明変数8、目的変数1）

本データセットには、コンクリートの材料配合条件、養生期間および圧縮強度の測定値が含まれている。

## 3. 使用技術（Tools）
Python
- pandas：データの読み込み、前処理、集計
- NumPy：数値計算、変数変換
- Matplotlib：データの可視化
- SciPy：相関分析
- statsmodels：重回帰分析、VIF、Breusch–Pagan検定、HC3ロバスト標準誤差
- Jupyter Notebook：解析コードおよび結果の記録
