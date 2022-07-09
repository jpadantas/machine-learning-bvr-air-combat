# machine-learning-bvr-air-combat
IEEE Latin America Transactions

Python code for the article Machine Learning to Improve Situational Awareness in Beyond Visual Range Air Combat.

This article presents an artificial intelligence model using artificial neural networks that provide parameters to improve the situational awareness of a Beyond Visual Range (BVR) air combat pilot. In this combat modality, it is necessary to make decisions based on information from sensors, mainly radars. Furthermore, since information regarding enemy aircraft systems is sometimes unknown, pilots' decisions are usually based on beliefs regarding the opponent. The presented model proposes to deal with such characteristics, generating behaviors for entities represented in a constructive simulation environment, i.e., simulated people operating simulated systems. We created BVR air combat simulations between two aircraft, with only one missile each, through Latin Hypercube Sampling (LHS) to choose input variables to cover almost homogeneously all their ranges. The aircraft have similar behaviors, and their parameters may change only at the beginning of the simulation. The simulation environment generated ten thousand air combat scenarios, varying thirty-six input parameters, for the analysis proposed in the case study. From this data, we could create supervised machine learning models that substantially improve the BVR air combat pilot's situational awareness regarding offensive situations, in which the reference aircraft employs a missile against a target, or defensive positions, in contrast \textcolor{blue}{to} when the same reference aircraft tries to avoid a possible enemy's missile launched in its direction. The offensive and defensive models were consistent with the accuracy of 0.930 and 0.924 and the F1-score of 0.717 and 0.678, respectively. Thus, the contribution of this work is to use machine learning algorithms to generate responses concerning the tactical state to improve the pilot's situational awareness and, therefore, the in-flight decision-making process.

Please check the ipynb files:

* 1-EDA.ipynb: Exploratory Data Analysis;
* 2-Feature-Selection.ipynb: Feature selection techniques using ANOVA-f Statistic and Mutual Information Statistics;
* 3-ANN-Classification-Attack.ipynb: Training and Evaluation of the Classification Model using an Artificial Neural Network concerning the Attack Data;
* 4-ANN-Classification-Defense.ipynb: Training and Evaluation of the Classification Model using an Artificial Neural Network concerning the Defense Data.
