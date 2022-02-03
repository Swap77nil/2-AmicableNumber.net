# AmicableNumber.net
.NET Program<br>
using System;<br>
namespace Exercises<br>
{<br>
    class AmicableNumber<br>
    {<br>
        static void Main(String[] args)<br>
        {<br>
            int num1,num2,sum1=0,sum2=0;<br>
            Console.WriteLine("\n........AMICABLE NUMBERS........\n");<br>
            Console.Write("\nEnter the First Number:");<br>
            num1 = Convert.ToInt32(Console.ReadLine());<br>
            Console.Write("\nEnter the Second Number:");<br>
            num2 = Convert.ToInt32(Console.ReadLine());<br>
            for (int i = 1; i < num1; i++)<br>
            {<br>
                if (num1 % i == 0)<br>
                {<br>
                    sum1 += i;<br>
                }<br>
            }<br>
            for (int i = 1; i < num2; i++)<br>
            {<br>
                if (num2 % i == 0)<br>
                {<br>
                    sum2 += i;<br>
                }<br>
            }<br>
            if(num1 == sum2 && num2 == sum1)<br>
            {<br>
                Console.WriteLine("\nThe numbers {0} and {1} are amicable.", num1, num2);<br>
            }<br>
            else<br>
            {<br>
                Console.WriteLine("\nThe numbers {0} and {1} are not amicable.", num1, num2);<br>
            }<br>
        }<br>
    }<br>
}<br>

OUTPUT:-
![Screenshot (9)](https://user-images.githubusercontent.com/98145032/152291167-1886bff9-5979-4b57-90df-565a4c5058f4.png)
![Screenshot (11)](https://user-images.githubusercontent.com/98145032/152291502-2753aa62-ca12-4b11-a58f-c580cbe0b333.png)
