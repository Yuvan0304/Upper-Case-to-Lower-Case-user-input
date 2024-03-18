# Upper-Case-to-Lower-Case-user-input

Program:

import java.util.*;
public class Main
{
  public static void main (String[]args)
  {
    Scanner sc=new Scanner(System.in);
	String s1 = new String();
	System.out.print("Eter the word");
    s1 =sc.nextLine();
    String s1lower=s1.toLowerCase();
    System.out.print("The word is:");
    System.out.print(s1lower);
  }}
