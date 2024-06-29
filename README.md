# MultiLangMemeNet
*MultiLangMemeNet: A Unified Multimodal Approach for Cross-Lingual Meme Sentiment Analysis*

This paper introduces MultiLangMemeNet, a novel unified multimodal approach for meme sentiment classification across diverse languages. The study proposes a model that integrates visual and textual components to effectively capture the multimodal nature of memes, evaluating its performance on datasets spanning five languages: English, Bangla, Chinese, Hindi, and Tamil. MultiLangMemeNet consistently outperformed both unimodal baselines (vision and text models) and other multimodal approaches across all languages tested, showing significant improvements in accuracy ranging from 2.46% to 13.74% over the best unimodal models, and 2-6% over other multimodal combinations. The researchers explored both early and late fusion strategies, finding that the optimal fusion approach may depend on the specific characteristics of each language. The study demonstrates the effectiveness of MultiLangMemeNet in capturing the complex interplay between visual and textual elements in memes across linguistic and cultural contexts. The paper concludes by discussing limitations and suggesting future research directions, including expanding the language scope, increasing dataset sizes, and exploring more advanced visual-linguistic pre-training techniques. Overall, this research represents a significant advancement in multilingual meme sentiment analysis, offering a robust and generalizable approach to understanding meme sentiment across different languages and cultures.

# 🔍 Proposed Methodology
![image](https://github.com/shakib-sadat/MultiLangMemeNet/assets/62327880/864bce3b-9f7b-473e-89b3-9f9df2f18b9d)

# 📊 Datasets
The MultiLangMemeNet study utilized datasets spanning five diverse languages. Below is a table with links to the datasets used for each language:

| Language | Dataset Link |
|----------|--------------|
| English | [Labeled Meme Images Dataset](https://www.kaggle.com/datasets/hammadjavaid/6992-labeled-meme-images-dataset) |
| Bangla | [MemoSen Dataset](https://github.com/eftekhar-hossain/MemoSen-LREC2022) |
| Chinese | [MET-Meme Dataset](https://www.kaggle.com/datasets/liaolianfoka/met-meme/data) |
| Hindi | [CM-OFF-MEME Dataset](https://github.com/Gitanjali1801/CM_MEMES) |
| Tamil | [Tamil Memes Dataset](https://zenodo.org/records/4765573) |

# ✔️ Proposed Model Performance

The table below shows the performance of MultiLangMemeNet in both early and late fusion approaches across five languages:

| Language | Model Name | Fusion Method | Accuracy | Precision | Recall | F1-score |
|----------|------------|---------------|----------|-----------|--------|----------|
| Bangla | MultiLangMemeNet | Early | 66.02 | 63.09 | 66.02 | 62.71 |
| ^ | ^ | Late | 65.11 | 66.37 | 65.11 | 65.52 |
| Hindi | MultiLangMemeNet | Early | 73.28 | 72.87 | 73.28 | 70.97 |
| ^ | ^ | Late | 69.93 | 68.48 | 69.93 | 68.67 |
| Tamil | MultiLangMemeNet | Early | 47.0 | 49.0 | 47.0 | 47.0 |
| ^ | ^ | Late | 59.0 | 35.0 | 59.0 | 44.0 |
| English | MultiLangMemeNet | Early | 61.0 | 57.0 | 63.0 | 56.0 |
| ^ | ^ | Late | 59.0 | 48.0 | 57.0 | 46.0 |
| Chinese | MultiLangMemeNet | Early | 61.0 | 70.0 | 61.0 | 65.2 |
| ^ | ^ | Late | 60.0 | 75.0 | 59.0 | 66.0 |
