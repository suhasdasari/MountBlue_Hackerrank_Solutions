public static int sockMerchant(int n, List<Integer> ar) {
        HashSet<Integer> set = new HashSet<>();
        int i,count=0;
        
        for(i=0;i<n;i++){
            int a = ar.get(i);
            if(set.contains(a)){
                set.remove(a);
                count++;
            }else{
                set.add(a);
            }
        }
        return count;
        
    }
