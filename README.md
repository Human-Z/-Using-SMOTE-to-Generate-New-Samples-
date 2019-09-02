# -Using-SMOTE-to-Generate-New-Samples-
以原始六个记录表，运用SMOTE来生成新的样本后，倒推新ID的各项记录。

该存储库包括用于SMOTE样本生成的原样本存放在raw_data中，以及创造特征构成新样本的代码get_feature_to_SMOTE.ipynb，并利用生成的新样本倒推六个表的ID记录。
其中对于信用卡账单记录详细的处理方案可从三张思维导图中获得。
最终还对新生成的所有样本数据进行检验，见feature_extract&LightGBM.ipynb
