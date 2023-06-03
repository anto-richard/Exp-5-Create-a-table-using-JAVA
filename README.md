# Exp-5-Create-a-table-using-JAVA...

## AIM:

To write a java program to create a table.

## ALGORITHM:

### Step 1:

Import the necessary packages.

### Step 2:

Create a Class named 'Employee' which has data members.

### Step 3:

Create methods in the class 'Employee'.

### Step 4:

Print the details of the employees.

### Step 5:

End the program.

## PROGRAM:

```java

Name   : Anto Richard. S
Reg No : 212221240005

public class EmpHist 
{ 
    public static void main(String[] args) 
    { 
          Employee emp1 = new Employee(); 
          emp1.name = "Robert"; 
          emp1.year_of_joining = 1994; 
          emp1.address = "64C- WallsStreat";
          
          Employee emp2 = new Employee(); 
          emp2.name = "Sam"; 
          emp2.year_of_joining= 2000; 
          emp2.address = "68D- WallsStreat";
          
          Employee emp3 = new Employee(); 
          emp3.name = "John"; 
          emp3.year_of_joining = 1999; 
          emp3.address = "26B- WallsStreat"; 
          
          emp1.disp(); 
          emp1.display(); 
          emp2.display(); 
          emp3.display(); 
     } 
}

public class Employee 
{ 
    String name; 
    int year_of_joining; 
    String address; 
    public void disp() 
    { 
        System.out.println("Name\t Year of Joining\t \t Address"); 
    } 
    public void display() 
    { 
        System.out.println(name + "\t" + year_of_joining + "\t" + "\t" + address); 
    } 
}

```

## OUTPUT:

![g1](https://github.com/anto-richard/Exp-5-Create-a-table-using-JAVA/assets/93427534/5263fade-b0de-4f48-a612-845f47f67260)


## RESULT:

Thus the java program to create a table is executted successfully.
