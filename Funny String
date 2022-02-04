public static String funnyString(String s) {
        
        StringBuilder sb = new StringBuilder(s);        //creating a copy of String s
        ArrayList<Integer> al = new ArrayList<>();      //to store the difference
        
        for(int i=0; i<s.length()-1; i++){                          // loop to calculate the diff between numbers and adding them to ArrayList "before" reversing the string
            int diff = Math.abs(s.charAt(i)-s.charAt(i+1));
            al.add(diff);
        }
        
        sb.reverse();                                    // reverseing the string
        
        for(int j=0; j<sb.length()-1; j++){                          /// loop to calculate the diff between numbers and adding them to ArrayList "AFTER" reversing the string
            int diff = Math.abs(sb.charAt(j)-sb.charAt(j+1));
            if(al.get(j)!=diff){                         // checking the diff matches the string before reversing
                return "Not Funny";
            }
        }
        
        return "Funny";
    }
