# Disease-Category-prediction
Automated disease diagnosis and prediction, powered by AI, play a crucial role in enabling medical professionals to deliver effective care to patients. While such predictive tools have been extensively explored in resource-rich languages like English, this manuscript focuses on predicting disease categories automatically from symptoms documented in the Afaan Oromo language, employing various classification algorithms. This study encompasses machine learning techniques such as support vector machines, random forests, logistic regression, and Naïve Bayes, as well as deep learning approaches including LSTM, GRU, and Bi-LSTM. Due to the unavailability of a standard corpus......

The **main objective** of this study is to apply NLP techniques to the symptoms given by the user and then utilize ML and DL models to predict disease class labels. Finally, the prediction accuracy of the models was evaluated to determine which model provided the best performance.

**#The contributions of our research are:**
	We developed an Afaan Oromo patient symptoms (AOPS) corpus that contains health text documents labeled in ten categories.
	We have developed word embedding (word2vec) from our corpus.
	We have conducted experiments with ML such as SVM (support vector machine), random forest, logistic regression, and Naïve Bayes and deep learning algorithms' such as LSTM (long short term memory), GRU (gated recurrent unit), and Bi-LSTM (bi-directional long short term memory).
	We compared the deep learning model’s performance with machine learning models and found that the DL model outperformed.
	From all the trained models, LSTM plus trained word2vec shows the best performance of all the other models by giving 95.7% accuracy and 96.0% F1 score.

<img src="https://github.com/user-attachments/assets/0bfd15ea-802a-4821-ad6b-ebc4c0e2cb5a" alt="Alt Text" width="700" height="100">

AOPS data preprocessing steps 

<img src="https://github.com/user-attachments/assets/58a0b049-c864-4733-b238-a3ba71a0d8c7" alt="Alt Text" width="600" height="400">

The architectural diagram of the overall proposed methodology 
<img src="https://github.com/user-attachments/assets/180c1f47-5a05-4dbc-8fce-78f1441d317a" alt="Alt Text" width="700" height="200">

Result comparison of the LSTM model with other DL and ML algorithms on all AOPS1, AOPS2, and AOPS3 
<img src="https://github.com/user-attachments/assets/5eca5c29-eb70-4638-9c64-2c1af0649d33" alt="Alt Text" width="500" height="300">

Confusion Matrix for LSTM model using Word2vec

<img src="https://github.com/user-attachments/assets/15b07f3f-c86f-49e5-b5c5-e7ac7f6c6f5c" alt="Alt Text" width="400" height="300">

Training and testing accuracy of LSTM model with Word2vec
**Read Full paper**: https://www.nature.com/articles/s41598-024-62278-7

For further information reach # etanaf@wollegauniversity.edu.et / 142334001@smail.iitpkd.ac.in

**Contributor:**
1. Etana Fikadu (PhD candidate)
2. Mrinal Das (PhD)
3. Teklu Urgessa (PhD)
