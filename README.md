# sudokuPuzzleKeyGenerator

The algorithm combine two partial keys to make a final key for encryption and decryption.    
The first partial key is the hash of user's passwd.   
The second partial key is the hash of sudoku puzzle solution.   
Implementing seed to achieve reproduction and backtracking to ensure uniqueness of final key.   
Adding GUI.   

Use case:    
keystr : the key to use for encryption or decryption   
N : the number of hashes to perform on the key string   
```
Key = sudokuPuzzleKey.Generator(*keystr, uint16(*N))
```