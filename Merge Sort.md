2.Proje

 [16,21,11,8,12,22] 
 
 Merge Sort, diziyi ardışık olarak en küçük alt dizilerine kadar yarılayan sonra da onları sıraya koyarak birleştiren ve yineleyen bir algoritmadır. 
 
  Yukarıda verilen dizinin sort türüne göre aşamalarını oluşturacak olursak;
				

				[16,21,11,8,12,22]
        
				  /            \
		 	  [16,21,11]          [8,12,22]
        
			   /      \            /      \
			[16,21]   [11]       [8,12]   [22]
      
                         /   \      |        /   \      |
		      [16]  [21]   [11]    [8]  [12]   [22]
          
                        \    /       |       \    /      |
                        
			[16,21]    [11]      [8,12]    [22]
      
			   \        /		\       /
			   [11,16,21]           [8,12,22]
         
			       \                    /
			         [8,11,12,16,21,22]
               

  Big-O gösterimi:
  

	Big-O: O(nlogn)
