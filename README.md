# BERT-E2E-ABSA
Exploiting BERT for End-to-End Aspect-based Sentiment Analysis


一、直接运行以下，即可得到结果（不过建议笔记本内存要大些，大于等于6G的机器能运行）
python fast_run.py 


二、跑出测试结果：
2.1 若是Linux上，可以直接运行sh train.sh（本文已经将测试数据放到了data/test_CFF文件夹下）
2.2 若是windowns环境，需要安装比如git bash类似软件，才能运行，注意要进入到文件夹所在目录下。
若是要运行自己的数据：需要修改 
1）放自己的数据在 ./data/[YOUR_EVAL_DATASET_NAME].
2）work.sh设置 TASK_NAME为 [YOUR_EVAL_DATASET_NAME]
再运行run: sh work.sh


本文主要来自：https://github.com/lixin4ever/BERT-E2E-ABSA/tree/30b3dffa8676363afd210997efccaac3110ccecf

希望NLP学习者一起交流。
