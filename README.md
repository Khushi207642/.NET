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

