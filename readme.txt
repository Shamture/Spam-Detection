-reviews
	-《虚假评论检测研究综述_李璐旸2017》  //目前较新较全面的虚假评论综述
	-《虚假评论综述_》   //同门写的综述
-method reference
	-《Detection of fake opinions using time series》 //[1]基于此篇论文写，参考其时间序列突发检测方法

思路：
1、利用字典的方法对评论进行情感分析得到情感分数。
2、利用分别对正向情感和负向情感进行突发检测利用分别对正向情感和负向情感进行突发检测,用[1]的方法，检测是否落在可疑区间内，
3、再利用是否可疑、文本相似度、评论长度、评论名词率、评论句子数量等特征训练SVM、RT、GBDT模型进行分类



1.Instruction
	1. dataset: The scripts for downloading datasets automatically. Add dataset names into .gitignore file, so the datasets downloaded won’t be pushed.
	2. code: all scripts related to models
	3. note: all notebooks(ipyntbook etc.)
	4. .gitignore(invisible): Excludes some files

	
