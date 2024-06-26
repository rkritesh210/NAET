# NAET

This repository contains the data for the paper "Multi-Aspect Annotation and Analysis of Nepali Tweets on Anti-Establishment Election Discourse."

# Abstract

In today’s social media-dominated landscape, digital platforms wield substantial influence over public opinion, particularly during crucial political events such as electoral processes. These platforms become hubs for diverse discussions, encompassing topics, reforms, and desired changes. Notably, in times of government dissatisfaction, they serve as arenas for anti-establishment discourse, highlighting the need to analyze public sentiment in these conversations. However, the analysis of such discourse is notably scarce, even in high-resource languages, and entirely non-existent in the context of the Nepali language. To address this critical gap, we present Nepal Anti Establishment discourse Tweets (NAET), a novel dataset comprising 4,445 multi-aspect annotated Nepali tweets, facilitating a comprehensive understanding of political conversations. Our contributions encompass evaluating tweet relevance, sentiment, and satire, while also exploring the presence of hate speech, identifying its targets, and distinguishing directed and non-directed expressions. Additionally, we investigate hope speech, an underexplored aspect crucial in the context of anti-establishment discourse, as it reflects the aspirations and expectations from new political figures and parties. Furthermore, we set NLP-based baselines for all these tasks. To ensure a holistic analysis, we also employ topic modeling, a powerful technique that helps us identify and understand the prevalent themes and patterns emerging from the discourse. Our research thus presents a comprehensive and multi-faceted perspective on anti-establishment election discourse in a low-resource language setting. The dataset is publicly available, facilitating in-depth analysis of political tweets in Nepali discourse and further advancing NLP research for the Nepali language through labeled data and baselines for various NLP tasks. The dataset for this work is made available at https://github.com/rkritesh210/NAET.    

## Annotation terminology

### Relevance
|  Class | Terminology | 
| :--------: | :--------: | 
| Non-Relevant | 0 | 
| Relevant | 1 | 


### Sentiment
|  Class | Terminology | 
| :--------: | :--------: | 
| Neutral | 0 | 
| Positive | 1 | 
| Negative | 2 | 


### Satire
|  Class | Terminology | 
| :--------: | :--------: | 
| No-Satire | 0 | 
| Satire | 1 | 


### Hate
|  Class | Terminology | 
| :--------: | :--------: | 
| No-Hate | 0 | 
| Hate | 1 | 

### Direction of Hate Speech

|  Class | Terminology | 
| :--------: | :--------: | 
| Undirected | 0 | 
| Directed | 1 | 

### Targets of Hate Speech
|  Class | Terminology | 
| :--------: | :--------: | 
| Individual | 1 | 
| Community | 2 | 
| Organization | 3 | 

### Citation

If you decide to use this dataset please cite the following paper.

[Multi-Aspect Annotation and Analysis of Nepali Tweets on Anti-Establishment Election Discourse](https://ieeexplore.ieee.org/document/10355965)

```bibtex
@article{rauniyar2023multi,
  title={Multi-Aspect Annotation and Analysis of Nepali Tweets on Anti-Establishment Election Discourse},
  author={Rauniyar, Kritesh and Poudel, Sweta and Shiwakoti, Shuvam and Thapa, Surendrabikram and Rashid, Junaid and Kim, Jungeun and Imran, Muhammad and Naseem, Usman},
  journal={IEEE Access},
  year={2023},
  publisher={IEEE}
}
```



