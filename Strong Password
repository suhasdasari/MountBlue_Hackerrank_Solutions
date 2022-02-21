public static int minimumNumber(int n, String password) {
        int small=0,caps=0,nums=0,spec=0;
        
        for(int i=0; i<n; i++){
            if(password.charAt(i) >= 'a' && password.charAt(i) <= 'z' ){
                small=1;
            }else if(password.charAt(i) >= 'A' && password.charAt(i) <= 'Z'){
                caps=1;
            }else if(password.charAt(i) >= '0' && password.charAt(i) <= '9'){
                nums=1;
            }else{
                spec=1;
            }
        }
        
        int count = small+caps+nums+spec;
        int req = 4-count;
        
        if(n+req<6){
            return 6-n;
        }else{
            return req;
        }

    }
