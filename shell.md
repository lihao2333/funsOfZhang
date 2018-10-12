## shell
Q:表示不连贯的数字  
A:`echo {1..11..2}` ==>`1 3 5 7 9`  
A:`perl -E 'map{say if $_%2==1}(1..11)'`  

