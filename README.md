# Dogs and Cats Image Detection using basic CNN Model
![image](https://user-images.githubusercontent.com/66888595/119804793-4dbaf200-befe-11eb-830f-8188835d5b92.png)![image](https://user-images.githubusercontent.com/66888595/119804825-557a9680-befe-11eb-97bd-23795391d7a9.png)

## Table of Content
<ul>
  <li>
    <a href="#overview">
      <span>1. Overview</span>
    </a>
  </li>
  
  <li>
    <a href="#data">
      <span>2. Dataset</span>
    </a>
  </li>
  
  <li>
    <a href="#Motivation">
      <span>3. Motivation</span>
    </a>
  </li>
  <li>
    <a href="#aspects">
      <span>4. Technical Aspects</span>
    </a>
  </li>
   
</ul>

<h3>
  <span id="overview">Overview</span>
</h3>

> This model, built in this .ipynb file, is based on Convolutional Neural Network, used to classify the image if it's a dog's or cat's iamge with a 75%(approximate) test accuracy.

<h3>
  <span id="data" >Dataset</span>
</h3>

> The dataset has been downloaded from these <a href="https://www.dropbox.com/s/t4pzwpvrzneb190/training_set.zip">Training Dataset Link</a> and <a href="https://www.dropbox.com/s/i37jfni3d29raoc/test_set.zip"> Test Dataset Link</a>. Next I unzipped those two files to use it.<br>The dogs vs. cats dataset is standard computer vision dataset that involves classifying photos as either containing a dog or cat. It was only effectively addressed in the last years using deep learning convolutional neural networks. While the dataset is effectively solved, it can be used as the basis for learning and practicing how to develop, evaluate, and use convolutional deep learning neural networks for image classification.

<h3>
  <span id="Motivation" >Motivation</span>
</h3>

> Every big project need a basic foundation. This project is the foundation of a bigger project. 

<h3>
  <span id="aspects" >Technical Aspects</span>
</h3>

> I personally followed the following steps(which I have mentioned in the notebook, separately):<br>1. Prepare the dataset for the model<br>2. Install TensorFlow 2.x<br>3. Develop convolutional neural network model for classifying the images of Dogs vs. Cats<br>4. Plot the change in accuracy per epochs<br>5. Evalutae the model on the testing data.<br>6. Analyse the model summary<br>7. Add Dropout to prevent overfitting and check its effect on accuracy<br>8. Increasing the number of hidden Layers check its effect on accuracy<br>9. Manipulate the batch_size and epochs and check its effect on accuracy.
