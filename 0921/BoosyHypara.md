# 各Boostingアルゴリズムのハイパーパラメータチューニングまとめ

## パラメータチューニング一般論
https://qiita.com/c60evaporator/items/ca7eb70e1508d2ba5359#23-%E3%83%91%E3%83%A9%E3%83%A1%E3%83%BC%E3%82%BF%E3%81%AE%E7%B5%84%E5%90%88%E3%81%9B%E3%82%92%E9%81%B8%E6%8A%9E

## lightgbm
- General
https://qiita.com/c60evaporator/items/351188110f328ff921b9
- LightgbmTuner 公式
https://tech.preferred.jp/ja/blog/hyperparameter-tuning-with-optuna-integration-lightgbm-tuner/
- By optuna
https://qiita.com/DS27/items/ec6a747977e57bb1837e
- By LightGBM Tuner
https://datadriven-rnd.com/lightgbm-tuner/
https://qiita.com/askl4267/items/28b476f76b01699430fe
- 探索範囲参考
https://github.com/optuna/optuna-examples/blob/main/lightgbm/lightgbm_simple.py
- 原論文
https://proceedings.neurips.cc/paper_files/paper/2017/file/6449f44a102fde848669bdd9eb6b76fa-Paper.pdf

## XGBoost
https://qiita.com/c60evaporator/items/a9a049c3469f6b4872c6

https://www.codexa.net/hyperparameter-tuning-python/

https://www.kaggle.com/code/prashant111/a-guide-on-xgboost-hyperparameters-tuning

https://www.kaggle.com/code/felipefiorini/xgboost-hyper-parameter-tuning
- 探索範囲参考
https://github.com/optuna/optuna-examples/blob/main/xgboost/xgboost_cv.py
- 原論文
https://arxiv.org/pdf/1603.02754.pdf
- その解説
https://qiita.com/triwave33/items/aad60f25485a4595b5c8
## CatBoost
- General
https://qiita.com/Mt_Taka/items/e12694aa5a7ed9539216
- By Optuna
https://qiita.com/shin_mura/items/8f1aa1ec90fa4ad6253e
- By Grid SV
https://www.projectpro.io/recipes/find-optimal-parameters-for-catboost-using-gridsearchcv-for-classification
- By Bayes
https://www.kaggle.com/code/shivampanwar/catboost-and-hyperparameter-tuning-using-bayes
- By Amazon
https://docs.aws.amazon.com/ja_jp/sagemaker/latest/dg/catboost-tuning.html
- 探索範囲参考
https://github.com/optuna/optuna-examples/blob/main/catboost/catboost_simple.py
- 原論文
https://arxiv.org/pdf/1706.09516.pdf

## 性能比較記事
https://towardsdatascience.com/catboost-vs-lightgbm-vs-xgboost-c80f40662924

## 深層学習と決定木Boostingとのアンサンブル
https://cloraordinary.com/%E8%AB%96%E6%96%87%E3%81%BE%E3%81%A8%E3%82%81-tabular-data-deep-learning-is-not-all-you-need

- その原論文
https://arxiv.org/pdf/2106.03253.pdf