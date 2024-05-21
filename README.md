# leaf
The Leaf.ipynb is the core model code , where the model is trained and validated on varaious datasets of plants which contain Healthy and diseased.
The model.ipynb is the prediction code of the model , where we deployed a streamlit application using local tunnel .
The Streamlit application can be accessed by running the model.ipynb code , It contains a specifc snippet where it shows the local tunnels provate key which then used as a password to access the webpage [https://leaf.loca.lt/].
The webpage contains 2 options of inserting an image, where u can insert the image as an url format or can upload directly from ur host system. Then the webpage classifies the image and shows the predicted output which is the leafs name and the probability of its score.
