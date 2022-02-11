public static int toys(List<Integer> w) {
        Collections.sort(w);
        int low = w.get(0);
        int count =1;
        
        for(int i=1; i<w.size(); i++){
            int num = w.get(i);
            if(num > 4+low ){
                low = w.get(i);
                count++;
            }
        }
        
        return count;
        
    }
