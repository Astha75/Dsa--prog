# Dsa--prog
DSA programming questions

comparision of element
</br>

import java.util.Scanner;
</br>
class pracarray{
    public static void main(String[] args) {
         Scanner sc=new Scanner(System.in);
        System.out.println("Enter the size of array:");
        int n= sc.nextInt();
        int [] arr= new int[n];
        System.out.println("Enter the comparision element in array:");
        int x=sc.nextInt();
        System.out.println("Enter elements in array:");
        for(int i=0;i<arr.length;i++){
            arr[i]=sc.nextInt();
        }
        int count=0;
        for(int j=0;j<arr.length;j++){
            if(arr[j]>x){
                count++;
            }
        }
        System.out.println(count+ "Number is greater then"+x);
    }
}
