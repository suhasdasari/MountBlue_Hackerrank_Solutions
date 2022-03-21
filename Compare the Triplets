public static List<Integer> compareTriplets(List<Integer> a, List<Integer> b) {
        
        ArrayList<Integer> list = new ArrayList<>();
        int alice = 0;
        int bob =0;
        
        for(int i=0; i< a.size() && i<b.size(); i++){
            int x = a.get(i);
            int y = b.get(i);
            
            if(x>y){
                alice++;
            }
            if(y>x){
                bob++;
            }
        }
        list.add(alice);
        list.add(bob);
        
        return list;
    }
