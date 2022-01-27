public static int countingValleys(int steps, String path) {
        
        int valley = 0;
        int altitude = 0;
        
        for(int i=0; i<steps; i++){
            if(path.charAt(i)=='U'){
                if(altitude==-1){
                    valley++;
                }
                altitude++;
            }
            if(path.charAt(i)== 'D'){
                altitude--;
            }
        }
        return valley;
    }
