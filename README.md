public class MyCLass {
    public static void main(String args[]) {
        int firstNumber = 1;
        int answer = 0;
        
        for (int secondNumber =0; secondNumber<21; secondNumber++)
        {
            answer = firstNumber * secondNumber;
            System.out.println(firstNumber + " * "+ secondNumber + "= " + answer);
        }
    }
}
