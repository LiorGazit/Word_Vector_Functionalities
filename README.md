# Word Vector Functionalities
This repo has a set of code chunks that leverage the associations between word vectors.

Go to the [Notebook](https://github.com/LiorGazit/Word_Vector_Functionalities/blob/master/word_vector_functionalities.ipynb) so to read about the value of **word vectors** for predictive text analytics, and for some examples and visualizations.   

**Examples**  
Words that are similar to C++:  
`analogy(['c++'], num_of_outputs=5)`  
compiler  
fortran  
compilers  
javascript  
objective-c  

****  
Word analogy: \<man\> <--> \<king\> **=** \<women\> <--> \<*???*\>  
`analogy(similar=['woman', 'king'], dissimilar=['man'], num_of_outputs=1)`  
queen   
****  
Which word doesn't belong?  
`print(model.doesnt_match("ringo john paul yoko george ".split()))`  
yoko  
