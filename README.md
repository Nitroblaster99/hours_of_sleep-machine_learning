# hours-of-sleep

The goal of this project is to showcase, the benefits of GANs creating fake data to enrich our dataset with new features. 
In our example, we have a dataset with different features determining the hours of sleep of an average person.
Our models, don't do a good job predicting values becasue the dataset is insufficient.
Therefore, we will build a GAN model to produce new features according to our dataset.
It is important to convert all values to numerical before the GAN training, because it doesn't understand cateforical values.
Later on, we need to solve another problem. Even though our GAN converges well, the new values basically mimic and are almsot iddentical to the old values. 
Consequently, the new dataset doesn't have much divergence, as a result the prediction model also does a terrible job at predicting.
The solution here, is to decrease the number of training epochs of the GAN to a small value, so the fake features it creates are more diverse.
Thusly, our new  GAN generated dataset looks more realistic, and so our results.
