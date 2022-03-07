# Plant-Disease-Prediction
 ## to run the file, just go into the folders directory and type streamlit run main_app.py 
 provided you downloaded all the requirements from requirements.txt file :)
 
Here's a project that i built with TensorFlow. The model predicts which of 4 diseases a leaf has. It was trained using 900 photos with 80/20 split of training and testing data. I was actually shocked it got 98% accuraccy on unseen previously test data.

Normalized the data using python's dividing method which in my opinion is AMAZING, you don't need to loop through all the pictures and divide them by 225, you can just do / 225.0. Then i reshaped the vectors.

For compressing the photos and ultimately building the model i used Conv2D and MaxPooling2D twice which i think is a rule of thumb of computer vision or at least extracting features from photos. The i flattened the image, added dense layer with activation function relu so it doesnt have negative values, then at the end obviously a dense layer with 3 outputs, because there are 3 labels, which i have declared as 0,1,2 above.

I've learned a lot coding this project. I feel like i've used 30 epochs too much on training the model since the accuracy after 15 epochs was 1.0. But hey! I feel like that's still something to show off because learning on your own mistakes is the biggest reward.
I'm completely hooked on OpenCV and TensorFlow as well as ScikitLearn now. Pretty sure i'm gonna improve upon this code in the nearest future.


 
 ![alt text](prediction.png)

