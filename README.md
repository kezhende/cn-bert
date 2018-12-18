# BERT在中文NLP领域的应用

## 分类
1. 微调：sh run.sh train
2. 分类：sh run.sh predict
3. 准确率：sh run.sh check_acc

## 语法检查
中文纠错一直是中文NLP难题，目前业界主要用到如下方法：  
1. 传统ngram语言模型（kenlm、srilm）
2. 神经网络语言模型（char-level、word-level）
3. 基于seq2seq的流畅度检测（只有paper，无代码）  
本文会基于bert的功能在语法检查领域做一次尝试，其实基本原理仍然是语言模型，只是对数据的表征能力更强

## 预训练
## 无目标提取文本向量