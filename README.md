# FutureMakers
Responses <br/>
**Week 1 <br/>**
**DAY 1 - 7/6/2021: <br/>**
I hope to develop a strong base of technical skills in AI that I can build on as I complete future projects. I am also excited to develop career skills which will help me find internships and jobs in the future. <br/>
**DAY 2 - 7/7/2021:<br/>**
From Dr. Kong's presentation, I learned that I do, in fact, have a unique story to tell and that by telling my story I can change the world in my own way. I also learned how to envigorate my stories to better capture the attention of my audience. This will be especially useful if I need to persude my audience to support a certain cause. In addition, it was great to hear the stories of people who attended one of Dr. Kong's workshops and how learning how to properly tell their story impacted their journey. <br/>
**DAY 3 - 7/8/2021:<br/>**
i. With supervised learning, we know the output values and the goal is to find the path from input to output. With unsupervised learning, we do not know the output values and have to predict the patterns based on the unlabeled data<br/>
ii. The statement Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries is false. Scikit-learn is a package that uses data analysis libraries like Graphviz and Pandas to visualize data.
<br/>
**DAY 4 - 7/9/2021:<br/>**
Identifying and treating different types of cancers can be a difficult task for doctors depending on the location of tumors and stage of progression. I found a dataset with segmented liver images with digestive cancer. By training a ML model to recognize digestive cancer, doctors can use less invasive procedures for diagnosis. 
https://www.kaggle.com/fattahuzzaman/ircadresearch-institute-against-digestive-cancer <br/>
**Week 2 <br/>**
**DAY 7 - 7/12/2021:<br/>**
**What are “Tensors” and what are they used for in Machine Learning? <br/>**
Tensors are the primary data structure used by neural networks. Inputs, outputs, and transformations within neural networks are represented by tensors. Tensors are multidimensional arrays and are generalizations. A scalar (index required = 0) is a 0 dimensional tensor. A vector (index required = 1) is a one dimensional tensor. A matrix (index required = 0) is a 2 dimensional tensor. When the index required is above two, in computer science, it is called an nd-array. In math it is called an nd-tensor. This is why a tensor is a generalization, since it can be used to represent any index required.<br/>
**What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial? <br/>**
Suppose I have an array called d with 7 elements [1, 2, 3, 4, 5, 6, 7], and I want to access the number 4 in the data structure. I can do this using a single index d[3]. Suppose, however, I have a 2D array called ff. I need two indexes to refer to the number 7 in the data structure. Using tensorflow, I can also perform matrix mathematical operations, such as multiplication. An example can be found in TensorFlow.ipynb.<br/>
**DAY 8 - 7/13/2021:<br/>**
Today, I build a model to detect sarcasm. I found some sample programs which used the Kaggle Dataset (https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection). I then tried taking pieces of different program and getting them to work in my Colab notebook. My Colab noteook compared the performance of three models: a NN, CNN, and LSTM. The results can be found in the chart below.
| Accuracy| Loss |
|------------|--------|
|NN     | 0.851328  |2.081993|
|CNN  | 0.856569  |1.647395|
|LSTM| 0.853774  |0.659341|

<br/>
<br/> **DAY 9 - 7/14/2021: <br/>**
Today, learned about CNNs using this cheatsheet:https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks. I also learned more about confusion matrices. I then built this model using the MNIST dataset for digit classification.  MNIST2.ipynb <br/>
**DAY 10 - 7/15/2021: <br/>
Today I played this game: https://www.survivalofthebestfit.com/game/. At first I was able to hire the appropriate number of candidates before time ran out. However, as the game gave me less time, became harder for me to hire the desired number of workers. Thus, I decided to automate the hiring process. I was able to hire candidates quicker, however I also began to receive complaints. Very qualified candidates were being rejected by the algorithmn. I decided to investgate this. I found that one of the skills I put emphasis on when I was hiring candidates was ambition. I did not realize this, but more orange people had higher ambition values. Thus, I began to hire more orange people than blue people. When I automated the process, the bias of hiring more orange than blue people transferred over to my model. While I did use a larger dataset, these implicit biases were still present. Thus I was met with complains and the company had to be shut down. This was a very eye-opening activity. I now realize that companies must be more conscious to not let their implicit biases affect who they are hiring. A real world example of a biased algorithmn is in 2014, Amazon developed a recruiting tool for identifying software engineers it might want to hire; the system swiftly began discriminating against women, and the company abandoned it in 2017. To fix this, the company should look at their hiring history. Mot likely, they hired more men than women. This implicit bias then transferred to the model. Looking forward, the company should be more conscious of who they hire and try to hire more women so that when they automate their hiring process, it does not discriminate against women.






