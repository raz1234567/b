# b
for test
using System;

namespace ConsoleApp1
{
    class Program
    {
        static void Main1(Arg[], string)
        {
            Console.WriteLine("Hello World!");


            float num = 10.76f;
            int num2 = (int)num;
            Console.WriteLine(num2);


            int n1 = 5, n2 = 3;
            Console.WriteLine(@"namaayesh a'ashari e taghsim {0}", ((double)n1 / n2));


            int age;
            Console.WriteLine("enter your age");
            //age = Convert.ToInt32(Console.ReadLine());
            //رشته ی گرفته شده از کاربر را به عدد تبدیل می کند


            int[] numbers = new int[5];
            //یا
            int[] numbers1 ={ 1, 2, 3 };

            //numbers2.length

            int[,] numbers3 = new int[3, 5];
            //دوبعدی
            //numbers3.getlength()
            int[,] numbers4 = { { 1,2,3,},
                                { 4,5,6 },
                                { 7,8,9 }};
            for(int i=0; i<numbers4.GetLength(0); i++)
            {
                for(int j=0; j<numbers4.GetLength(1); j++)
                {
                    Console.WriteLine(numbers4[i, j] + "");
                }
                Console.WriteLine();
            }




            int[][] dandaane = new int[3][];
            dandaane[0] = new int[5];
            dandaane[0] = new int[1];
            dandaane[0] = new int[8];

            int[][] dandaane = new int[3][];
            dandaane[0] = new int[5] { 1, 2, 3, 4, 5 };
            dandaane[0] = new int[1] { 6 };
            dandaane[0] = new int[8];
        }
    }
}
