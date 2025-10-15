% global group logo up here?
# Think Globally, Group Locally: Evaluating LLMs Using Multi-Lingual Word Grouping Games
The repository for data and code associated with the EMNLP Main 2025 paper "Think Globally, Group Locally: Evaluating LLMs Using Multi-Lingual Word Grouping Games", presenting the GlobalGroup dataset and evaluation.

Authors: César Guerra-Solano, Zhuochun Li, Xiang Lorraine Li

Abstract: Large language models (LLMs) can exhibit biases in reasoning capabilities due to linguistic modality, performing better on tasks in one language versus another, even with similar content. Most previous works evaluate this through reasoning tasks where reliance on strategies or knowledge can ensure success, such as in commonsense or math tasks. However, abstract reasoning is vital to reasoning for everyday life, where people apply "out-of-the-box thinking" to identify and use patterns for solutions, without a reliance on formulaic approaches. Comparatively, little work has evaluated linguistic biases in this task type. In this paper, we propose a task inspired by the New York Times Connections: GlobalGroup, that evaluates models in an abstract reasoning task across several languages. We constructed a game benchmark with five linguistic backgrounds -- English, Spanish, Chinese, Hindi, and Arabic -- in both the native language and an English translation for comparison. We also proposed game difficulty measurements to evaluate models on games with similar difficulty, enabling a more controlled comparison, which is particularly important in reasoning evaluations. Through experimentation, we find English modalities largely lead to better performance in this abstract reasoning task, and performance disparities between open- and closed-source models.

This paper will soon be available on Arxiv and in EMNLP Main 2025 conference proceedings.

Current:
- All unscored games datasets
- All groupings datasets, including the combined translated groupings datasets for ease of view

To-do:
- Scored games datasets
- Model prompting script for game, overlap
- Evaluation scripts for model responses, games
