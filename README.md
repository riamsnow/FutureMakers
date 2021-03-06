# FutureMakers
<h1>Responses</h1>
<h1>Week 1</h1> 
<h2>DAY 1 - 7/6/2021: </h2> 
I hope to develop a strong base of technical skills in AI that I can build on as I complete future projects. I am also excited to develop career skills which will help me find internships and jobs in the future. <br/>
<h2> DAY 2 - 7/7/2021: </h2> 
From Dr. Kong's presentation, I learned that I do, in fact, have a unique story to tell and that by telling my story I can change the world in my own way. I also learned how to envigorate my stories to better capture the attention of my audience. This will be especially useful if I need to persude my audience to support a certain cause. In addition, it was great to hear the stories of people who attended one of Dr. Kong's workshops and how learning how to properly tell their story impacted their journey. <br/>
<h2>DAY 3 - 7/8/2021:</h2>
i. With supervised learning, we know the output values and the goal is to find the path from input to output. With unsupervised learning, we do not know the output values and have to predict the patterns based on the unlabeled data<br/>
ii. The statement Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries is false. Scikit-learn is a package that uses data analysis libraries like Graphviz and Pandas to visualize data.
<br/>
<h2>DAY 4 - 7/9/2021:</h2>
Identifying and treating different types of cancers can be a difficult task for doctors depending on the location of tumors and stage of progression. I found a dataset with segmented liver images with digestive cancer. By training a ML model to recognize digestive cancer, doctors can use less invasive procedures for diagnosis. 
https://www.kaggle.com/fattahuzzaman/ircadresearch-institute-against-digestive-cancer <br/>
<h1>Week 2</h1>
<h2>DAY 7 - 7/12/2021:</h2>
<h3>What are “Tensors” and what are they used for in Machine Learning? </h3>
Tensors are the primary data structure used by neural networks. Inputs, outputs, and transformations within neural networks are represented by tensors. Tensors are multidimensional arrays and are generalizations. A scalar (index required = 0) is a 0 dimensional tensor. A vector (index required = 1) is a one dimensional tensor. A matrix (index required = 0) is a 2 dimensional tensor. When the index required is above two, in computer science, it is called an nd-array. In math it is called an nd-tensor. This is why a tensor is a generalization, since it can be used to represent any index required.<br/>
<h3>What did you notice about the computations that you ran in the TensorFlow programs (i.e. interactive models) in the tutorial?</h3>
Suppose I have an array called d with 7 elements [1, 2, 3, 4, 5, 6, 7], and I want to access the number 4 in the data structure. I can do this using a single index d[3]. Suppose, however, I have a 2D array called ff. I need two indexes to refer to the number 7 in the data structure. Using tensorflow, I can also perform matrix mathematical operations, such as multiplication. An example can be found in TensorFlow.ipynb.<br/>
<h2>DAY 8 - 7/13/2021:</h2>
Today, I built a model to detect sarcasm. I found some sample programs which used the Kaggle Dataset (https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection). I then tried taking pieces of different program and getting them to work in my Colab notebook. My Colab noteook compared the performance of three models: a NN, CNN, and LSTM. The results can be found in the chart below. <br/>
|Algorithm| Accuracy| Loss| 
|---|---|---|
|NN|0.851328|2.081993|
|CNN|0.856569|1.647395|
|LSTM|0.853774|0.659341|
<h2>DAY 9 - 7/14/2021: </h2>
Today, I learned about CNNs using this cheatsheet:https://stanford.edu/~shervine/teaching/cs-230/cheatsheet-convolutional-neural-networks. I also learned more about confusion matrices. I then built this model using the MNIST dataset for digit classification.  MNIST2.ipynb <br/>
<h2>DAY 10 - 7/15/2021: </h2>
Today, I played this game: https://www.survivalofthebestfit.com/game/. At first I was able to hire the appropriate number of candidates before time ran out. However, as the game gave me less time, it became harder for me to hire the desired number of workers. Thus, I decided to automate the hiring process. I was able to hire candidates quicker, however I also began to receive complaints. Very qualified candidates were being rejected by the algorithmn. I decided to investgate this. I found that one of the skills I put emphasis on when I was hiring candidates was ambition. I did not realize this, but more orange people had higher ambition values. Thus, I began to hire more orange people than blue people. When I automated the process, the bias of hiring more orange than blue people transferred over to my model. While I did use a larger dataset, these implicit biases were still present. Thus I was met with complains and the company had to be shut down. This was a very eye-opening activity. I now realize that companies must be more conscious to not let their implicit biases affect who they are hiring. A real world example of a biased algorithmn is in 2014, Amazon developed a recruiting tool for identifying software engineers it might want to hire; the system swiftly began discriminating against women, and the company abandoned it in 2017. To fix this, the company should look at their hiring history. Mot likely, they hired more men than women. This implicit bias then transferred to the model. Looking forward, the company should be more conscious of who they hire and try to hire more women so that when they automate their hiring process, it does not discriminate against women.<br/>
<h2>DAY 11 - 7/16/2021: </h2>
(x)I built this ML model which uses the MNIST dataset. Day11_MNIST.ipynb <br/>
<h1>Week 3</h1>
<h2>DAY 14 - 7/19/2021: </h2>
Today, I read an article on choosing loss functions and watched a lecture and reviewed slides on loss functions and optimization. I then built this ML model to predict house prices. houseprices.ipynb <br/>
<h2>DAY 15 - 7/20/2021: </h2>
(x)I completed a tutorial on choosing activiation functions for deep learning. I also learned how to implement the Rectified Linear Unit. <br/>
<h2>DAY 16 - 7/21/2021: </h2>
Today, I reviewed an article on the importance of ethics in the real-world context of AI and automation. I then built this facial recognition model. facialrecognition.ipynb <br/>
<h2>DAY 17 - 7/22/2021: </h2>
Today, I reviewed some of the basics of image classification techniques with ML, using
this notebook. I then reviewed how to build an image classification model using this walkthrough. Finally, I built this model which distinguishes between dogs and cats. dogsandcats.ipynb <br/>
<h2>DAY 18 - 7/23/2021: </h2>
Today, I read about how to avoid overfitting in deep learning neural networks. I then studied the second half of this article which discussed overfitting and regularization approaches. Finally, I followed this tutorial about different approaches for handling overfitting in deep learning models using the Twitter US Airline Sentiment data set. twitter.ipynb <br/>  
<h1>Week 4</h1> 
<h2>DAY 21 - 7/26/2021: </h2>
Today, I learned about downsampling and upsampling. I was also introduced to autoencoders. I built this model to practice what I learned. autoencoders.ipynb <br/> 
<h2>DAY 22 - 7/27/2021: </h2>
Today, I watched a TED Talk by Professor Rosalid Picard to learn about the origins of Affective Computing. I also read about the EMPath 2020 makeathon and checked out this (https://github.com/MITESHPUTHRANNEU/Speech-Emotion-Analyzer) Speech Emotion Analyzer project by Mitesh Putran. I modified it and used Jupyter Notebook instead of Colab, since it was easier for me to import the necessary packages. My work can be found in Speech_Emotion_Analyzer.ipynb <br/> 
<h2>DAY 23 - 7/28/2021: </h2>
Today, I learned about Natural Language Processing to understand how machines make sense of human language. I then built my own Movie Review Classifier moviereviews.ipynb Something important to consider while developing NLP models is that occupational stereotypes may present themselves if developers are not careful. For example, the title nurse may be attributed to the pronouns she or her while the title surgeon may be attributed to the pronouns he or him. <br/> 
<h2>DAY 24 - 7/29/2021: </h2>
Today, I was introduced to Computer Vision. I now better understand how machines “see” the visual world and how they can “read” your emotions by looking at your face. I then watch a TED Talk by Rana El Kaliouby - This App Knows How I Feel. Finally, I implement the emotion detection project outlined in this tutorial (https://cbmm.mit.edu/video/tutorial-computer-vision-4817) using OpenCV. My code can be found in Emotion_Detection.ipynb <br/> 
<h1>Create-a-thon (Weeks 5-6) </h1>
For our team's project, we built an automatic inventory for a fridge. I worked with the YOLOv4 object detection model and trained the model to recognize 5 different classes of foodstuff:apple, banana, cabbage, milk, and pineapple. This code can be found in YOLO_groceries_custom_Aug12.ipynb. My team's presentation can be found here: https://docs.google.com/presentation/d/1hopfIz62eXKrorUGw-sa97ZAOA_W9y2x7CGYSlvMyoI/edit#slide=id.ge96762b759_0_4 and my YOLO model can be found in YOLO_groceries_custom_Aug12.ipynb. <br/>
Participating in this program was a truly rewarding experience. I cannot wait to take what I have learned and apply it to projects I work on in the future. I would like to thank the SureStart Team and Dr. Taniya Mishra for providing me with this amazing opportunity, as well as my mentor Arezoo Bybordi for her guidance throughout the program. 








