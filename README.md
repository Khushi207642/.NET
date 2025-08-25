# .NET
Practical 1
-1.1

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace P1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello");
            Console.WriteLine("I'm Khushi Panchal");
            Console.WriteLine("Course : B.C.A ");

        }
    }
}

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c0805b7a-0b5b-4a77-916f-120da343c0b4" />

~ 1.2

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = 10;
            double f = 6.7;
            char c='A';
            string s = "C#";
            bool flag = true;

            Console.WriteLine(num);
            Console.WriteLine(f);
            Console.WriteLine(c);
            Console.WriteLine(s);
            Console.WriteLine(flag);
        }
    }
}

<img width="1465" height="331" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/e09c6a0f-50e9-43d3-ba56-cfb76d57c3ca" />

~ 1.3

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p3
{
    class Program
    {
        static void Main(string[] args)
        {
            int num = 25;
            double d = num;
            Console.WriteLine("Integer Value " +num);
            Console.WriteLine("Double value after implicit conversion : " + d); 
        }
    }
}

 <img width="1450" height="190" alt="image" src="https://github.com/user-attachments/assets/d9b8e0dd-ef87-470c-878e-00a24db62ccf" />

~ 1.4

using System;
using System.Collections.Generic;
using System.Linq;
using System.Runtime.Remoting.Metadata.W3cXsd2001;
using System.Text;
using System.Threading.Tasks;

namespace p4
{
    class Program
    {
        static void Main(string[] args)
        {
            double d=6.7;
            int num = (int)d;

            Console.WriteLine("Double value : "+d);
            Console.WriteLine("Integer value explicit conversion " + num);
            
           
        }
    }
}
 <img width="461" height="77" alt="image" src="https://github.com/user-attachments/assets/c0aa1a7a-4017-4840-b270-cd07d1ff8092" />

~ 1.5

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace P5
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter marks of subject 1 ");
            int m1=int.Parse(Console.ReadLine());
            Console.Write("Enter marks of subject 2 ");
            int m2= int.Parse(Console.ReadLine());

            int total = m1 + m2;
            Console.WriteLine("Total Marks " +total);

        }
    }
}
  <img width="373" height="98" alt="image" src="https://github.com/user-attachments/assets/d0609091-8be3-4852-a29b-455b18245657" />

~ 1.6

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p6
{
    class Program
    {
        static void Main(string[] args)
        {
            int Price1 = 10;
            int Price2 = 20;

            Console.WriteLine("Before Swapping");
            Console.WriteLine("Price 1 " + Price1);
            Console.WriteLine("Price 2 "+ Price2);

            int temp = Price1;
            Price1 = Price2;
            Price2 = temp;

            Console.WriteLine("After swapping ");
            Console.WriteLine("Price 1 " + Price1);
            Console.WriteLine("Price 2 "+Price2);
        }
    }
}

 <img width="312" height="157" alt="image" src="https://github.com/user-attachments/assets/96e708df-a6a9-498f-82d8-8f8755d589b9" />

~ 1.7

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p7
{
    class Program
    {
        static void Main(string[] args)
        {
            int rollNumber;

            Console.Write("Enter your roll number: ");
            rollNumber = int.Parse(Console.ReadLine());

            if (rollNumber % 2 == 0)
            {
                Console.WriteLine("The roll number is even.");
            }
            else
            {
                Console.WriteLine("The roll number is odd.");
            }
        }
    }
}

 <img width="353" height="79" alt="image" src="https://github.com/user-attachments/assets/63f7f049-6b6b-4cc2-aa70-2c122c88c5be" />

~ 1.8

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p8
{
   class Program
    {
        static void Main(string[] args)
        {
            double side = 5.0;
            double area = side * side;
            Console.WriteLine("Side length of square : " + side);
            Console.WriteLine("Area of the square : " + area);

        }
    }
}

 <img width="361" height="77" alt="image" src="https://github.com/user-attachments/assets/cd5978ac-1067-4b0f-a248-034a426646dd" />


~ 1.9

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p9
{
    class Program
    {
        static void Main(string[] args)
        {
            int number = 50;

            // Boxing: converting int to object
            object boxedValue = number;

            // Display the values
            Console.WriteLine("Original int value: " + number);
            Console.WriteLine("Boxed object value: " + boxedValue);
        }
    }
}

 <img width="295" height="66" alt="image" src="https://github.com/user-attachments/assets/05b4eb51-194a-4b7d-8c6a-1d1206a13f96" />


