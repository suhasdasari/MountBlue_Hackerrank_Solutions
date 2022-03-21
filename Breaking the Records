public static List<Integer> breakingRecords(List<Integer> scores) {
        
        List<Integer> arr = new ArrayList<>();
        
        int highest=scores.get(0);
        int lowest=scores.get(0);
        int i,count=0,count1=0;
        
        for(i=1;i<scores.size();i++){
            int c = scores.get(i);
            if(c>highest){
                highest=c;
                count++;
            }
            
            if(c<lowest){
                lowest=c;
                count1++;
            }
        }
        arr.add(count);
        arr.add(count1);
        
        return arr;
        
    }
