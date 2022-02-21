public static int minimumAbsoluteDifference(List<Integer> arr) {
        
        Collections.sort(arr);
        int low = arr.get(arr.size()-1);
        
        for(int i=0; i<arr.size()-1; i++){
            int diff = Math.abs(arr.get(i)-arr.get(i+1));
            low = Math.min(low,diff);
        }
        
        return low;
        
    }
