# ETE
Some papers on event time embedding, including event time relationship extraction, time segment extraction, time segment prediction.
# Contents
# Libiraries
- LibKGE code
# Methodologies
### Time embedding
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2019 | ACL | Timex |
### Event-Event time relation extraction
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2021 | EMNLP | Stack-Propagation |
| 2020 | EMNLP | TORQUE |
| 2021 | ACL   | TIMERS |
| 2022 | ACL   | DocTime |
### Event time argument extraction
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2017 | ACL | SynTime |
| 2016 | ACL | TemAnchoring |
| 2021 | ACL | 4-tuple |
### Event-Event time relation prediction
### Event time argument prediction
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2021 | K-CAP | TIME2BOX |
| 2020 | EMNLP | TIMEPLEX |
| 2020 | ACL | TACOLM |
| 2021 | ACL | TTE |
| 2022 | ACL | VerbalAspect |
### Time knowledge graph completion
| Year | Source | Methods |
| :---: | :---: | :---: | 
| 2020 | ICLR | TNTComplEx |
# Papers
### Event embedding
- Tanya Goyal and Greg Durrett. "Embedding time expressions for deep temporal ordering models". ACL, 2019.
### Event-Event time relation extraction
- Haoyang Wen and Heng Ji. "Utilizing Relative Event Time to Enhance Event-Event Temporal Relation Extraction". EMNLP 2021.
- Qiang Ning, Hao Wu, Rujun Han, Nanyun Peng, Matt Gardner, and Dan Roth. "TORQUE: A Reading Comprehension Dataset of Temporal Ordering Questions". EMNLP 2020.
- Puneet Mathur, Rajiv Jain, Franck Dernoncourt, Vlad Morariu, Quan Hung Tran, and Dinesh Manocha. "TIMERS: Document-level Temporal Relation Extraction". ACL, 2021.
- Puneet Mathur, Vlad I Morariu, Verena Kaynig-Fittkau, Jiuxiang Gu, Franck Dernoncourt, Quan Hung Tran, Ani Nenkova,Dinesh Manocha, and Rajiv Jain. "DocTime: A Document-level Temporal Dependency Graph Parser". ACL, 2022.
### Event time argument extraction
- Xiaoshi Zhong, Aixin Sun, and Erik Cambria. "Time Expression Analysis and Recognition Using Syntactic Token Types and General Heuristic Rules". ACL 2017.
- Nils Reimers, Nazanin Dehghani, Iryna Gurevych. "Temporal Anchoring of Events for the TimeBank Corpus". ACL, 2016.
- Haoyang Wen, Yanru Qu, Heng Ji, Qiang Ning, Jiawei Han, Avirup Sil, Hanghang Tong, Dan Roth. "Event Time Extraction and Propagation via Graph Attention Networks". ACL, 2021.
### Event-Event time relation prediction
### Event time argument prediction
- Ling Cai, Krzysztof Janowicz, Bo Yan, Rui Zhu, and Gengchen Mai. "Time in a Box: Advancing Knowledge Graph Completion with Temporal Scopes". K-CAP 2021.
- Prachi Jain, Sushant Rathi, Mausam, and Soumen Chakrabarti. "Temporal Knowledge Base Completion: New Algorithms and Evaluation Protocols"
- Ben Zhou, Qiang Ning, Daniel Khashabi, and Dan Roth. "Temporal Common Sense Acquisition with Minimal Supervision". ACL, 2020.
- Nazanin Dehghani, Hassan Hajipoor, Hadi Amiri. "Embedding Time Differences in Context-sensitive Neural Networks for Learning Time to Event". ACL, 2021.
- Eleni Metheniti, Tim Van de Cruys, and Nabil Hathout. "About Time: Do Transformers Learn Temporal Verbal Aspect?". ACL, 2021.
### Time knowledge graph completion
- Timothee Lacroix, Guillaume Obozinski, and Nicolas Usunier. "TENSOR DECOMPOSITIONS FOR TEMPORAL KNOWLEDGE BASE COMPLETION". 2020 ICLR.
# Datasets
| Year | Source | Methods | MR | MRR | Hits@1 | Hits@3 | Hits@10 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 2018 | EMNLP | TA-DistMult | 276 | 0.477 | 0.363 | - | 0.686 |
# Performance
