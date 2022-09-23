# ETE
Some papers on event time embedding, including event time relationship extraction, time segment extraction, time segment prediction.
<!-- # Contents -->
<!-- # Libiraries
- LibKGE code -->
# Methodologies
### Time embedding
| Year | Source | Methods |
| :---: | :---: | :---: |
| 2018 | ACL | TempRels|
| 2019 | ACL | Timex |
| 2021 | ACL-IJCNLP | Curcature |
### Event-Event temporal relation extraction
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2018 | KDD | CCMs |
| 2019 | CORR  | CaTeRS |
| 2020 | EMNLP | TORQUE |
| 2021 | EMNLP | Stack-Propagation |
| 2021 | ACL   | TIMERS |
| 2022 | ACL   | DocTime |
### Event time argument extraction
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2016 | ACL | TemAnchoring |
| 2017 | ACL | SynTime |
| 2018 | EMNLP | CogCompTime |
| 2018 | ACL   | DecisionTree |
| 2021 | ACL | 4-tuple |
| 2021 | arxiv | STAGE |
### Event-Event temporal relation prediction
| Year | Source | Methods |
| :---: | :---: | :---: | 
### Event time argument prediction
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2020 | EMNLP | TIMEPLEX |
| 2020 | ACL | TACOLM |
| 2021 | K-CAP | TIME2BOX |
| 2021 | ACL | TTE |
| 2021 | ACL-IJCNLP | DeepHit |
| 2022 | ACL | VerbalAspect |
### Time knowledge graph completion
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2020 | ICLR | TNTComplEx |
| 2020 | EMNLP | RE-NET |
| 2021 | AAAI | CyGNet |
| 2021 | KDD | T-GAP |
# Papers
### Time embedding
- Qiang Ning, Hao Wu, and Dan Roth. "A Multi-Axis Annotation Scheme for Event Temporal Relations". ACL, 2018.
- Tanya Goyal and Greg Durrett. "Embedding time expressions for deep temporal ordering models". ACL, 2019.
- Sebastien Montella. "Hyperbolic Temporal Knowledge Graph Embeddings with Relational and Time Curvatures". ACL-IJCNLP, 2021.
- Kaspar Beelen, Federico Nanni, Mariona Coll Ardanuy, Kasra Hosseini, Giorgia Tolfo, and Barbara McGillivray. "When Time Makes Sense: A Historically-Aware Approach to Targeted Sense Disambiguation". ACL-IJCNLP, 2021.
### Event-Event temporal relation extraction
- Qiang Ning, Zhili Feng, Hao Wu, Dan Roth. "Joint Reasoning for Temporal and Causal Relations". ACL, 2018.
- Rujun Han, Mengyue Liang, Bashar Alhafni, and Nanyun Peng. "Contextualized Word Embeddings Enhanced Event Temporal Relation Extraction for Story Understanding". CoRR, 2019.
- Qiang Ning, Hao Wu, Rujun Han, Nanyun Peng, Matt Gardner, and Dan Roth. "TORQUE: A Reading Comprehension Dataset of Temporal Ordering Questions". EMNLP, 2020.
- Haoyang Wen and Heng Ji. "Utilizing Relative Event Time to Enhance Event-Event Temporal Relation Extraction". EMNLP, 2021.
- Puneet Mathur, Rajiv Jain, Franck Dernoncourt, Vlad Morariu, Quan Hung Tran, and Dinesh Manocha. "TIMERS: Document-level Temporal Relation Extraction". ACL, 2021.
- Aman Madaan and Yiming Yang. "Neural Language Modeling for Contextualized Temporal Graph Generation". NAACL, 2021.
- Puneet Mathur, Vlad I Morariu, Verena Kaynig-Fittkau, Jiuxiang Gu, Franck Dernoncourt, Quan Hung Tran, Ani Nenkova,Dinesh Manocha, and Rajiv Jain. "DocTime: A Document-level Temporal Dependency Graph Parser". ACL, 2022.
### Event time argument extraction
- Nils Reimers, Nazanin Dehghani, Iryna Gurevych. "Temporal Anchoring of Events for the TimeBank Corpus". ACL, 2016.
- Xiaoshi Zhong, Aixin Sun, and Erik Cambria. "Time Expression Analysis and Recognition Using Syntactic Token Types and General Heuristic Rules". ACL 2017.
- Qiang Ning, Ben Zhou, Zhili Feng, Haoruo Peng, Dan Roth. "CogCompTime: A Tool for Understanding Time in Natural Language". EMNLP, 2018.
- Nils Reimers, Nazanin Dehghani, Iryna Gurevych. "Event Time Extraction with a Decision Tree of Neural Classiﬁers". ACL, 2018.
- Haoyang Wen, Yanru Qu, Heng Ji, Qiang Ning, Jiawei Han, Avirup Sil, Hanghang Tong, Dan Roth. "Event Time Extraction and Propagation via Graph Attention Networks". ACL, 2021.
- Luke Breitfeller, Aakanksha Naik, and Carolyn Rose. "STAGE: Tool for Automated Extraction of Semantic Time Cues to Enrich Neural Temporal Ordering Models". Arxiv, 2021.
### Event-Event temporal relation prediction
- Qiang Ning, Sanjay Subramanian, and Dan Roth. "An Improved Neural Baseline for Temporal Relation Extraction". EMNLP, 2019.
### Event time argument prediction
- Prachi Jain, Sushant Rathi, Mausam, and Soumen Chakrabarti. "Temporal Knowledge Base Completion: New Algorithms and Evaluation Protocols". EMNLP, 2020.
- Ben Zhou, Qiang Ning, Daniel Khashabi, and Dan Roth. "Temporal Common Sense Acquisition with Minimal Supervision". ACL, 2020.
- Ling Cai, Krzysztof Janowicz, Bo Yan, Rui Zhu, and Gengchen Mai. "Time in a Box: Advancing Knowledge Graph Completion with Temporal Scopes". K-CAP, 2021.
- Nazanin Dehghani, Hassan Hajipoor, Hadi Amiri. "Embedding Time Differences in Context-sensitive Neural Networks for Learning Time to Event". ACL, 2021.
- Eleni Metheniti, Tim Van de Cruys, and Nabil Hathout. "About Time: Do Transformers Learn Temporal Verbal Aspect?". ACL, 2021.
- Lianhui Qin, Aditya Gupta, Shyam Upadhyay, Luheng He, Yejin Choi, Manaal Faruqui. "TIMEDIAL: Temporal Commonsense Reasoning in Dialog". ACL-IJCNLP, 2021.
- Christine De Kock, Andreas Vlachos. "Survival text regression for time-to-event prediction in conversations". ACL-IJCNLP, 2021.
### Time knowledge graph completion
- Timothee Lacroix, Guillaume Obozinski, and Nicolas Usunier. "TENSOR DECOMPOSITIONS FOR TEMPORAL KNOWLEDGE BASE COMPLETION". 2020, ICLR.
- Woojeong Jin, Meng Qu, Xisen Jin, and Xiang Ren. "Recurrent Event Network: Autoregressive Structure Inference over Temporal Knowledge Graphs". EMNLP, 2020.
- Cunchao Zhu, Muhao Chen, Changjun Fan, Guangquan Cheng, and Yan Zhang. AAAI, 2021.
- Jaehun Jung, Jinhong Jung, and U Kang. "Learning to Walk across Time for Interpretable Temporal Knowledge Graph Completion". KDD, 2021.
<!-- # Datasets -->
<!-- | Year | Source | Methods | MR | MRR | Hits@1 | Hits@3 | Hits@10 | -->
<!-- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | -->
<!-- | 2018 | EMNLP | TA-DistMult | 276 | 0.477 | 0.363 | - | 0.686 | -->
<!-- # Performance -->
