# .NET
Practical 1

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

PRACTICAL 2

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

PRACTICAL 3

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

PRACTICAL 4
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

 PRACTICAL 5 
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

PRACTICAL 6
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

PRACTICAL 7

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

PRACTICAL 8

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


PRACTICAL 9

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


PRACTICAL 10 

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


PRACTICAL 11

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
