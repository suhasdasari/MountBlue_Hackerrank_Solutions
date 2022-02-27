public static int sansaXor(List<Integer> arr) {
        
        int xor = arr.get(0);
        
        if(arr.size()%2 == 0){
            return 0;
        }
        
        for(int i=2; i<arr.size(); i=i+2){
            
            int num = arr.get(i);
            xor = (xor & (~num)) | ((~xor) & num);
        }
        
        return xor;
        
        
    }
