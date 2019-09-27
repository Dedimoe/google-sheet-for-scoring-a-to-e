# google-sheet-for-scoring-a-to-e
google-sheet-for-scoring-a-to-e


> 3.5 - 4.0 score A

> 2.5 - 3.5 score B

> 1.5 - 2.5 score C

> 0.5 - 1.5 score D

> 0   - 0.5 score E

''''
=IF(AND(K5=0, K5<=0.5), "E", IF(AND(K5>0.5, K5<=1.5), "D", IF(AND(K5>1.5, K5<=2.5), "C", IF(AND(K5>2.5, K5<=3.5), "B", IF(AND(K5>3.5, K5<=4), "A", "Undefined")))))
''''
