# plant classification

classifies plants as either poison ivy, dandelions, or tulips

applies grad-cam to different images based on trained neural network

used gradcam to identify potential biases in dataset

Due to the distinct background for each image class, my image classifier had been trained to recognize the background of the image rather than the plant itself. Modified my datasets so that it would include images that have very different backgrounds. By using Grad-CAM in conjunction with my machine model, I was able to increase the classifier’s efficiency to 94.6%, which was much better than the high 70s and low 80s. 
