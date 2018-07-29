# 粤语分析
采用pycantonese作为粤语语料库以及预料分析工具

# 分词工具
采用jieba分词工具进行分词，jieba的分词字典需要从pycantonese里面获得

# 用法
1. ./data/init_dict.txt  初始化的分词，可以加入一些常用的词，格式是[单词] [词频] [词性]。 例如: 嗰度 120 r
2. word_dictionary.py 创建分词字典，运行即可在./data/下面创建分词字典dict.txt
3. word_segment.py 分词工具, 运行查看分词结果