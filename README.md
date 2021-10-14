# ljycrowd
Our resources (especially the datasets) on the research of crowdsourcing. 

These datasets can be utilized for the research topics related to label aggregation with diverse data formats. 

## Categorical Label

### Difficult Heterogeneous-Answer Multiple-Choice Questions
The questions are heterogeneous-answer multiple-choice questions; the crowd answers are categorical labels. It contains difficult tasks that require highly specialized knowledge and the ability of a large majority of the workers is inadequate. The number of experts is very small and the average accuracy of crowd labels in each dataset relatively low. 

[Hyper Questions: Unsupervised Targeting of a Few Experts in Crowdsourcing](https://dl.acm.org/doi/10.1145/3132847.3132971)
[Dataset](http://www.ml.ist.i.kyoto-u.ac.jp/en/en-research/li2017cikm)

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
[Dataset](https://github.com/garfieldpigljy/CrowdWSA2019)

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
Pairwise Preference Comparisons: Whether Object A is perferred to Object B, by Worker W. 

[Dataset](https://github.com/yukinobaba/crowdea)
[CrowDEA: Multi-View Idea Prioritization with Crowds](https://ojs.aaai.org/index.php/HCOMP/article/view/7460)

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
Triplet Similarity Comparisons: Which Object B and Object C is more similar to Object A, by Worker W. 
 
[Dataset](https://github.com/garfieldpigljy/CrowdTSC2021)
Paper: Label Aggregation for Crowdsourced Triplet Similarity Comparisons: to appear. 

	@inproceedings{CrowdTSC2021,
		title = "Label Aggregation for Crowdsourced Triplet Similarity Comparisons",
		author = "Li, Jiyi and Endo, Lucas Ryo and Kashima, Hisashi",
		booktitle = "Proceedings of the 28th International Conference on Neural Information Processing (ICONIP2021)",
		month = Dec,
		year = "2021"
	}
