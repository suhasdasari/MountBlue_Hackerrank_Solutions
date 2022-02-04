public static long taumBday(int b, int w, int bc, int wc, int z) {
        
        long sum;
        long b1 = b;
        long w1 = w, bc1=bc,wc1 = wc,z1=z;
        if(wc1+z1 < bc1){
            sum = w1*wc1 + b1*(wc1+z1);
        }else if(bc+z < wc){
            sum = b1*bc1 + w1*(bc1+z1);
        }else{
            sum = b1*bc1 + w1*wc1;
        }
        return sum;
    }
