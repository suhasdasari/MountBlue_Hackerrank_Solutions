public static int libraryFine(int d1, int m1, int y1, int d2, int m2, int y2) {
        
        int fine = 0;
        
        if(d1<=d2 && m1<= m2 && y1<=y2 ){
            fine = 0;
        }
        if(y1==y2 && m1==m2 && d1>d2){
            int a = d1-d2;
            fine = a * 15;
        }
        if(y1==y2 && m1>m2){
            int b = m1-m2;
            fine = b * 500;
        }
        if(y1>y2){
            int c = y1-y2;
            fine = c * 10000;
        }
        return fine;
    }
