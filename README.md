# SECOND-LARGEST-ELEMENT-OF-THE-ARRAY
import java.util.*;
class HelloWorld {
    public static void main(String[] args) {
        int a[];
        a=new int[100];
        int l=0;
        int sl=0;
        Scanner sc= new Scanner(System.in);
        int n=sc.nextInt();// Array length
        for(int i=0;i<n;i++){
            int k=sc.nextInt();
            if (k>l){
            a[0]=k;
            sl=l;
            }
            l=a[0];
        }
        System.out.print(sl+" is the arrays largest element ");
    }
  }
