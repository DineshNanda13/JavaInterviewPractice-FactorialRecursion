# JavaInterviewPractice-FactorialRecursion
Java Program to find factorial of a number using Recursion

package fact_rec;

/**
 *
 * @author  Dinesh Nanda
 
 */
 
/**public class Fact_Rec {
    
    public int fact(int num){
        if(num <= 1){
            return 1;
        }
        else{
            return num * fact(num - 1);
        }
    }
    public static void main(String[] args) {
        Fact_Rec factorial = new Fact_Rec();
        System.out.println(factorial.fact(5));
    }
    
}
