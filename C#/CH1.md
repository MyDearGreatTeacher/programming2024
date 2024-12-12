#


## 
```c#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ex0101
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello C#...");
        }
    }
}
```


## 
```c#
//using System;
using static System.Console;

/*namespace Ex0201
{
   internal class Demo01
   {
      static void Main(string[] args)
      {
         WriteLine("Hello World!");
         WriteLine("Visual C#...");
         ReadKey();
      }
   }
}*/

//使用C# 9.0 Top-level Statement
//System.Console.WriteLine("Hi! 我是.NET 5.0...");

//使用C# 9.0 Top-level Statement, 加入名稱空間
/*using System;
Console.WriteLine("Hi! 我是.NET 5.0...");*/

//使用C# 9.0 Top-level Statement, using敘述滙入靜態類別
WriteLine("Hi! 我是.NET 5.0...");
```


## 
```c#
// See https://aka.ms/new-console-template for more information
Console.WriteLine("Hello, World!");
Console.WriteLine(Environment.OSVersion.VersionString);
```


## 
```c#
using System;

namespace Ex0104
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```


## 
```c#
// See https://aka.ms/new-console-template for more information
//Console.WriteLine("Hello, World!");
using static System.Console;
//Console.WriteLine("我是.NET 6.0");
WriteLine("我是.NET 6.0");
```


## 
```c#
//滙入名稱空間
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;


namespace Ex0203
{
    internal class Demo03
    {
        //* 傳統的主控台應用程式
        //作業系統：Windows
        static void Main(string[] args)
        {
            Console.WriteLine("Hello .NET Framework!");            
        }
    }
}
```


## 
```c#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using static System.Console;   //滙入靜態類別

namespace Ex0204
{
   internal class Program
   {
      static void Main()
      {
         Write("請輸入你的名字：");
         string name = ReadLine();
         WriteLine($"Good Day! {name}");
      }
   }
}
```


## 
```c#
using System;   //滙入System名稱空間

class Demo03   //類別名稱
{
   static void Main()   //主程式
   {
      Console.Write("請輸入名稱：");
      string? name = Console.ReadLine();
      Console.Write("請輸入提款金額：");
      int money = Convert.ToInt32(Console.ReadLine());
      Console.WriteLine($"Hi! {name}, 提款金額：{money:C0}");
   }
}
```

# ch3
## 
```c#
using System;
using static System.Console;

namespace Ex0301
{
   internal class Program
   {
      static void Main(string[] args)
      {
         int num1 = 1_23_456;      //任意底線
         long num2 = 456_789_123L; //長整數加後置字元L
         //屬性MaxValue、MinValue取得long型別最大和最小值
         long max = Int64.MaxValue;
         long min = Int64.MinValue;
         int num3 = 0b1011_110;   //二進位

         int num4 = 0b_111_110_10; //0b  2進位
         int num5 = 0x_FB12;       //0x 16進位
         WriteLine($"Number: {num1:N0}, {num2:n0}");

         //以十進位輸出變數num3, num4, num5
         WriteLine($"二進位變十進位：{num3:D5}, {num4:d5}, {num5}");

         //GetType()方法回傳資料型別
         WriteLine($".NET Framework型別: {num1.GetType()}");
         WriteLine($"最大值: {max}, \n最小值: {min}");
      }
   }
}
```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```


## 
```c#

```
