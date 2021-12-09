# **Question**
**[16,21,11,8,12,22] -> Array**

	a. Write the stages of the Merge Sort of the above array. 
	b. Write the Big-O natotion of the above array.

# **Answer**
  **a.**
 

      [16,21,11] - [8,12,22]
      [16,21] - [11] | [8,12] - [22]
      [16,21] - [11] | [8,12] - [22]
      [16] - [21] - [11] | [8] - [12] - [22]
      [16,21] - [11] | [8,12] - [22]
      [11,16,21] | [8,12,22]
      [8,11,12,16,21,22]
  
  **b.**
  

    O(nLogn)
