# code-to-sum-10-num
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
     Scanner sc=new Scanner(System.in);
     float sum=0,num;

        for (int i = 0; i <= 10; i++)
        {
            System.out.println("Enter your number..:");
            num= sc.nextFloat();
            //sum+=i;
            sum+=num;
        }
        System.out.println("sum =" + sum);
    }
}