~ 1.10

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p10
{
    internal class Program
    {
        static void Main(string[] args)
        {
            object boxedValue = 100;

            // Unboxing: converting the object back to int
            int unboxedValue = (int)boxedValue;

            // Display the unboxed value
            Console.WriteLine("Unboxed int value: " + unboxedValue);
        }
    }
}

 <img width="310" height="63" alt="image" src="https://github.com/user-attachments/assets/16d5519e-e540-4ce9-871c-2cf7166f7840" />


~ 1.11

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace P11
{
    class Program
    {
        static void Main(string[] args)
        {
            int age;

            Console.Write("Enter your age: ");
            age = int.Parse(Console.ReadLine());

            if (age >= 18)
            {
                Console.WriteLine("You are eligible to vote.");
            }
            else
            {
                Console.WriteLine("You are not eligible to vote.");
            }
        }
    }
}

 <img width="335" height="74" alt="image" src="https://github.com/user-attachments/assets/bc7d44b3-3616-4ac8-afcf-518f77345fa2" />



PRACTICAL 2

~ 2.1

USING FOR LOOP

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num, fact = 1;
            Console.Write("Enter a Number");
            num = Convert.ToInt32(Console.ReadLine());
            for (int i = 1; i <= num; i++)
                fact *= i;
            Console.WriteLine("Factorial using loop = " + fact);
        }
    }
}

 <img width="367" height="69" alt="Screenshot 2025-08-04 040808" src="https://github.com/user-attachments/assets/7d382e62-bfdb-4d67-b0c8-2da84666ebd1" />



USING WHILE LOOP

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num, fact = 1,i=1;
            Console.Write("Enter a Number");
            num = Convert.ToInt32(Console.ReadLine());
            while (i <= num)
            {
                fact *= i;
                i++;
            }
            Console.WriteLine("Factorial using loop = " + fact);
        }
    }
}
 <img width="354" height="81" alt="image" src="https://github.com/user-attachments/assets/d7086753-1a45-47b2-8328-7258b3fbbb3a" />

~ 2.2

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num,i,count=0;
            Console.WriteLine("Enter a Number");
            num=Convert.ToInt32(Console.ReadLine());
            if(num<=1)
            {
                Console.WriteLine("Not a prime number");
                return;
            }

            for (i = 1; i <= num; i++)
            {
                if (num % i == 0)
                {
                    count++;
                }

            }

            if (count == 2)
            {
                Console.WriteLine("Prime Numbers");
            }
            else
            {
                Console.WriteLine("Not a prime number");
            }
        }
    }
}

 <img width="282" height="86" alt="image" src="https://github.com/user-attachments/assets/47103401-94df-4d1e-bc83-b15ecc52eb67" />

~ 2.3

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num, remainder,reverse=0;
            Console.Write("Enter a number : ");
            num=Convert.ToInt32(Console.ReadLine());
            while(num!=0)
            {
                remainder = num % 10;
                reverse = reverse * 10 + remainder;
                num /= 10;
            }
            Console.Write("Reversed Number : " + reverse);
        }
    }
}
 <img width="320" height="65" alt="image" src="https://github.com/user-attachments/assets/682b0397-14ee-465d-94e3-080b27c38f65" />


~ 2.4

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int original, num ,reverse=0,digit;
            Console.Write("Enter a number : ");
            original=Convert.ToInt32(Console.ReadLine());
            num=original;
            
            while(num!=0)
            {
                digit = num % 10;
                reverse = reverse * 10 + digit;
                num/=10;    
            }
            Console.WriteLine("Reverse Number : " + reverse);

            if (original == reverse)
            {
                Console.WriteLine("It is Palindrome");
            }
            else
            {
                Console.WriteLine("It is not palindrome");
            }
        }
    }
}

 <img width="282" height="80" alt="image" src="https://github.com/user-attachments/assets/d5131cfe-7e36-46ad-afda-2df940bc12ea" />

~ 2.5

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int num, sum = 0, digit;

            Console.Write("Enter a Number : ");
            num=Convert.ToInt32(Console.ReadLine());

            while (num != 0)
            {
                digit = num % 10;
                sum += digit;
                num /= 10;
            }
            Console.WriteLine("Sum of Digit : " + sum);
        }
    }
}

 <img width="281" height="57" alt="image" src="https://github.com/user-attachments/assets/06269075-313a-4cd3-bf2f-2940cd216f27" />

