# Main
Main program  
 public class Main1 {
 public int addition(int x, int y) {
    return x + y;
  }


  public int addition(int x, int y, int z) {
    return x + y + z;
  }

  
  public double addition(double x, double y) {
    return x + y;
  }

      public static void main(String[] args) {
      
     Main1 number = new Main1();


    int res1 = number.addition(43,78);
    System.out.println("Addition of two integers: " + res1);

    int res2 = number.addition(22,27,16);
    System.out.println("Addition of three integers: " + res2);

    double res3 = number.addition(30.15, 40.22);
    System.out.println("Addition of two doubles: " + res3);    
    }
    
}

Output:
Addition of two integers: 121
Addition of three integers: 65
Addition of two doubles: 70.37
