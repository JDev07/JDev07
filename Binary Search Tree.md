

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin binary search tree ye göre 'ROOT-> 7' dir.

ROOT '7' olduğu için soluna 7 den küçük veya eşitleri sağına ise 7 den büyük ve eşitleri yazarsak;

 2. eleman "5", 7'den küçük olduğundan ilk rootun soluna yazılır.
				7
			       / 
			      5
 3. eleman "1" 7'den ve 5'ten küçük olduğu için 5'in soluna yazılır.
				7
			       / 
			      5   
			     /    
			    1      
 8, 7 den büyük olduğu için 7'nin sağına yazılır.
				7
			       / \
			      5   8
			     /    
			    1      
 3, 5'yen küçük 1'den büyük olduğu için 1in sağına yazılır.
				7
			       / \
			      5   8
			     /    
			    1      
			     \ 
		 	      3  
 6, 5'ten büyük olduğu için sağına yazılır.
				7
			       / \
			      5   8
			     / \   
			    1   6   
			     \ 
		 	      3  
 0, 1'den küçük olduğu için soluna yazılır.
				7
			       / \
			      5   8
			     / \   
			    1   6   
			   / \ 
		 	  0   3  
 9, 8'den büyük olduğu için sağına yazılır.
				7
			       / \
			      5   8
			     / \   \
			    1   6   9
			   / \ 
		 	  0   3  
 4, 5'ten küçük, 3'ten büyük olduğu için 3'ün sağına yazılır.
				7
			       / \
			      5   8
			     / \   \
			    1   6   9
			   / \ 
		 	  0   3  
			       \
			        4
 2, 3'ten küçük olduğu için soluna yazılır.
				7
			       / \
			      5   8
			     / \   \
			    1   6   9
			   / \ 
		 	  0   3  
			     / \
			    2   4
          
 şeklinde düzenleme yapılır.         
