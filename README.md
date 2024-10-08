# ljycrowd

Our resources (especially the publications and datasets) on the research of crowdsourcing. These datasets can be utilized for the research topics such as crowdsourced label aggregation (truth discovery) with diverse data formats. 

## Categorical Label

### Difficult Heterogeneous-Answer Multiple-Choice Questions
The questions are heterogeneous-answer multiple-choice questions; the crowd answers are categorical labels. It contains difficult tasks that require highly specialized knowledge and the ability of a large majority of the workers is inadequate. The number of experts is small and the average accuracy of crowd labels in each dataset is low. 

[Hyper Questions: Unsupervised Targeting of a Few Experts in Crowdsourcing](https://dl.acm.org/doi/10.1145/3132847.3132971)

[[Data (Label Only)]](http://www.ml.ist.i.kyoto-u.ac.jp/en/en-research/li2017cikm)
[[Data (with Text Content)]](https://github.com/garfieldpigljy/CrowdLabelwithTextContent)
[[PDF]](https://drive.google.com/file/d/1BMLReNx-eX5m_B5Pg44a5als3GHMr0VM/view?usp=sharing)

	@inproceedings{HyperQuestion,
		author = {Li, Jiyi and Baba, Yukino and Kashima, Hisashi},
		title = {Hyper Questions: Unsupervised Targeting of a Few Experts in Crowdsourcing},
		year = {2017},
		isbn = {9781450349185},
		publisher = {Association for Computing Machinery},
		address = {New York, NY, USA},
		url = {https://doi.org/10.1145/3132847.3132971},
		doi = {10.1145/3132847.3132971},
		booktitle = {Proceedings of the 2017 ACM on Conference on Information and Knowledge Management},
		pages = {1069–1078},
		numpages = {10},
		keywords = {crowdsourcing, answer aggregation, hyper question, heterogeneous-answer multiple-choice questions},
		location = {Singapore, Singapore},
		series = {CIKM '17}
	}

## Text/Word Sequence
This data contains crowdsourced word sequences with diverse quality, e.g., translated sentences generated from multiple workers to a given sentence. 

[AnnoNLP2019: A Dataset of Crowdsourced Word Sequences: Collections and Answer Aggregation for Ground Truth Creation](https://aclanthology.org/D19-5904/)

[SIGIR2020: Crowdsourced Text Sequence Aggregation Based on Hybrid Reliability and Representation](https://dl.acm.org/doi/abs/10.1145/3397271.3401239)

[[Data]](https://github.com/garfieldpigljy/CrowdWSA2019)
[[AnnoNLP2019 PDF]](https://aclanthology.org/D19-5904.pdf)
[[SIGIR2020 PDF]](https://drive.google.com/file/d/1o-LR-uZ6u8kcxcq6tdx4vPWSkeb9FJSG/view?usp=sharing)

	@inproceedings{CrowdWSA2019,
		title = "A Dataset of Crowdsourced Word Sequences: Collections and Answer Aggregation for Ground Truth Creation",
		author = "Li, Jiyi and Fukumoto, Fumiyo",
		booktitle = "Proceedings of the First Workshop on Aggregating and Analysing Crowdsourced Annotations for NLP (AnnoNLP2019)",
		month = nov,
		year = "2019",
		address = "Hong Kong",
		publisher = "Association for Computational Linguistics",
		url = "https://www.aclweb.org/anthology/D19-5904",
		doi = "10.18653/v1/D19-5904",
		pages = "24--28"
	}

	@inproceedings{CrowdHRRASA,
		author = {Li, Jiyi},
		title = {Crowdsourced Text Sequence Aggregation Based on Hybrid Reliability and Representation},
		year = {2020},
		isbn = {9781450380164},
		publisher = {Association for Computing Machinery},
		address = {New York, NY, USA},
		url = {https://doi.org/10.1145/3397271.3401239},
		doi = {10.1145/3397271.3401239},
		booktitle = {Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR2020)},
		pages = {1761–1764},
		numpages = {4},
		keywords = {reliability, crowdsourcing, text sequence aggregation},
		location = {Virtual Event, China},
		series = {SIGIR '20}
	}

## Pairwise Preference Comparison Label
Pairwise Preference Comparisons: "Whether Object A is perferred to Object B, by Worker W". 

[CrowDEA: Multi-View Idea Prioritization with Crowds](https://ojs.aaai.org/index.php/HCOMP/article/view/7460)

[[Data]](https://github.com/yukinobaba/crowdea)
[[PDF]](https://ojs.aaai.org/index.php/HCOMP/article/view/7460/7299)

	@article{CrowDEA, 
		title={CrowDEA: Multi-View Idea Prioritization with Crowds}, 
		volume={8}, 
		url={https://ojs.aaai.org/index.php/HCOMP/article/view/7460}, 
		number={1}, 
		journal={Proceedings of the AAAI Conference on Human Computation and Crowdsourcing}, 
		author={Baba, Yukino and Li, Jiyi and Kashima, Hisashi}, 
		year={2020}, 
		month={Oct.}, 
		pages={23-32} 
	}

## Triplet Similarity Comparison Label
Triplet Similarity Comparisons: "Which Object B and Object C is more similar to Object A, by Worker W". 

Paper: Label Aggregation for Crowdsourced Triplet Similarity Comparisons: to appear. 

[[Data]](https://github.com/garfieldpigljy/CrowdTSC2021)
[[PDF]](https://drive.google.com/file/d/1fBfvhrizRAtFpqIIqzJI72Ps6UQA6QZf/view?usp=sharing)

	@inproceedings{CrowdTSC2021,
		title = "Label Aggregation for Crowdsourced Triplet Similarity Comparisons",
		author = "Li, Jiyi and Endo, Lucas Ryo and Kashima, Hisashi",
		booktitle = "Proceedings of the 28th International Conference on Neural Information Processing (ICONIP2021)",
		month = Dec,
		year = "2021"
	}
	

## Our Publications on Crowdsourcing
- **Jiyi Li**, "Human-LLM Hybrid Text Answer Aggregation for Crowd Annotations", Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP 2024), to appear, Nov. 2024.

- **Jiyi Li**, "A Comparative Study on Annotation Quality of Crowdsourcing and LLM via Label Aggregation", Proceedings of the 2024 IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP 2024**), pp. 6525-6529, Apr. 2024. [arXiv][URL(PDF)]
[[arXiv]](http://arxiv.org/abs/2401.09760)
[[URL]](https://ieeexplore.ieee.org/document/10447803)
[[Data]](https://github.com/garfieldpigljy/CrowdLabelwithTextContent)

- Xiaotian Lu, **Jiyi Li**, Zhen Wan, Xiaofeng Lin, Koh Takeuchi and Hisashi Kashima, "Evaluating Saliency Explanations in NLP by Crowdsourcing", the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (**LREC-COLING 2024**), pp. 6431–6443, May. 2024.
[[URL(PDF)]](https://aclanthology.org/2024.lrec-main.570/)

- **Jiyi Li**, "Learning Representations for Sparse Crowd Answers", Proceedings of the 30th International Conference on Neural Information Processing (**ICONIP 2023**), Part 6, LNCS, pp. 468-480, Nov. 2023.
[[URL]](https://link.springer.com/chapter/10.1007/978-981-99-8076-5_34)
[[PDF]](https://drive.google.com/file/d/1ZfHU_8IEum0-JyT5Fklq1bHJNhIu20U5/view?usp=sharing)
  
- Xiaotian Lu, **Jiyi Li**, Koh Takeuchi, Hisashi Kashima, "Multiview Representation Learning from Crowdsourced Triplet Comparisons", Proceedings of the ACM Web Conference 2023 (**WWW 2023**), pp. 3827-3836, Apr. 2023.
[[URL(PDF)]](https://dl.acm.org/doi/abs/10.1145/3543507.3583431)
[[arXiv]](https://arxiv.org/abs/2302.03987)
[[Code]](https://github.com/17bit/multiview_crowdsourcing)

- **Jiyi Li**, "Context-based Collective Preference Aggregation for Prioritizing Crowd Opinions in Social Decision-making", Proceedings of the ACM Web Conference 2022 (**WWW 2022**), pp. 2657-2667, Apr. 2022.
[[URL]](https://dl.acm.org/doi/fullHtml/10.1145/3485447.3512137)
[[PDF]](https://drive.google.com/file/d/1Q-Hz6JFFW0rGLW5i3cjah7IiIxJuyQ-C/view?usp=sharing)

- Jingzheng Li, Hailong Sun, **Jiyi Li**, "Beyond confusion matrix: learning from multiple annotators with awareness of instance features", **Machine Learning**, 2022.
[[URL(PDF)]](https://link.springer.com/article/10.1007/s10994-022-06211-x)

- Guoxi Zhang, **Jiyi Li**, Hisashi Kashima, "Improving Pairwise Rank Aggregation via Querying for Rank Difference", Proceedings of the 9th IEEE International Conference on Data Science and Advanced Analytics (**DSAA 2022**), Oct. 2022.
[[URL]](https://ieeexplore.ieee.org/abstract/document/10032454)
[[PDF]](https://drive.google.com/file/d/18kbU9nt0v6UlC_yNMSUed6E4hFwUdhv_/view?usp=sharing)
  
- Jingzheng Li, Hailong Sun, **Jiyi Li**, Zhijun Chen, Renshuai Tao, Yufei Ge, "Learning from Multiple Annotators by Incorporating Instance Features", arXiv preprint arXiv:2106.15146, 2021. (IJCAI 2021 Workshop Weakly Supervised Representation Learning (**WSRL 2021**)) 
[[arXiv]](https://arxiv.org/abs/2106.15146) 

- **Jiyi Li**, Yasushi Kawase, Yukino Baba, Hisashi Kashima, "Performance as a Constraint: An Improved Wisdom of Crowds Using Performance Regularization", the 29th International Joint Conference on Artificial Intelligence (**IJCAI 2020**), pp. 1534-1541, Jul. 2020. 
[[URL]](https://www.ijcai.org/Proceedings/2020/213) 

- **Jiyi Li**, "Crowdsourced Text Sequence Aggregation based on Hybrid Reliability and Representation", the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR 2020**), Virtual event, pp. 1761-1764, Jul. 2020. 
[[URL]](https://dl.acm.org/doi/10.1145/3397271.3401239) 
[[PDF]](https://drive.google.com/file/d/1o-LR-uZ6u8kcxcq6tdx4vPWSkeb9FJSG/view?usp=sharing) 
[[Data]](https://github.com/garfieldpigljy/CrowdWSA2019)

- Xingkun Zuo, **Jiyi Li**, Qili Zhou, Jianjun Li, Xiaoyang Mao, "AffectI: A Game for Diverse, Reliable, and Efficient Affective Image Annotation", the 28th ACM International Conference on Multimedia (**MM 2020**), Virtual event, pp. 529-537, Oct. 2020. 
[[URL]](https://dl.acm.org/doi/10.1145/3394171.3413744) 
[[PDF]](https://drive.google.com/file/d/1A3WAVkYHU0MxFcomA4ch_5Lcqp3EpvZZ/view?usp=sharing) 

- Yukino Baba, **Jiyi Li**, Hisashi Kashima, "CrowDEA: Multi-view Idea Prioritization with Crowds", the eighth AAAI Conference on Human Computation and Crowdsourcing (**HCOMP 2020**), Virtual event, 8(1), pp. 23-32. 
[[URL]](https://ojs.aaai.org/index.php/HCOMP/article/view/7460) 

- **Jiyi Li**, "Budget Cost Reduction for Label Collection with Confusability Based Exploration", the 26th International Conference on Neural Information Processing of the Asia-Pacific Neural Network (**ICONIP 2019**), Sydney, pp.231-241, Dec.2019. 
[[URL]](https://link.springer.com/chapter/10.1007/978-3-030-36802-9_26) 
[[PDF]](https://drive.google.com/open?id=1WfGC1nDnWe8h4MZUUk5KC2ETBPQyAhps) 

- **Jiyi Li**, Fumiyo Fukumoto, "A Dataset of Crowdsourced Word Sequences:  Collections and Answer Aggregation for Ground Truth Creation", the 2019 Conference on Empirical Methods in Natural Language Processing and 9th International Joint Conference on Natural Language Processing (**EMNLP-IJCNLP 2019**) Workshop on Aggregating and analysing crowdsourced annotations for NLP (**AnnoNLP 2019**), Hong Kong, pp. 24–28, Nov. 2019. 
[[URL]](https://aclanthology.org/D19-5904/) 
[[Data]](https://github.com/garfieldpigljy/CrowdWSA2019) 

- **Jiyi Li**, Yukino Baba, Hisashi Kashima, "Incorporating Worker Similarity for Label Aggregation in Crowdsourcing", The 27th International Conference on Artificial Neural Networks (**ICANN 2018**), Rhodes, pp.596-606, Oct.2018. 
[[URL]](https://link.springer.com/chapter/10.1007/978-3-030-01421-6_57) 
[[PDF]](https://drive.google.com/file/d/1GbhFlshet_zNiiY-GXPa58-U4jcmJErd/view?usp=sharing) 

- **Jiyi Li**, Yukino Baba, Hisashi Kashima, "Simultaneous Clustering and Ranking from Pairwise Comparisons",  the 27th International Joint Conference on Artificial Intelligence (**IJCAI 20'18**), Stockholm, pp.1554-1560, Jul.2018. 
[[URL]](https://www.ijcai.org/proceedings/2018/215) 

- **Jiyi Li**, Yukino Baba, Hisashi Kashima, "Hyper Questions: Unsupervised Targeting of a Few Experts in Crowdsourcing", the 26th ACM International Conference on Information and Knowledge Management (**CIKM 2017**), Singapore, pp.1069-1078, Nov. 2017. 
[[URL]](https://dl.acm.org/doi/10.1145/3132847.3132971) 
[[PDF]](https://drive.google.com/file/d/1BMLReNx-eX5m_B5Pg44a5als3GHMr0VM/view?usp=sharing) 
[[Data (Label Only)]](http://www.ml.ist.i.kyoto-u.ac.jp/en/en-research/li2017cikm)
[[Data (with Text Content)]](https://github.com/garfieldpigljy/CrowdLabelwithTextContent)

- **Jiyi Li**, Hisashi Kashima, "Iterative Reduction Worker Filtering for Crowdsourced Label Aggregation", The 18th International Conference on Web Information Systems Engineering (**WISE 2017**), pp. 46-54, Moscow, Oct. 2017. 
[[URL]](https://link.springer.com/chapter/10.1007/978-3-319-68786-5_4)
[[PDF]](https://drive.google.com/file/d/1nx0VVrs7xrMqKc7Oz6vdgnX99W5V4-oc/view?usp=sharing)

