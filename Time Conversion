public static String timeConversion(String s) {
        StringBuilder sb = new StringBuilder(s);
        int len = sb.length();
        if(sb.charAt(len-2)=='A'){
            if(s.charAt(1)=='2' && s.charAt(0)=='1'){
                sb.setCharAt(0,'0');
                sb.setCharAt(1,'0');
            }
            sb.delete(len-2,len);
        }else{
            if(s.charAt(1)=='2' && s.charAt(0)=='1'){
                 sb.delete(len-2,len);
            }else{
                String str = "";
            str = str + sb.charAt(0);
            str = str + sb.charAt(1);
            int num = Integer.parseInt(str) + 12;
            String str1 = String.valueOf(num);
            sb.setCharAt(0,str1.charAt(0));
            sb.setCharAt(1,str1.charAt(1));
            sb.delete(len-2,len);
            }
            
        }
        
        return sb.toString();
        
    }
