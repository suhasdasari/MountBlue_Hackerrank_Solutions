public static String pangrams(String s) {
        
        String a = s.toLowerCase();
        HashSet<Character> hs = new HashSet<>();
        
        if(a.length()<26){
            return "not pangram";
        }
        
        for(int i=0; i<a.length(); i++){
            if(a.charAt(i)>='a' && a.charAt(i)<='z'){
                hs.add(a.charAt(i));
            }
        }
        
        if(hs.size()==26){
            return "pangram";
        }else{
            return "not pangram";
        }
    }