~ 2.6

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading;
using System.Threading.Tasks;

namespace Practical_2
{
    class Program
    {
        static void Main(string[] args)
        {
            int subject1, subject2, subject3;
            int total;
            double average;

            Console.Write("Enter marks for Subject 1: ");
            subject1 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter marks for Subject 2: ");
            subject2 = Convert.ToInt32(Console.ReadLine());

            Console.Write("Enter marks for Subject 3: ");
            subject3 = Convert.ToInt32(Console.ReadLine());

            total = subject1 + subject2 + subject3;
            average = total / 3.0;

            Console.WriteLine("\nTotal Marks: " + total);
            Console.WriteLine("Average Marks: " + average);

            if (average >= 80)
            {
                Console.WriteLine("Grade: A");
            }
            else if (average >= 60)
            {
                Console.WriteLine("Grade: B");
            }
            else if (average >= 40)
            {
                Console.WriteLine("Grade: C");
            }
            else
            {
                Console.WriteLine("Grade: F");
            }

        }
    }
}

 <img width="568" height="207" alt="image" src="https://github.com/user-attachments/assets/c55d258f-de75-4dc0-b29e-4a79b7096dfa" />




Practical 3

~ 3.1
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string name = "Khushi";
            Console.WriteLine("Name : "+name);
            string sub = name.Substring(0, 2);
            Console.WriteLine("First three characters : " + sub);
        }
    }
}

 <img width="448" height="75" alt="image" src="https://github.com/user-attachments/assets/6cec1741-4d8d-456b-926d-0cd9c6978b49" />

~(for own purpose)

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string name = "Khushi panchal";
            Console.WriteLine("real : "+name);
            string newstr = name.Replace("Khushi", "Khush");
            Console.WriteLine("New replace is : "+newstr);
        }
    }
}


  <img width="436" height="65" alt="image" src="https://github.com/user-attachments/assets/04cabd33-aa11-4365-8000-c92cb3fa137c" />

~3.2
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter a sentence : ");
            string sen=Console.ReadLine();


            Console.WriteLine("Enter a word to replace : ");
            string old = Console.ReadLine();

            Console.WriteLine("Enter a new word : ");
            string newword= Console.ReadLine();

            string replaced=sen.Replace(old, newword);
            Console.WriteLine("Modify sentence : " + replaced);
        }
    }
}

 <img width="413" height="194" alt="image" src="https://github.com/user-attachments/assets/b98c9d7d-1eda-4be6-9941-cc9b5c603d60" />

~3.3

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter a sentence : ");
            string sen = Console.ReadLine();
            string[] word = sen.Split(' ');
            Console.WriteLine("Words to be : ");
            for(int i=0; i<word.Length; i++)
            {
                if(word[i]!="")
                {
                    Console.WriteLine(word[i]);
                }
            }


        }
    }
}

  <img width="298" height="143" alt="image" src="https://github.com/user-attachments/assets/a20e730a-1ceb-4e80-85c0-981d7aa40e4a" />


  ~3.4

  using System;
using System.Text;

namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter a sentence: ");
            string sentence = Console.ReadLine();

            StringBuilder st = new StringBuilder(sentence);

            Console.Write("Enter a string to append: ");
            string appendText = Console.ReadLine();

            st.Append(" " + appendText);

           
            Console.WriteLine("\nUpdated String: " + st.ToString());
        }
    }
}

 <img width="434" height="114" alt="image" src="https://github.com/user-attachments/assets/589b7c70-823f-4177-831c-b24dfb54028d" />



~3.5

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace p23
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Enter a sentence : ");
            string sen = Console.ReadLine();

            StringBuilder sb = new StringBuilder(sen);
            Console.Write("Enter what to do : ");

            string extra = Console.ReadLine();
            Console.Write("Enter position number :");

            int pos = int.Parse(Console.ReadLine());
            sb.Insert(pos, extra);
            Console.WriteLine("After insertion : " + sb.ToString());
        }
    }
}


 <img width="467" height="129" alt="image" src="https://github.com/user-attachments/assets/41537831-e445-4b7c-8478-9451c053bf8d" />

Practical 4

