# Generative-Adversarial-Networks

Generative adversarial networks are implicit likelihood models that generate data samples from the statistical distribution of the data. They’re used to copy variations
within the dataset. They use a combination of two networks: generator and discriminator.


![image](https://user-images.githubusercontent.com/124021133/218245614-333ba082-a8c8-4320-a1db-9935bf3f480f.png)


#Generator

A generator network takes a random normal distribution (z), and outputs a generated sample that’s close to the original distribution.

#Discriminator

A discriminator tries to evaluate the output generated by the generator with the original sample, and outputs a value between 0 and 1. If the value is close to 0, then the generated sample is fake, and if the value is close to 1 then the generated sample is real.


Some of the result:

-----------------------------------------------------------------------



![download (1)](https://user-images.githubusercontent.com/124021133/218485066-8d4a53da-c7fb-4f8b-9646-00f08323019f.png)
![download](https://user-images.githubusercontent.com/124021133/218485077-7fae7bd5-ddce-491e-afb1-8cfc4a594bcc.png)



------------------------------------------------------------------------


Model produce a image of Zero . Note : It has never seen a image of zero . 

Some of the application of GAN :
-Creating human faces which can be used in video games .
-Generating Cartoon Character 
-Face Aging 
-Generating images in medicine or material science , where there's a very few data .
