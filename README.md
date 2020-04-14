# -Hidden-markov-Model-implementation-for-Weather-prediction
This is the implementation of the hidden Markov mode from scratch for the given  discrete weather dataset. The dataset is from the kaggle.  This project deals with:

i. The state matrix and all needed probabilities such as 𝑎𝑖𝑗 𝑎𝑛𝑑 𝑏𝑗𝑘  are  calculated from given data 
II. The probability of the given observation using the Viterbi algorithm. 
III. The most probable path to generate the given observations using Decoding algorithm

Assumption :
For initialization condition, assumed that in the 𝑇(0) system is in state sunny.   

 Dataset: The dataset contains 1000 rows of past weather observations. The states (ω) are “sunny”, “rainy” and “foggy”. The emission states are “yes”, “no” indicating if an umbrella was observed. 
