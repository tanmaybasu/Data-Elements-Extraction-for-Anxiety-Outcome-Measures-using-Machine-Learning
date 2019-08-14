# Anxiety-Outcome-Measures-using-Machine-Learning
The process of developing systematic reviews is a well established method of collecting evidence from publications, where it follows a predefined and explicit protocol design to promote rigour, transparency and repeatability. The process is manual and involves lot of time and needs expertise. The aim of this work is to build an effective framework using machine learning techniques to partially automate the process of systematic literature review by extracting required data elements of anxiety outcome measures. A framework is thus proposed that initially builds a training corpus by extracting different data elements related to anxiety outcome measures from relevant publications. The publications are retrieved from Medline, EMBASE, CINAHL, AHMED and Pyscinfo following a given set of rules defined by a research group in the United Kingdom reviewing comfort interventions in health care. Subsequently, the method trains a machine learning classifier using this training corpus to extract the desired data elements from new publications. The experiments are conducted on 48 publications containing anxiety outcome measures with an aim to automatically extract the sentences stating the mean and standard deviation of the measures of outcomes of different types of interventions to lessen anxiety. The experimental results show that the recall and precision of the proposed method using random forest classifier are respectively 100% and 83%, which indicates that the method is able to extract all required data elements
