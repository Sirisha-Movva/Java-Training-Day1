# Java-Training-Day1
Java Language -> Object Oriented 
			8 -> Functional Programming
			
		Rich Clients - Core Java
		Thin Client(Web Application)  - Servlet + JSP
											------------> HTML + JavaScript + CSS
		Web Application(MVC+RIA)	  - Struts / Spring framework
............................................
...........................................
    Development

1. Rich Client
		Download exe, install
		RAM, CPU, 

2. Thin Client
		Web Applications
		Browser + Network connectivity

3. Rich Internet Applications (RIA)
		Web Application(Server Side) + 
				Browser(Html + Javascript + CSS)
.......................................
........................................
        Lab 1- 
	class Lab1
		{
		 public static void main(String[] args) {
				String firstname ="Vaishali";
				String lastname = "Tapaswi";
				String name = firstname + "  " + lastname;
				System.out.println("Hello World - Lab1");
				System.out.println(name);
			}
		}

	repeat the code
	
	Lab2 --> create two variables -> one string (name) and int (marks)
		intiailze it to yourname and marks as 55
		print the details
		class Lab2{
			public static void main(String[] args){
				String name = "aaa";
				int marks = 20;
				System.out.println("Name = " + name  + ", Marks = " + marks);
			}
		}
    ......................................................
    .....................................................
    Conditional Statements (https://www.tutorialspoint.com/compile_java_online.php)

Lab3 - show "Pass" if marks >=35
public class Lab3{

     public static void main(String []args){
        String name  = "Seema";
        int marks = 20;
        if (marks >= 35)
            System.out.println("Student Name " + name + ", status is PASS" );
        else
            System.out.println("Student Name " + name + ", status is FAIL" );
            
     }
}
..................................
...................................
Lab 4 - Print odd or even for given number) -> single vs multiple lines
	public class Lab4{

	     public static void main(String []args){
		int num= 20;
		if ((num%2)==0){
			System.out.println("Number is Even");
			System.out.println("Some description of even numbers");
			}
		else
			System.out.println("Number is Odd");
	     }
	}
  ...............................
  ..............................
  Lab 5 - switch case (https://www.w3schools.com/java/java_switch.asp)
	initialize a string variable and based on length of that string show message and small name. big name (if else) (if length >5 big else small)
	initialize a string variable and based on length of that string show message and small name. mid size, big name, biggest (switch)
				0..5 -> small name
				6..10 -> mid
				11..15 -> big name
	public class Lab5{

     public static void main(String []args){
      String name = "aaaaaaa";
	
    System.out.println("Length = " + name.length() );
 
	switch (name.length()) {
	  case 1:
	  case 2:
	  case 3:
	  case 4: 
	  case 5:
	    System.out.println("Length is less than or equal to 5 which means small name ");
	    break;
	  case 6:
	  case 7:
	  case 8:
	  case 9:
	  case 10:
		    System.out.println("Lenght is greater than 5 and less than or equal to 10, which means mid size name");
	    break;
	}
	//--------------------------------------------
	if (name.length() <= 5)
		  System.out.println("Length is less than or equal to 5 which means small name ");
	else if (name.length() <= 10)
		 System.out.println("Lenght is greater than 5 and less than or equal to 10, which means mid size name"); 
	}
	}
  ....................................
  ........................................
  Lab 6 - For 
	int count = 13;
    	System.out.println("Current Value = " + count);
	for(int i = 0; i< count;i++){
		System.out.println("Current i = "+ i);
	}
  ...................
  ...................
  Lab 7 - while 
public class Lab7{

     public static void main(String []args){
	int count = 20;
	while(count > 10){
		System.out.println("count is less than 10");
		// count = count  - 1 
		count--;
	}
}
}
............................
...............................
Lab 8 - create a varialbe name and assign some value...
	use for loop to print hello as many times as string length.
  ............................
  ................................
  Lab 9
	Create a variable sum = 150 and write a while (sum <=200) -> to add 1 in each iteration.
