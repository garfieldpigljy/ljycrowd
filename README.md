<b> At the beginning, this is my suggestion after my terrible experiences of utilizing Amazon Mechanical Turk (as well as AWS Billing System integrated with it). 
Considering its extremely poor customer services (very late reply, much later reply than promise, no problem can be resolved, stupid technical problems that cannot be resolved, stupid receipt system that will cause crucial problems in the accounting process of your institution), extremely low quality of data and very high price of qualifications (but still very poor data quality even if you utilize qualifications), I strongly suggest to you, no matter you are a researcher on crowdsourcing or you want to utilize crowdsourcing to collect the data in your own research areas, if you want to reduce the terrible troubles during collecting data, do NOT utilize Amazon Mechanical Turk !!!! (as well as using it with AWS !! AWS agent will just transfer you to MTurk and say a agent will contact you in 24 hour, but then nobody will reply you; Mturk agent will say they need to wait for the service team, finally, nothing can be resolved !!!) </b>

# ljycrowd

Our resources (especially the publications and datasets) on the research of crowdsourcing. These datasets can be utilized for the research topics such as crowdsourced label aggregation (truth discovery) with diverse data formats. 

## Categorical Label

### Difficult Heterogeneous-Answer Multiple-Choice Questions
The questions are heterogeneous-answer multiple-choice questions; the crowd answers are categorical labels. It contains difficult tasks that require highly specialized knowledge and the ability of a large majority of the workers is inadequate. The number of experts is small and the average accuracy of crowd labels in each dataset is low. 

[Hyper Questions: Unsupervised Targeting of a Few Experts in Crowdsourcing](https://dl.acm.org/doi/10.1145/3132847.3132971)

[[Data]](http://www.ml.ist.i.kyoto-u.ac.jp/en/en-research/li2017cikm)
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

	@inproceedings{CrowdTSC2021,
		title = "Label Aggregation for Crowdsourced Triplet Similarity Comparisons",
		author = "Li, Jiyi and Endo, Lucas Ryo and Kashima, Hisashi",
		booktitle = "Proceedings of the 28th International Conference on Neural Information Processing (ICONIP2021)",
		month = Dec,
		year = "2021"
	}
	

## Our Publications on Crowdsourcing

- Jingzheng Li, Hailong Sun, **Jiyi Li**, Zhijun Chen, Renshuai Tao, Yufei Ge, "Learning from Multiple Annotators by Incorporating Instance Features", arXiv preprint arXiv:2106.15146, 2021. (IJCAI 2021 Workshop Weakly Supervised Representation Learning (**WSRL 2021**)) 
[[URL]](https://arxiv.org/abs/2106.15146) 

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
[[Data]](https://dl.acm.org/doi/10.1145/3132847.3132971) 

- **Jiyi Li**, Hisashi Kashima, "Iterative Reduction Worker Filtering for Crowdsourced Label Aggregation", The 18th International Conference on Web Information Systems Engineering (**WISE 2017**), pp. 46-54, Moscow, Oct. 2017. 
[[URL]](https://link.springer.com/chapter/10.1007/978-3-319-68786-5_4)
[[PDF]](https://drive.google.com/file/d/1nx0VVrs7xrMqKc7Oz6vdgnX99W5V4-oc/view?usp=sharing)

