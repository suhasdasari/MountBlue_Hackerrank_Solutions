public static int beautifulDays(int i, int j, int k) {
        
        int count =0;
        
        for(int a=i; a<=j; a++){
            int x = a;
            int rev = 0;
            
            while(x>0){
                int num = x % 10;
                rev = rev * 10 + x % 10;
                x = x/10;
            }
            int diff = rev-a;
            
            if(diff%k == 0){
                count++;
            }
        }
        return count;
        
    }
