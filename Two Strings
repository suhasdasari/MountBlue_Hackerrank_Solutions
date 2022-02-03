public static String twoStrings(String s1, String s2) {
        
        char[] arr1 = s1.toCharArray();
        char[] arr2 = s2.toCharArray();
        
        HashSet<Character> hs = new HashSet<>();
        
        for(int i=0; i<arr1.length; i++){
            hs.add(arr1[i]);
        }
        
        for(int i=0; i<arr2.length; i++){
            if(hs.contains(arr2[i])){
                return "YES";
            }
        }
        
        return "NO";
        
    }
