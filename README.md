# 类型转换-java
package the_first_one;
import java.util.Scanner;
import java.util.Random;
public class the_first {
	public class DoubleToIntconverts {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
    double input = 1231224141123.3232;
    int result = truncateDoubleToInt(input);}
        public static int truncateDoubleToInt(double value) {
        	if (value < Integer.MIN_VALUE||value>Integer.MAX_VALUE) {
        		throw new IllegalArgumentException("值超出 int 类型的范围");
        	}
        	return (int) value;
        }
       
    		   
       
	}}
