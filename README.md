<h2>Find Outliers with AutoEncoder - Full Tutorial </h2>

<p>
This video shows hot to find outliers in data by using AutoEncoders. This approach relies on reconstruction errors calculated by AutoEncoders which can be trained in your Jupyter Notebook with Python programming language very quickly. In this video we will setup a very simple AutoEncoder which consists of Encoder and Decoder.<br>

For this example I used a circle-shaped data distribution, but this approach will work for any shape of data distribution. The main idea is that Encoder compress the input data which results in less dimensions of data and then the Decoder attempts to reconstruct the compressed data back to original data distribution. <br>

These data points which are not outliers has low reconstruction error, while these data points which are far away from dominating data distribution (circle-shape in this example) are identified as anomaly or outliers.<br>

To setup an autoencoder with encoder and decoder, I used Tensorflow 2.10 in this video tutorial.<br>
During the video I ofter visualize the data to better understand what is going on behind to open Black box of the main idea for you.<br>

Before ingesting the initial input to Decoder part, we must to convert our numerical data representation into Tensorflow Tensor. Tensor is that format which is readable for Artificial Neural Network (ANN) in many architectures (Tensorflow, PyTorch, etc.). By having this, we are ready to train our AutoEncoder. I also suggest to apply numpy method to the tensor to be sure that the data type of our tensor is float (floating number).<br>

To calculate the reconstruction errors for our data points we use the MSE (Mean Squared Error) loss function. It is enough to find outliers (anomalies) in our dataset.<br>
</p>


Link to the full video tutorial: [!!! YOUTUBE VIDEO !!!](https://youtu.be/f3FY7ZmoFN4)
