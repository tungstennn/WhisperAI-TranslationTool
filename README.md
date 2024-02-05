This is the code for the utilzation of WhisperAI, the code is engineered to run through and test an audio file twice (test1, test2), iterating through each mode (base, small, medium, large) and outputs a transcript and a translation of the audio provided into a .txt file.
This provides a simple and reliable way to visually compare the repeatability and accuracy of the differernt models.

Things to add-on/improve:
- This code is very dependent on the local machine running it. To make this code more reliable, deploy an EC2 instance that can handle the workload while also minimizing costs.
- Find a way to quantify the repeatability and accuracy of the language models (using a 3rd party translation tool, such as google translate)
- Using a large database of audio files for a specific language, attempt to train the model to yield a greater accuracy and repeatability
