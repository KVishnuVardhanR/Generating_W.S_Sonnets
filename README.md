# Generation of W.S Sonnets

## Requirements
- Google Colab, Tensorflow 2.x

## Training
- We'll use the training data of **William Shakespeare** Sonnets using this [link](https://storage.googleapis.com/laurencemoroney-blog.appspot.com/sonnets.txt).
- As we know training a Language Modelling task is compuationally costly and time consuming, Lets use the Colab TPU's to reduce the cost.
- Setup the TPU Runtime in Colab by folowing the steps below :
  - Click on the **Runtime** on the left hand side of the Colab Notebook.
  - Scroll down and Click on the **Change Runtime Type**.
  - Click on the **Hardware Accelerator** and select **TPU** and click **Save**.
- Run the code given in train_test.py file to get 95% training accuracy.

## Test and Deployment
- test the model to generate Meaningful text by following the steps:
  - Save the Model Architecture along with its weights.
  - Test the model on a random seed text to generate the Sonnets.
- Now we can be able to generate a Meaningful Sonnets in Shakespeare Style.   
  
  
## Resources  
- The code has been trained and tested in the [Colab Notebook](https://colab.research.google.com/drive/1IHRuukShhjqIh-uBFYPcUqNXE_s5d30S#scrollTo=07QePX57qhuS).

   