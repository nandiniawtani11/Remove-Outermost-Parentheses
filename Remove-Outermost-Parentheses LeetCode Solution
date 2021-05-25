import java.lang.*;
import java.io.*;
import java.util.*;
class Solution {
    public String removeOuterParentheses(String s) {
        Stack<Character> stack=new Stack<>();
        int l=0;
        String str="";
        String str1="";
        for(int i=s.length()-1;i>=0;i--)
        {
            //System.out.println(s.charAt(i));
            if(s.charAt(i)==')')
            {
                stack.push(s.charAt(i));
                l++;
                 
            }
            else
            {
                stack.push(s.charAt(i));
                l--;
               System.out.println("Stack: " + stack);
                if(l==0)
                {
                    stack.pop();
                    while(stack.size()!=1)
                    {
                        str=str+stack.pop(); 
                        
                    }
                    stack.pop();
                    str1=str+str1;
                    str="";
                }
            }
        }
     
           return str1;
    }
}