~4.1

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp3
{
    class Program
    {
        static void Main(string[] args)
        {
            int[] intarray;
            intarray = new int[5];
            intarray[0] = 10;
            intarray[1] = 20;
            intarray[2] = 30;
            intarray[3] = 40;
            intarray[4] = 50;
            int Length=intarray.Length;
            for (int i = 0; i < intarray.Length; i++)
            {
                Console.WriteLine("" + intarray[i]);
            }
        }
    }
}

 <img width="355" height="148" alt="image" src="https://github.com/user-attachments/assets/c67cb89a-c5c7-4b23-a1ad-b4936f8fb8df" />

~4.2


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

struct Book
{
    public int BookID;
    public string Title;
    public string Author;
    public double Price;
}

class Program
{
    static void Main(string[] args)
    {
        // Create array of 3 books
        Book[] books = new Book[3];

        // Taking input for 3 books
        for (int i = 0; i < 3; i++)
        {
            Console.WriteLine($"\nEnter details of Book {i + 1}:");

            Console.Write("Enter Book ID: ");
            books[i].BookID = int.Parse(Console.ReadLine());

            Console.Write("Enter Title: ");
            books[i].Title = Console.ReadLine();

            Console.Write("Enter Author: ");
            books[i].Author = Console.ReadLine();

            Console.Write("Enter Price: ");
            books[i].Price = double.Parse(Console.ReadLine());
        }

        // Display book details
        Console.WriteLine("\n--- Book Details ---");
        for (int i = 0; i < 3; i++)
        {
            Console.WriteLine($"\nBook {i + 1}:");
            Console.WriteLine($"ID: {books[i].BookID}");
            Console.WriteLine($"Title: {books[i].Title}");
            Console.WriteLine($"Author: {books[i].Author}");
            Console.WriteLine($"Price: {books[i].Price}");
        }
    }
}


 <img width="568" height="705" alt="image" src="https://github.com/user-attachments/assets/e51985b6-cf90-457a-a7ca-f12f36238b9c" />
  <img width="658" height="335" alt="image" src="https://github.com/user-attachments/assets/c673e2ab-05fa-4a1d-b2d8-a8ac9eb7001d" />

~4.3

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

struct Employee
{
    public int ID;
    public string Name;
    public double Salary;
}

class Program
{
    static void Main(string[] args)
    {
        Console.Write("Enter number of employees: ");
        int n = int.Parse(Console.ReadLine());

        Employee[] employees = new Employee[n];

        // Input details
        for (int i = 0; i < n; i++)
        {
            Console.WriteLine($"\nEnter details of Employee {i + 1}:");

            Console.Write("Enter ID: ");
            employees[i].ID = int.Parse(Console.ReadLine());

            Console.Write("Enter Name: ");
            employees[i].Name = Console.ReadLine();

            Console.Write("Enter Salary: ");
            employees[i].Salary = double.Parse(Console.ReadLine());
        }

        // Display details
        Console.WriteLine("\n--- Employee Details ---");
        for (int i = 0; i < n; i++)
        {
            Console.WriteLine($"\nEmployee {i + 1}:");
            Console.WriteLine($"ID: {employees[i].ID}");
            Console.WriteLine($"Name: {employees[i].Name}");
            Console.WriteLine($"Salary: {employees[i].Salary}");
        }
    }
}

 <img width="422" height="546" alt="image" src="https://github.com/user-attachments/assets/1a3ea171-5c3a-483c-9b55-e75acad784b9" />

~4.4

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

struct Employee
{
    public int ID;
    public string Name;
    public double Salary;
}

class Program
{
    static void Main(string[] args)
    {
        Console.Write("Enter number of employees: ");
        int n = int.Parse(Console.ReadLine());

        Employee[] employees = new Employee[n];

        // Input details
        for (int i = 0; i < n; i++)
        {
            Console.WriteLine($"\nEnter details of Employee {i + 1}:");

            Console.Write("Enter ID: ");
            employees[i].ID = int.Parse(Console.ReadLine());

            Console.Write("Enter Name: ");
            employees[i].Name = Console.ReadLine();

            Console.Write("Enter Salary: ");
            employees[i].Salary = double.Parse(Console.ReadLine());
        }

        // Display employees with salary > 50000
        Console.WriteLine("\n--- Employees with Salary > 50000 ---");
        bool found = false;
        for (int i = 0; i < n; i++)
        {
            if (employees[i].Salary > 50000)
            {
                found = true;
                Console.WriteLine($"\nEmployee {i + 1}:");
                Console.WriteLine($"ID: {employees[i].ID}");
                Console.WriteLine($"Name: {employees[i].Name}");
                Console.WriteLine($"Salary: {employees[i].Salary}");
            }
        }

        if (!found)
        {
            Console.WriteLine("\nNo employees found with salary greater than 50000.");
        }
    }
}

 <img width="546" height="426" alt="image" src="https://github.com/user-attachments/assets/e9a5d213-1f09-4e7f-aa0e-113b3209a786" />

