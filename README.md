<pre>
# Neural Network Structure
Neural network with Input layer (len(nodes) - based on words trained), 1 hidden layer (10 nodes) and Output layer (1 node)  
  
layer_0 - Input Layer  
layer_1 - Hidden Layer  
layer_2 - Output Layer  
  
Dimensions -  
Input X       - (L1_dim,)        # L1_dim = len(unique_words)  
weights_0_1   - (L1_dim,10)      # weights between Layer 0 and Layer 1  
layer_1       - (10,)            # Layer 1 Output  
weights_1_2   - (10,)            # weights between Layer 1 and Layer 2  
layer_2       - ()               # Layer 2 Output  
error_term_2  - ()               # Error term at layer 2  
error_term_1  - (10,)            # Error term at Layer 1  
  
# Steps implemented
1. Data Preprocessing
2. Bag of words approach
3. Increase accuracy - Binary Vector representation
4. Increase Computation Speed
5. Further Enhance Accuracy
6. Analysing behaviour of Weights
</pre>
