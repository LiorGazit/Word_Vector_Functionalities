# Word Vector Functionalities
This repo has a set of code chunks that leverage the associations between word vectors.

Go to:  
- [playing_with_vector_embeddings.ipynb](https://github.com/LiorGazit/Word_Vector_Functionalities/blob/master/playing_with_vector_embeddings.ipynb)   
- [word_vector_functionalities.ipynb](https://github.com/LiorGazit/Word_Vector_Functionalities/blob/master/word_vector_functionalities.ipynb)  
There you can read about **word vectors** for predictive text analytics, and for some examples and visualizations.   

**Examples**  
Words that are similar to C++:  
`analogy(['c++'], num_of_outputs=5)`  
compiler  
fortran  
compilers  
javascript  
objective-c  

****  
Word arithmetic for: `king` - `man` + `woman`  
```
queen           (similarity: 0.7699)
monarch         (similarity: 0.6843)
throne          (similarity: 0.6756)
```

Word arithmetic for: `metallica` - `guitars` + `keyboard`
```
r.e.m.          (similarity: 0.5041)
phish           (similarity: 0.5034)
hetfield        (similarity: 0.4807)
```

Word arithmetic for: `school` - `discipline` + `sport`
```
college         (similarity: 0.6758)
sports          (similarity: 0.6738)
girls           (similarity: 0.6159)
```

****  
Which word doesn't belong?  
`print(model.doesnt_match("ringo john paul yoko george ".split()))`  
yoko  
