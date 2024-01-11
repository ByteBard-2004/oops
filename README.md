# oops
class MathOperation {
    protected int sum;
    public void multiplication() {
        int a = 1;
        int b = 2;
        sum = a * b; 
        System.out.println("THE a*b  OF MULTIPLICATION IS : " + sum);
    }
}
class Addition extends MathOperation {
    public void add() {
        int a1 = 5;
        int b1 = 5;
        sum = a1 + b1; 
        System.out.println("THE a+b OF ADDITION IS : " + sum);
    }
}
public class Main {
    public static void main(String[] args) {
        MathOperation m = new MathOperation(); 
        Addition a = new Addition(); 
        m.multiplication();
        a.add();
    }
}
