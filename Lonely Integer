public static int lonelyinteger(List<Integer> a) {
        
        HashSet<Integer> hs = new HashSet<>();
        
        for(int i=0; i<a.size(); i++){
            int x = a.get(i);
            if(hs.contains(x)){
                hs.remove(x);
            }else{
                hs.add(x);
            }
        }
        
        ArrayList<Integer> al = new ArrayList<>(hs);
        int unique = al.get(0);
        
        return unique;
    }
