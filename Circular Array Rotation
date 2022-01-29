public static List<Integer> circularArrayRotation(List<Integer> a, int k, List<Integer> queries) {
        
        ArrayList<Integer> al = new ArrayList<>();
        
        for(int i=0; i<k; i++){
            a.add(0,a.get(a.size()-1));
            a.remove(a.size()-1);
        }
        
        for(int i=0; i<queries.size(); i++){
            int x = queries.get(i);
            al.add(a.get(x));
        }
        
        return al;
        
    }