~4.5

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;



struct Employee
{
    public int ID;
    public string Name;
    public double Salary;
}

class Program
{
    static void Main(string[] args)
    {
        Console.Write("Enter number of employees: ");
        int n = int.Parse(Console.ReadLine());

        Employee[] employees = new Employee[n];

        // Input details
        for (int i = 0; i < n; i++)
        {
            Console.WriteLine($"\nEnter details of Employee {i + 1}:");

            Console.Write("Enter ID: ");
            employees[i].ID = int.Parse(Console.ReadLine());

            Console.Write("Enter Name: ");
            employees[i].Name = Console.ReadLine();

            Console.Write("Enter Salary: ");
            employees[i].Salary = double.Parse(Console.ReadLine());
        }

        // Search employee by ID
        Console.Write("\nEnter the Employee ID to search: ");
        int searchID = int.Parse(Console.ReadLine());
        bool found = false;

        for (int i = 0; i < n; i++)
        {
            if (employees[i].ID == searchID)
            {
                found = true;
                Console.WriteLine("\n--- Employee Found ---");
                Console.WriteLine($"ID: {employees[i].ID}");
                Console.WriteLine($"Name: {employees[i].Name}");
                Console.WriteLine($"Salary: {employees[i].Salary}");
                break; // Exit loop after finding the employee
            }
        }

        if (!found)
        {
            Console.WriteLine("\nEmployee with the given ID was not found.");
        }
    }
}

 <img width="548" height="435" alt="image" src="https://github.com/user-attachments/assets/94ff289a-190d-4e65-9111-da70e9769bc9" />

~4.6

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;



struct Employee
{
    public int ID;
    public string Name;
    public double Salary;
}

class Program
{
    static void Main(string[] args)
    {
        int[] numbers = { 45, 12, 78, 34, 89, 23, 56, 91, 5, 67 };

        int largest = numbers[0];
        int smallest = numbers[0];

        for (int i = 1; i < numbers.Length; i++)
        {
            if (numbers[i] > largest)
                largest = numbers[i];

            if (numbers[i] < smallest)
                smallest = numbers[i];
        }

        Console.WriteLine("Numbers: " + string.Join(", ", numbers));
        Console.WriteLine($"\nLargest number: {largest}");
        Console.WriteLine($"Smallest number: {smallest}");

    }
}

 <img width="663" height="117" alt="image" src="https://github.com/user-attachments/assets/9e5f21db-0b49-4d63-b726-57882241ee8f" />

~4.6

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;



struct Student
{
    public int RollNo;
    public string Name;
    public int[] Marks; // For 3 subjects
}

class Program
{
    static void Main(string[] args)
    {
        Console.Write("Enter number of students: ");
        int n = int.Parse(Console.ReadLine());

        Student[] students = new Student[n];

        // Input student details
        for (int i = 0; i < n; i++)
        {
            Console.WriteLine($"\nEnter details for Student {i + 1}:");

            Console.Write("Enter Roll No: ");
            students[i].RollNo = int.Parse(Console.ReadLine());

            Console.Write("Enter Name: ");
            students[i].Name = Console.ReadLine();

            students[i].Marks = new int[3];
            for (int j = 0; j < 3; j++)
            {
                Console.Write($"Enter marks for Subject {j + 1}: ");
                students[i].Marks[j] = int.Parse(Console.ReadLine());
            }
        }

        // Display student details with total and average
        Console.WriteLine("\n--- Student Details ---");
        for (int i = 0; i < n; i++)
        {
            int total = 0;
            for (int j = 0; j < 3; j++)
            {
                total += students[i].Marks[j];
            }
            double average = total / 3.0;

            Console.WriteLine($"\nRoll No: {students[i].RollNo}");
            Console.WriteLine($"Name: {students[i].Name}");
            Console.WriteLine($"Marks: {string.Join(", ", students[i].Marks)}");
            Console.WriteLine($"Total Marks: {total}");
            Console.WriteLine($"Average Marks: {average:F2}");
        }
    }
}

 <img width="556" height="695" alt="image" src="https://github.com/user-attachments/assets/0e8f33cd-f438-42a0-a6fb-cfa5756f0d47" />
