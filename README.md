Smart contracts are digitally written set of transaction protocols which are automatically executed during transactions between mutually distrusted nodes without the mediation of any centralized trusted authority. Recently, many platforms have been used for writing smart contracts like Contract Oriented Language (COL) and Ethereum.
There are few incidences of such exploitations of smart contracts. For example, in June 2016, a decentralized investment fund named DAO (Decentralized Autonomous Organization) lost approximately $70 million due to the stealing of over 3.6 million Ether. Machine learning tools can be used to detect these attacks. Symbolic tools like OYENTE and MAIAN are typically used for vulnerability prediction in smart contracts. In the previous study, LSTM was used to analyse Smart contracts. This repository shows how we can use AWD-LSTM to detect vulnerabilities in a contract.

The high-level idea of the present protocol is to combine a pre-trained encoder with the ‘custom head’ to obtain a better classification: this is motivated by ULMFIT which was originally implemented for the NLP application as articulated in [Howard, J., &amp; Ruder, S. (2018). Universal language model fine-tuning for text classification. arXiv preprint arXiv:1801.06146].
The models are built and trained using fastai library, which is an open-source platform to develop deep-learning models. The models are trained on Google Collaboratory which provides K-80 GPU with 12GB RAM for free to run ML algorithms.

This method produces acceptable results with an accuracy of 91.0% and an F1 score of 90.0% in multi-class classification of SCs. The high AUC indicates robust performance of the algorithm for the detection of vulnerabilities in the SCs.

Google Drive link to all the weights saved:
https://drive.google.com/open?id=11mgiNKVRI81wKWzgf9Z47YYE_BQ6Wkr6
