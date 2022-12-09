# Machine Learning for Cybersecurity
Lab2: Designing a backdoor detector for BadNets trained on the YouTube Face dataset using the pruning defense

Structure of File Directory

 ├── Lab3
 
        └── cl
        
            └── valid.h5
            
            └── test.h5
            
        └── bd
        
            └── bd_valid.h5
            
            └── bd_test.h5
            
├── models

        └── bd_net.h5
        
    	   └── bd_weights.h5
     

​       └── bd_repaired_2.h5 

​       └── bd_repaired_2_weights.h5

​       └── bd_repaired_4.h5 

​       └── bd_repaired_4_weights.h5

​       └── bd_repaired_10.h5 

​       └── bd_repaired_10_weights.h5
├── eval.py

├──  Homework-2.ipynb

For Homework-2.ipynb, just run it directly. For eval.py, run 

python3 eval.py D:/QMDownload/Python/Lab3/cl/test.h5 D:/QMDownload/Python/models/repaire\_2.h5

in the terminal.
