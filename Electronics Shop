static int getMoneySpent(int[] keyboards, int[] drives, int b) {
        int sum = 0;
        int num = 0;
        
        for(int i=0; i<keyboards.length; i++){
            for(int j=0; j<drives.length; j++){
                if(keyboards[i]+drives[j] <= b && keyboards[i]+drives[j]>num){
                    num = keyboards[i]+drives[j];
                }
            }
        }
        
        if(num==0){
            return -1;
        }else{
            return num;
        }
    }
