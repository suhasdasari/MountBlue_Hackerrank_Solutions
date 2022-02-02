public static int chocolateFeast(int n, int c, int m) {
        
        int num = n/c;
        int wrap=0,extra=0,sum=0;
        
        while(num>0){
            sum = sum + num;
            wrap = num + extra;
            num = wrap/m;
            extra = wrap % m;
        }
        
        return sum;
        
    }
