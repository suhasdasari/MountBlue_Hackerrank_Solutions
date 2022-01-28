static int jumpingOnClouds(int[] c, int k) {
        
        int e =100;
        int jump = 0;
        
        for(int i=0; i<c.length; i++){
            
            jump = (jump+k)%c.length;
            
            if(c[jump] == 1){
                e = e -2-1;
            }else{
                e = e -1;
            }
            
            if(jump == 0){
                break;
            }
            
        }
        
        return e;


    }
