# 通过例子学习 XGBoost

xxx

## 基础

- [回归 Hello World](xxx)（使用 XGBoost 对 xxx 进行拟合）
- [分类 Hello World](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/i_basic/02_hello_world_breast_cancer_dataset.ipynb)（使用 XGBoost 对 [Breast Cancer Dataset](http://archive.ics.uci.edu/ml/datasets/Breast+Cancer) 进行分类）
- [缺失值填充](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/i_basic/03_use_imputer_to_handle_missing_data.ipynb)（使用 `Imputer` 对缺失值进行填充）
- [K-fold Cross Validation](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/i_basic/04_k-fold_cv.ipynb)（使用 K-fold 对模型进行验证）
- [Stratified K-fold CV](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/i_basic/05_stratified_k-fold.ipynb)（对于多分类的情况，采用 Stratified K-fold 保证类别均衡）
- [决策树可视化](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/i_basic/06_plot_single_dt.ipynb)（画出单棵决策树）

## 中级

- [模型的保存与加载 - 方式1](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/ii_intermediate/07_save_%26_reload_trained_model_by_using_pickle.ipynb)（使用 `pickle` 保存与加载训练好的模型）
- [模型的保存与加载 - 方式2](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/ii_intermediate/08_save_%26_reload_trained_model_by_using_joblib.ipynb)（使用 `joblib` 保存与加载训练好的模型）
- [特征重要性可视化](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/ii_intermediate/09_plot_feature_importances.ipynb)（两种方式画出特征重要性）
- [特征选择](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/ii_intermediate/10_feature_selection.ipynb)（用特征重要性去做特征选择）
- [Early Stopping](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/ii_intermediate/11_early_stopping.ipynb)（采用 Early Stopping 避免过拟合）
- [画出学习曲线](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/ii_intermediate/12_plot_learning_curve.ipynb)（从学习曲线中判断模型的训练情况）

## 高级

- [微调树的数目](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/iii_advanced/13_tune_number_of_trees.ipynb)（使用网格搜索微调树的数目）
- [微调树的大小](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/iii_advanced/14_tune_size_of_tree.ipynb)（使用网格搜索微调树的大小）
- [微调学习率](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/iii_advanced/15_tune_shrinkage.ipynb)（使用网格搜索微调学习率）
- [微调行采样](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/iii_advanced/16_tune_row_subsampling.ipynb)（使用网格搜索微调行采样）
- [微调树层级列采样](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/iii_advanced/17_tune_column_subsampling_bytree.ipynb)（使用网格搜索微调树层级列采样）
- [微调结点层级列采样](https://github.com/Genpeng/xgboost-examples/blob/master/ipython/iii_advanced/18_tune_column_subsampling_bylevel.ipynb)（使用网格搜索微调结点层级列采样）
