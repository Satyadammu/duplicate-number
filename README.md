# duplicate-number
public class Duplicatenumber {  
    public static void main(String args[]) {      
        int [] arr = new int [] {1,3,7,6,4,5,3,2,8,4,2,7};   
          
        System.out.println("Duplicate numbers are: ");  
        for(int i = 0; i < arr.length; i++) {  
            for(int j = i + 1; j < arr.length; j++) {  
                if(arr[i] == arr[j])  
                    System.out.println(arr[j]);  
            }  
        }  
    }  
}
