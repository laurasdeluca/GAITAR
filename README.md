# GAITAR

**GAITAR** The repository includes a series of Jupyter notebooks focused on computational analysis, topic modeling, and keyword-in-context concordance extraction.

## Project Goals

- Analyze thematic patterns in AI-generated responses and early modern texts
- Visualize topic clusters and word usage across documents
- Explore sentiment and language patterns associated with Cleopatra and other figures
- Build keyword-in-context (concordance) displays and similarity heatmaps

## 📁 Notebooks

 Notebook Name                  | Description |
|-------------------------------|-------------|
| `GAITAR-topicmodeling.ipynb`  | Performs LDA topic modeling on `.docx` files, using basic text preprocessing and unigrams/bigrams. Displays top keywords per topic. |
| `gaitar-topicfreq.ipynb`      | A full topic modeling pipeline with visualizations. Produces bar charts of topic proportions per document and top keywords per topic, saved to CSV. |
| `GAITAR3.ipynb`               | Combines topic modeling, VADER sentiment analysis, concordance display, and a cosine similarity heatmap across documents. Outputs topic and sentiment data to CSV. |
| `GAITAR4.ipynb`               | Extends GAITAR3 with KMeans clustering of topic weights, PCA visualizations, simulated topic evolution over time, and per-topic word clouds. Saves topic distributions to CSV. |

