
<h1><strong>Reviews Text Summarization</strong></h1>
<h2> Building an Enterprise grade Summarization model </h2> 

<h3> <strong>Problem Statment : </strong> </h3>
  1. We are trying to save the time of the users spent on reading all reviews and leading to confusion and not useful.<br>
  2. A small negative thing on a comment we lead to a customer skip that product and opt the other <br>
  3. Giving it as a helping hand to efficiently select a product <br>
<br>
<p>The project is all about providing an extra feature for the AMAZON E-COM platform in the reviews sections. <br>

>Here we are trying to implement a summarization model that takes all the text in the review field and provides you with the summarized review of the products </p>


<h2> <strong>Stage One: </strong> </h2>

<ol>
  <li><strong>Data collection </strong>
    <p>Gathering data through Web Scraping the Amazon website </p>
  <li> <strong>Data Preprocessing: </strong>
    <p>Prepare the data suitable to train the model </p>
  <li> <strong>Model training and Evaulation: </strong>
    <p>Using the scraped data train, test and hypertune the model  to acheive state of art performance </p> 
  <li> <strong>Model Prediction and Loss minimization: </strong>
    <p>Trying out to minimize the loss function and check for over-fiiting and under-fitting scenarios </p> 
  <li> <strong>Hypertuning the Model</strong>
    <p>Tuning to model to improve the exisiting accuracy</p> </ol>
     

<h2> <strong>Stage Two: </strong> </h2>
<ol>
  <li> <strong>Building the App</strong>
    <p>Wrapping the model with Django Server </p>
  <li> <strong>Connecting to Databases</strong>
    <p>Using Postgre/MongoDB to store the input</p>
  <li> <strong>Model Deployment</strong>
    <p>Deploying the Model on EC2 instance for easy access and scalability</p>
</ol>

<h2> <strong>Stage Three: (Repeat Stage ONE) </strong> </h2>
<ol>
   <li><strong>Adding a progress bar</strong>
    <p>This progress bar reflects Customer satifcation on the product. <br> <strong>Note: It can be a direct evaluation metric for the product </strong>
    </p>
    
  <li><strong>Count of reviews</strong>
    <p>This gives a clarity to customer to how many reviews have been summarised to get this output 
    </p>

  <li><strong>Merging it with deployed model</strong>
    <p>Update the page with this feature</p>