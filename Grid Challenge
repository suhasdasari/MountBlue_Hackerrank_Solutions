public static String gridChallenge(List<String> grid) {
        
        ArrayList<String> al = new ArrayList<>();
        
        for(int i=0; i<grid.size(); i++){
            
            String str = grid.get(i);
            char[] arr = str.toCharArray();
            Arrays.sort(arr);
            al.add(String.valueOf(arr));
        }
        
        for(int j=0; j<al.size()-1; j++){
            for(int k=0; k<al.size(); k++){
                if(al.get(j).charAt(k) > al.get(j+1).charAt(k)){
                    return "NO";
                }
            }
        }
        
        return "YES";
        
    }
