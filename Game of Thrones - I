public static String gameOfThrones(String s) {
        HashSet<Character> hs = new HashSet<>();
        for(int i=0; i<s.length(); i++){
            hs.add(s.charAt(i));
        }
        int num =0;
        
        ArrayList<Character> al = new ArrayList<>(hs);
        
        for(int i=0; i<al.size(); i++){
            int count =0;
            for(int j=0; j<s.length(); j++){
                if(al.get(i) == s.charAt(j)){
                    count++;
                }
            }
            if(count % 2 != 0){
                num++;
            }
        }
        
        if(num>1){
            return "NO";
        }else{
            return "YES";
        }
        
    }
