using System;
namespace CSharp_Shell
{
	public class program
	{
		int x=0;
		void print(int x,int y)
		{
			x=x+y;
			Console.WriteLine(x);
		}
		public static void Main()
		{
			program p=new program();
			p.print(5,5);
		}
		}
	}
