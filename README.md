                          Automatic Opinion Question Generation  


 

This file contains the final report along with the code of each phase of training and testing.

The following work is done using an Encoder-decoder with an Attention mechanism to generate questions in Arabic and English. It uses a beam search decoding algorithm to generate multiple questions from one input.

To use this work, you must:

-	Use the following libraries with these exact versions: 2.3 for TensorFlow, 2.1 for Keras and 1.19 for NumPy
-	Make sure you are using GPU while training and execute the cells in the exact order.
-	This code keeps track of every checkpoint (The exact checkpoint used to generate the questions for both Arabic and 	English are in a file under the name (Checkpoint))
-	The beam function allows to generate multiple outputs from the same input 
-	To test the quality of your questions using automatic metrics use the files in (Test) with different methods for each metric.

-	For any further enquiries about this work, please contact: 
