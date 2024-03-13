# T-pattern
I have completed T pattern program in java
public class Main {
    public static void main(String[] args) {
        int size = 5;

     
        for (int i = 0; i < size; i++) {
      
            for (int j = 0; j < size; j++) {
               
                if (j == size / 2 || i == 0)
                    System.out.print("*");
                else
                    System.out.print(" ");
            }
    
            System.out.println();
        }
    }
}

