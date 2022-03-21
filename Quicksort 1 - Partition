public static List<Integer> quickSort(List<Integer> arr) {
        ArrayList<Integer> left = new ArrayList<>();
        ArrayList<Integer> equal = new ArrayList<>();
        ArrayList<Integer> right = new ArrayList<>();
        
        int pivot = arr.get(0);
        
        for(int i=0;i<arr.size();i++){
            int num = arr.get(i);
            
            if(num<pivot){
                left.add(num);
            }else if(num>pivot){
                right.add(num);
            }else{
                equal.add(num);
            }
        }
        
        ArrayList<Integer> fin = new ArrayList<>();
        fin.addAll(left);
        fin.addAll(equal);
        fin.addAll(right);
        
        return fin;
    }
