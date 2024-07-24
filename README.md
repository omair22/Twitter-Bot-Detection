# Twitter Bot Detection with Textual and Numeric Feature Set

## Project Overview
The project aims to detect Twitter bots to stop the spread of false and misleading information. By analyzing both textual and numeric features, the system labels users as genuine or fake using various machine learning algorithms.

## Author
  Omair Ansari  
  CSE: AI & ML  
  University of Petroleum and Energy Studies  
  Bidholi, Dehradun  
  Email: ansari.omair10@gmail.com

## Abstract
The project detects Twitter bots to prevent the dissemination of false and misleading information. Bots, which perform automated tasks over the internet, account for nearly 48 million automated accounts, with 56% of internet bot traffic considered bad. Twitter bots spread false narratives by transmitting spam subject matters, influencing the majority towards one direction. Detecting bot accounts on social media sites like Twitter is crucial for a healthy exchange ecosystem. The project uses machine learning algorithms to determine spam messaging and label users as genuine or fake, thus stopping the cluster of false information about entities and events.

## Introduction
Bots engage with people on social media, reply to messages, execute commands, and perform online searches, mimicking human behavior. Particularly on Twitter, bots spread information that influences public decisions on topics like elections, war, and religion. This project detects these bots, labeling users as fake or genuine to promote the consumption of realistic information and fair decisions. Machine learning algorithms are employed to accomplish this.

## Purpose
The purpose of this project is to detect Twitter bots to stop the spread of false information. By determining spam messages and labeling users as fake or genuine using machine learning algorithms, the project aims to stop the dissemination of false information about entities and events.

## Target Beneficiary
The primary beneficiaries are Twitter users and entities affected by the exchange of false information on the internet.

## Project Scope
Detecting bots will help users make fair decisions, ensuring that information regarding sensitive topics like elections, war, and religion is not biased. This will help prevent the public from being influenced by false narratives and allow for informed decision-making based on accurate information.

## Data and Methodology
Data for this project is fetched from GitHub, providing data of genuine and fake tweets through developer-friendly APIs. The dataset has 19 columns and 2797 rows, with 1476 genuine tweets and 1321 bot tweets. The data is preprocessed and analyzed using various machine learning algorithms, including KNN, Adaboost, and SVM.

## Results and Discussion
The project compares the performance of different machine learning algorithms. Random Forest, after hyper-tuning, performs the best, achieving high accuracy, precision, recall, and F1-score. The project also highlights the importance of using both textual and numeric features in detecting Twitter bots.

## Conclusion
The project demonstrates that combining textual and numeric features is effective for classifying Twitter bots using machine learning algorithms. Future work will focus on gathering more data, incorporating additional features, and exploring deep learning models to further improve bot detection.

## References
1. Jefferson Viana Fonseca Abreu; Celia Ghedini Ralha; Joao Jose Costa Gondim: Twitter Bot Detection with Reduced Feature Set (2020)
2. J. Rodríguez-Ruiz, J. I. Mata-Sa´nchez, R. Monroy, O. Loyola- Gonza´lez, and A. Lo´pez-Cuevas, “A one-class classification approach for bot detection on twitter,” Computers & Security, vol. 91, p. 101715, 2020.
3. E. Beg˘enilmis¸ and S. Uskudarli, “Organized behavior classification of tweet sets using supervised learning methods,” in Proceedings of the 8th International Conference on Web Intelligence, Mining and Semantics (WIMS’18). New York, NY, USA: ACM, 2018.
4. J. Fernquist, L. Kaati, and R. Schroeder, “Political bots and the swedish general election,” in 2018 IEEE International Conference on Intelligence and Security Informatics (ISI). IEEE, 2018, pp. 124–129.
5. O. Varol, E. Ferrara, C. A. Davis, F. Menczer, and A. Flammini, “Online Human-Bot Interactions: Detection, Estimation, and Charac- terization,” in 11th International AAAI Conference on Web and Social Media (ICWSM), May 2017.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
