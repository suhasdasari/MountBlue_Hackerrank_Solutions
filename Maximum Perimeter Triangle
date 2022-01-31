public static List<Integer> maximumPerimeterTriangle(List<Integer> sticks) {
        
        Collections.sort(sticks);
        ArrayList<Integer> al = new ArrayList<>();
        int i =sticks.size()-3;
        
        while(i>=0){
            
            if(sticks.get(i) + sticks.get(i+1) > sticks.get(i+2)){
                break;
            }else{
                i -= 1;
            }
        }
        
        if(i<0){
            al.add(-1);
        }else{
            al.add(sticks.get(i));
            al.add(sticks.get(i+1));
            al.add(sticks.get(i+2));
        }
        
        return al;

    }
