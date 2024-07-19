                          Automatic Question Generation -ARABIC-


This work is done by: A.Rahma & L.Bahri under the supervision of L.Ouahrani

This file contains the final report along with code of each phase training, testing and the interface using Tkinter.

The following work is done using an Encoder-decoder with Attention mechanism to generate questions in Arabic and English language. It uses a beam search decoding algorithm in order to generate multiple questions from one input.

In order to use this work, you must:

-	Use the following libraries with these exact versions: 2.3 for Tensorflow, 2.1 for Keras and 1.19 for NumPy
-	This dataset set is already splitted (80% & 20%), make sure to split yours and leave the 20% for the test phase.
-	Make sure you are using GPU while training and execute the cells in the exacte order.
-	This code keeps track of every checkpoint (The exacte checkpoint used to generate the questions for both Arabic and 	English are in a file under the name (Checkpoint))
-	The beam function allows you to generate multiples outputs from the same input 
-	To test the quality of your questions using automatic metrics use the files in (Test) with different methods for each 	metric.

-	For any further enquiries about this work, please contact: 
  amirarahma.aa@gmail.com
  lylia.g1.25@gmail.com 
