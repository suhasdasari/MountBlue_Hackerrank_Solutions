public static int beautifulTriplets(int d, List<Integer> arr) {
        
        int i,j,k;
        int count =0;
        
        for(i=0;i<arr.size()-2;i++){
            for(j=i+1;j<arr.size()-1;j++){
                if(arr.get(j)-arr.get(i) == d){
                for(k=i+2;k<arr.size();k++){
                    if(arr.get(i)<arr.get(j) && arr.get(j)<arr.get(k)){
                        if(arr.get(k)-arr.get(j) ==d){
                            count++;
                        }
                    }
                }
                }
            }
        }
        
        return count;
    }
