# Automatic-Image-Captioning
<p>I have created a simple and effective neural network architecture that includes a Vision Deep CNN and a Language Generating RNN to 
automatically generate captions from images using Microsoft Common Objects in Context (MS COCO) dataset.</p>
<h3>Image Captioning Model</h3>
<img src="https://user-images.githubusercontent.com/48044041/183286526-f8f73343-a2d0-4786-bfa3-9774bc5bfb10.png">
<p>Steps followed in this project: </p>
<p>1. The Dataset used is the COCO data set by Microsoft.</p>
<p>2. Feature vectors for images are generated using a CNN based on the ResNet architecture by Google.</p>
<p>3. Word embeddings are generated from captions for training images. NLTK was used for working with processing of captions.</p>
<p>4. Implemented an RNN decoder using LSTM cells.</p>
<p>5. Trained the network for approximately 3 hours using GPU to achieve average loss of about 2%.</p>
<p>6. Obtained outputs for some test images to understand efficiency of the trained network.</p>

<h3>Network Architecture</h3>
<img src="https://user-images.githubusercontent.com/48044041/183288691-e9e9bab7-ea77-4b72-8531-4dbd89eb309f.png" height="50%" width="70%" />

<h3>Results:</h3>
<p>These are some of the outputs given by the network using the microsoft coco dataset</p>
<img src="https://user-images.githubusercontent.com/48044041/183288795-8baa63d1-fcea-47f5-b7fe-e1511625fd82.png" height="50%" width="70%" /><br></br>
<img src="https://user-images.githubusercontent.com/48044041/183288865-66ab80a1-d603-4b60-b99c-13cb3a5af3ed.png" height="50%" width="70%"/>

